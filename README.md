
# Mask detection using YOLOv4

![image5](https://user-images.githubusercontent.com/78642104/171058495-8ff1e87a-4172-423a-bf01-dd8ed83127ec.png)

This repository contains the 4 custom files needed. (i.e. yolov4-custom.cfg, obj.data, obj.names and process.py) except obj.zip(labeled images).

I had uploaded my colab notebook also where I had created a  `custom object detector using Yolo-v4` to detect whether a person is wearing a mask or not. I had imported darknet in my project from https://github.com/AlexeyAB/darknet/.

Here I had used only two labels:

1.) Mask

2.) Without Mask

The obj.zip file contains 1510 images along with their YOLO labeled text files. I have labeled around 1350 of these and downloaded 149 labeled images from roboflow. I have given the links for my dataset sources at the bottom. You can download it from my drive - 

https://drive.google.com/file/d/15qIgsoo3m6P4E7GhaOYPHFe4zsrj55g3/view?usp=sharing

This dataset has mostly close-up images (around 1300) and very few long-shot images (around 200). 

# Interesting Result 

See Elon Msuk is not wearing mask 😂

![image6](https://user-images.githubusercontent.com/78642104/235326569-0f7b3516-bdb0-4275-a277-77e78422e344.png)

**Note:** You can see result on more images in prediction folder.
