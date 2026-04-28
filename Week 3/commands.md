## Segmentation
yolo predict model=yolov8n-seg.pt source=... save=True

## Convert to video
ffmpeg -framerate 30 -i frame_%04d.jpg -c:v libx264 -pix_fmt yuv420p segmented_video.mp4

## Add audio
ffmpeg -i segmented_video.mp4 -i new_audio.mp3 -c:v copy -c:a aac -shortest final_segmented_video.mp4