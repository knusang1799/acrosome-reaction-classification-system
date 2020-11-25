# acrosome-reaction-classification-system
Acrosome reaction classification system (ARCS) is detecting algorithm for analysis of acrosome reaction (AR) of the mammalian sperm in the microscopic images. The ARCS repository contains trained models for detection of the AR and test images. 

The codes are modified in object_detection_tutorial.ipynb of the TensorFlow Object Detection API.
You can see the original version of the codes in the TensorFlow Object Detection API.

https://github.com/tensorflow/models/tree/master/research/object_detection


The files is edited for detection of the acrosome reaction of sperm by Dr. Sang-Hee Lee.
If you have question regarding codes and information, please send the email.

Email: knusang1799@gmail.com
    
Additionally, you can download acrosome reaction classification system (ARCS) containing trained models based on ResNet 50 and Inception-ResNet v2.
    
Github: https://github.com/knusang1799/acrosome-reaction-classification-system.git

Installation of Tensorflow Object Detection API. 

### 1. Installation of the ARCS

#### 1) Installation of annaconda 3

please see the url:
https://docs.anaconda.com/anaconda/install/

#### 2) Create virtual environment

```
conda create -n tensorflow1
```

#### 3) Installation of the packages

```
conda install tensorflow == 1.14.0
conda install pillow lxml Cython jupyter matplotlib pandas
pip install opencv-python
```

#### 4) Dowload ARCS gihub
 
```
https://github.com/tensorflow/models/tree/master/research/object_detection
```

#### 5) Download the trained models in models

```
ResNet-400-mag
  https://drive.google.com/file/d/13Cezk-9A8FZMOXIXuCA83jTWh0FUNSX8/view?usp=sharing
ResNet-1000-mag
  https://drive.google.com/file/d/1YEg9CPAyyj3P-1jgHFDiAMcQXwOUTaNV/view?usp=sharing
Incep-Res-400-mag
  https://drive.google.com/file/d/11UaEdgu9CMUCRxsyvtpuAJptO-Owr4dN/view?usp=sharing
Incep-Res-1000-mag
  https://drive.google.com/file/d/1oMuq2AaDW1b4JQDXPfEYFRorcJJ7Xh41/view?usp=sharing
```

### 2. 
