# HBset-A_Human_Behavior_Dataset_for_YOLO_application
This is an open multiple human behaviors image dataset (HBset) for object detection model development applied in the public emergency satey.
The dataset categories the common human behaviours and groups in the public emergency as 8 classes:  

*1. normal_person  
2. kid  
3. holding_crutch  
4. holding_baby  
5. lagging_luggage  
6. playing_phone  
7. pregnancy  
8. using_wheelchair*

Accurately detecting these behaviours is very helpful for emergency rescue and evacuation strategy-making. 
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
@misc{HBset-A_Human_Behavior_Dataset_for_YOLO_application,
    title={HBset-A_Human_Behavior_Dataset_for_YOLO_application},
    author={Yifei DING},
    howpublished = {\url{https://github.com/JDmoric/HBset-A_Human_Behavior_Dataset_for_YOLO_Application}},
    year={2023}
}
