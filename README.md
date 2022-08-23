[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/aquavision-automating-the-detection-of-waste/object-detection-on-aquatrash)](https://paperswithcode.com/sota/object-detection-on-aquatrash?p=aquavision-automating-the-detection-of-waste)
[![harshpanwar](https://img.shields.io/twitter/follow/harsh__panwar?style=social)](https://mobile.twitter.com/harsh__panwar)

# AquaVision
Official dataset introduced in the paper [AquaVision: Automating the detection of waste in water bodies using deep transfer learning](https://doi.org/10.1016/j.cscee.2020.100026)

# AquaTrash

This dataset contains 369 images of Trash used for deep learning. Each image is manually labelled by our team for accurate detections making a total of 470 bounding boxes. There are total 4 classes {(0: glass), (1:paper), (2:metal), (3:plastic)}

# Usage
1. Each image stored in the images folder has one or more labelled bounding boxes. 
2. The labelled bounding box are stored in the annotations.csv file with the following format:
  ```
  <file_path>,<x_min>,<y_min>,<x_max>,<y_max>
  ```



<div align="center">
  <div class="column">
    <img src="https://raw.githubusercontent.com/wiki/pedropro/TACO/images/1.png" width="17%" hspace="3">
    <img src="https://raw.githubusercontent.com/wiki/pedropro/TACO/images/2.png" width="17%" hspace="3">
    <img src="https://raw.githubusercontent.com/wiki/pedropro/TACO/images/3.png" width="17%" hspace="3">
    <img src="https://raw.githubusercontent.com/wiki/pedropro/TACO/images/4.png" width="17%" hspace="3">
    <img src="https://raw.githubusercontent.com/wiki/pedropro/TACO/images/5.png" width="17%" hspace="3">
  </div>
</div>
</br>

The images are licensed under CC BY 4.0 License by Pedro F Proença and Pedro Simões.
Visit  @ [tacodataset.org](http://tacodataset.org) for more information.
```
Both the images and annotations provided by this dataset are all under free copyright licences.
While the annotations are licenced under CC BY 4.0, images may be under different specific public 
licences since these were obtained from different sources and users. The licence along with the 
original URL of each individual image are referenced in the accompanying annotation file. If the 
licence entry is missing, then this is by default: CC BY 4.0.
```
