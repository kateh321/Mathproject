# Classification of Blood cells using Neural Networks

## Overview
The aim of this project is to design convolutional neural networks to classify blood cells and compare different models metrics. 

## Dataset
Dataset can be found at:
* !https://data.mendeley.com/datasets/snkd93bnjr/1

It contains over 17000 images of different blood cells.
## Requirements
* Numpy
* matplotlib.pyplot
* seaborn
* tensorflow
* keras
* sklearn
* split-folders

A text file above, can be execuated in the collab notebook using !pip install requirements.


# Setting up 

The programs above were created using Google collab, here it will explain how to set up a google collab account and run the programs. 

## Step 1
First, an account is required to use google collab, if you do not have one you can sign up at https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp

Once an account is created go to https://colab.research.google.com/?utm_source=scs-index and create a new notebook.

![gdrive.jpg](https://i.postimg.cc/tgdyHV1Y/gdrive.jpg)](https://postimg.cc/qt7WsqxT)



## Step 2

Mount your google drive to collab by using the code below.

```
from google.colab import drive
drive.mount('/content/gdrive')
```

In the lefthand corner of your notebook as can be seen below marked by the red square is three vertical lines, if you click it and then click the folder which is marked in the image below you can see the list of files.

[![gdrive.jpg](https://i.postimg.cc/c4cbZMTq/gdrive.jpg)](https://postimg.cc/zVVjFh9p)

Change directory to be located in the drive directory using the code below.

```
%cd %cd /content/gdrive/MyDrive/

```


```
%cd 



## Step 3.

Clone the github respitory to your google drive using the code below.

```
!git clone https://github.com/kateh321/Mathproject

```


The files are now saved on your google drive ready to be used, go to https://drive.google.com/drive/my-drive and a new folder Mathproject should 
be present with the programs in it.


## Step 4

The libraries required for this project are listed below

## Requirements
* Numpy
* matplotlib.pyplot
* seaborn
* tensorflow
* keras
* sklearn
* split-folders

All libraries except for split-folders are preinstalled in collab. Use the following command to install split folders.

```
!pip install split-folders
```

## Step 5

Final step is to click run all and the program should run start to finish.

[![run.jpg](https://i.postimg.cc/wMN1KQmn/run.jpg)](https://postimg.cc/H8pYX53t)

Approximate run times for each program using GPU is:
math_model_1.ipyjb -  33 min 33 seconds
math_model_2.ipyjb - 
VVG16_model.ipy -

Please note the run times can vary as google collab uses different GPUs overtime and resources are not always guaranteed.





