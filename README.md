# State of Art Segmentation Network Architectures
This Repository contains the basic architectural description and implementation of some state of the art Segmentation Networks. Image 
Segmentation is the process of identifying parts of the image and understanding what object they belong to. It lays the basis for performing object detection
and classification. 

<p align="center">
    <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/segmentation.png">
</p>


## Table of Contents:
  + [Datasets](#datasets)
  + [U-Net Architecture](#u-net-architecture)
  + [Seg-Net Architecture](#seg-net-architecture)
  + [Res-Net Architecture](#res-net-architecture)
  + [FCN-8 Architecture](#fcn-8-architecture)

### Datasets:
I have used two different datasets to implement these architectures. I have added both the original images and masks with its numpy files. 

  + Top View Heads Dataset: can be downloaded [here](https://drive.google.com/open?id=1op3raw2kRKmKOmsVhBK3RXoIXewwR_ug)
  + Lungs Segmentation from chest X-rays Dataset: can be downloaded [here](https://drive.google.com/open?id=1-HbRytWbfBGQ8y3Nw555QpZM95urda4V)
  

### U-Net Architecture:
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/unet-architecture.png"; width=70%; height=70%>
  <br>
  <em> An illustration of U-NET Architecture </em>
</p>

#### Implementation and Results:

[Code: Google Colab Notebook for Lungs Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/U-NET%20Architecture/UNET-implementation-Lungs%20Segmentation%20from%20Chest%20X-rays.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/unet-Lungs.png">
</p>

[Code: Google Colab Notebook for TVH Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/U-NET%20Architecture/UNET-implementation-Lungs%20Segmentation%20from%20Chest%20X-rays.ipynbhttps://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/U-NET%20Architecture/UNET-implementation-TOP%20VIEW%20HEADS%20Dataset.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/unet-TVH.png">
</p>


### Seg-Net Architecture:
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/segnet-architecture.png"; width=70%; height=70%>
  <br>
  <em> An illustration of Seg-NET Architecture </em>
</p>

#### Implementation and Results:

[Code: Google Colab Notebook for TVH Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/Seg-NET%20Architecture/Seg-NET-implementation-TOP%20VIEW%20HEADS%20Dataset.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/segnnet-TVH.png">
</p>

### Res-Net Architecture:
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/resnet-architecture.png"; width=70%; height=70%>
  <br>
  <em> An illustration of Res-NET Architecture </em>
</p>

#### Implementation and Results:

[Code: Google Colab Notebook for TVH Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/Res-NET%20Architecture/Res-NET-implementation-TOP%20VIEW%20HEADS%20Dataset.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/resnnet-TVH.png">
</p>

### FCN-8 Architecture:
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/fcn8-architecture.png"; width=70%; height=70%>
  <br>
  <em> An illustration of FCN-8 Architecture </em>
</p>  

#### Implementation and Results:
[Code: Google Colab Notebook for Lungs Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/FCN8%20Architecture/FCN8-implementation-Lungs%20Segmentation%20from%20Chest%20X-rays%20Dataset.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/fcn-Lungs.png">
</p>

[Code: Google Colab Notebook for TVH Segmentation](https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/FCN8%20Architecture/FCN8-implementation-TOP%20VIEW%20HEADS%20Dataset.ipynb)
<p align="center">
  <img src="https://github.com/zeeshannisar/State-of-Art-Segmentation-Network-Architectures/blob/master/ReadMe%20Images/fcn-TVH.png">
</p>


