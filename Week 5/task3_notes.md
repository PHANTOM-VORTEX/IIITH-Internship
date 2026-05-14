# 05WT3 Completed

Custom YOLO model training completed using the resized dataset.

## Training Configuration
- Model: YOLOv8 Nano (yolov8n.pt)
- Epochs: 100
- Image Size: 384
- Device: NVIDIA RTX 4050 GPU

## Observations
Training and validation analytics were generated.

Validation classification loss showed an early spike and then stabilized.
No strong overfitting trend was observed within the chosen epoch range.

## Generated Outputs
Training outputs saved under:
runs/detect/train2/

Important files:
- weights/best.pt
- weights/last.pt
- results.png
- results.csv