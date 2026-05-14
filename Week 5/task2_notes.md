# 05WT2 Completed

Resized the custom YOLO dataset images using FFmpeg while preserving aspect ratio.

Scaling used:
384:-1

Reason:
Bounding box labels remain valid because YOLO annotations are stored in normalized coordinates and aspect ratio was preserved.

Resized dataset prepared:

dataset_resized/
- images/train
- images/val
- images/test
- labels/train
- labels/val
- data.yaml
- train.txt
- val.txt