# Tracking_Pipeline

- Tracking_Pipeline helps you to solve the tracking problem more easily

- I integrate detection algorithms like: Yolov5, Yolov4, YoloX, NanoDet

- And tracking algorithms like : Sort, Deepsort, Motpy, ByteTrack, Norfair



## **How to use sample** 

### Setup
  - pip install -r requirements.txt

### Yolov5

  - download : https://drive.google.com/file/d/1Z3miSUwmKMxbMzucjCrUVvdKpcqiq5_P/view?usp=sharing
  - put at : Tracking_Pipeline/Detection/yolov5/weights

### Yolov4

  - download : https://drive.google.com/file/d/1SgNJYjpc568K0RZPgs7a1RAydbe6kcRQ/view?usp=sharing
  - put at : Tracking_Pipeline/Detection/yolov4/weights

### YoloX 

  - download : https://drive.google.com/file/d/1R9SVlocFeInt2Z7fNujYl0CqdqVMX5_c/view?usp=sharing
  - put at : Tracking_Pipeline/Detection/yolox/weights

### NanoDet

  - download : https://drive.google.com/file/d/1fupJv-pziAgg0v9dliP2MFqVDdukVqRP/view?usp=sharing
  - put at : Tracking_Pipeline/Detection/nanodet/weights

### Deepsort :

  - download : https://drive.google.com/file/d/1onB8c0BOO4xhRD1k2erXGz6P-UU-r4Iy/view?usp=sharing
  - put at : Tracking_Pipeline/Tracking/deep_sort/deep/checkpoint

### Modify algorithm in Tracking_Pipeline/tracking_config.yaml

Need to update with OpenVINO inferencing

Based on https://github.com/DaisyLabSolutions/tracking-pipeline
