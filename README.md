# HBset-A Human-Behavior-Dataset-for-YOLO-application
An open multiple human behavior image dataset for object detection model development
## Download link of the HBset (Images and Labels)
https://connectpolyu-my.sharepoint.com/:f:/r/personal/22038199r_connect_polyu_hk/Documents/HBset?csf=1&web=1&e=YN97Ku
## Split the dataset as train, valid and test subset
```python
python splt_data.py
```
# Train YOLO (for example, YOLOv7) using HBset 
## Download the profiles from the official YOLOv7 github repository
https://github.com/WongKinYiu/yolov7

# Citation
@article{wang2022yolov7,
  title={{YOLOv7}: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors},
  author={Wang, Chien-Yao and Bochkovskiy, Alexey and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2207.02696},
  year={2022}
}
