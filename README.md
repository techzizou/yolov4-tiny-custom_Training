

# Training a custom Yolov4-tiny detector for mask detection


## What is YOLOv4-tiny?

YOLOv4-tiny is proposed based on YOLOv4 to simple the network structure and reduce parameters, which makes it be suitable for developing on mobile and embedded devices. YOLOv4-tiny is the compressed version of YOLOv4. It has only two YOLO heads as opposed to three in YOLOv4. It is trained from 29 pre-trained convolutional layers.

The FPS (Frames Per Second) in YOLOv4-tiny is approximately eight times that of YOLOv4. However, YOLOv4-tiny gets 40 mAP@ IoU=0.5(AP50) on the MS COCO dataset as compared to 65.7 of YOLOv4.

![](vs.png)


# Object Detection for masks

![](a.gif)


Colab tutorial for training a custom Yolov4-tiny detector.

https://colab.research.google.com/drive/1hQO4nOoD6RDxdbz3C1YSiifTsyZjZpYm?usp=sharing

Check out my Medium article on this.

https://medium.com/@techzizou007/training-a-custom-detector-for-mask-detection-using-yolov4-tiny-darknet-b58be08c9593

Also , check out my YouTube video on this 

[Youtube Link](https://www.youtube.com)



# **CREDITS**

   **REFERENCES**
 
*    [Alexey AB GitHub ](https://github.com/AlexeyAB/darknet)

*    [pjreddie Github ](https://github.com/pjreddie/darknet)

*    [theAIGuysCode GitHub](https://github.com/theAIGuysCode/YOLOv4-Cloud-Tutorial)


   **DATASET SOURCES**

You can download labeled datasets from the sites mentioned below. These sites contain images of many classes along with their annotations/labels in multiple formats such as the YOLO_DARKNET txt files and the PASCAL_VOC xml files.

*   [Open Images Dataset by Google](https://storage.googleapis.com/openimages/web/index.html)

*   [Kaggle Datasets](https://www.kaggle.com/datasets)

*   [Roboflow Public Datasets](https://public.roboflow.com/)

*   [VisualData Datasets](https://www.visualdata.io/discovery)


   **MASK DATASET SOURCES**

*   [Prajnasb Github](https://github.com/prajnasb/observations)

*   [Andrewmvd Kaggle](https://www.kaggle.com/andrewmvd/face-mask-detection)

*   [X-zhangyang Github](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset)

*   [Chandrikadeb7 Github](https://github.com/chandrikadeb7/Face-Mask-Detection)

   **VIDEO SOURCES**
    
*   [Pexels site](https://www.pexels.com/)

![](test2-tiny.gif)
