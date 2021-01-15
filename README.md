

# Training a custom detector for Object Detection using YOLOv4-tiny


![](a.gif)


## Mask detection using YOLOv4-tiny

The **yolov4-tiny** folder contains the 4 custom files needed. (i.e. **yolov4-tiny-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images)

I will be sharing my labeled custom mask dataset **obj.zip** file on the following link. You can download it from here.

https://jmp.sh/6UwqTPu

The **obj.zip** file contains 1370 images along with their YOLO labeled text files. There are approximately 950 images for class **with_mask** and approximately 450 images for class **without_mask**. 

These images are mostly close-up images. If you want to download more long shot images, you can search for datasets online. There are many sites where you can find more datasets. Check out my Medium article below for links to these sites. You can add your own images and their YOLO labeled text files to the dataset. Try to find good quality images.

**<ins>NOTE</ins>**:The **yolov4-tiny-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. with_mask & without_mask). You can edit these files for your custom object dataset.

## Colab tutorial for training a custom Yolov4-tiny detector

https://colab.research.google.com/drive/1hQO4nOoD6RDxdbz3C1YSiifTsyZjZpYm?usp=sharing

## My Medium article on this

https://medium.com/@techzizou007/training-a-custom-detector-for-mask-detection-using-yolov4-tiny-darknet-b58be08c9593

## Watch my YouTube video on this 

[Youtube Link](https://www.youtube.com)

![](test2-tiny.gif)

