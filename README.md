# Laboratory Work 6 — YOLOv7

## Topic
Working with open-source code.

## Article
**YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors**

Authors: Chien-Yao Wang, Alexey Bochkovskiy, Hong-Yuan Mark Liao.

## Original repository
https://github.com/WongKinYiu/yolov7

## Task
The purpose of this laboratory work is to study open-source code, run the YOLOv7 object detection model and demonstrate its operation on a test image.

## Environment
- Python 3.10.11
- PyTorch
- YOLOv7

## Run

```bash
python detect.py --weights yolov7.pt --conf 0.25 --img-size 640 --source inference/images/horses.jpg
