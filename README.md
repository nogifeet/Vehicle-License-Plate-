# Vehicle-License-Plate-
Vehicle License Plate Detection Using Yolo_v3 darknet
For a more detailed explanation refer to Introduction to Yolo_v3 License Plate Datector

Python Packages:
Numpy, Pandas, Random, Matplotlib, OpenCV, Tesseract and PIL

Tools:
Git, Powershell, Windows SDK, Cuda Toolkit, cuDNN, Jupyter Notebook, Google Collab, OIDv4_Toolkit and darknet

Helper Function:
create_annotation.py
create_train.py
create_obj.py

---------------------------------------------------------------OBJECTIVE-----------------------------------------------------------
1.Download and Create Usage for Darknet
2.Download Images and Labels using OIDv4_Toolkit
3.Create custom training files and configration files.
4.Test trained yolo_v3 model 
5.Get cropped object of interest from image
6.Use Tesseract for reading license plate from cropped images

---------------------------------------------------------------CONFIGURE TRAINING FILES----------------------------------------------
Obj.Classes:
Traffic sign
Vehicle registration plate

Obj.Data:
classes=2
train= data/Vehicle/train.txt
valid= data/Vehicle/valid.txt
names= data/Vehicle/obj.names
backup= backup/Vehicle/

train.txt & valid.txt:
data/Vehicle/Images/00068f1248eacccf.jpg
data/Vehicle/Images/00234c09cb4fa8e3.jpg
.......
data/Vehicle/Images/004cda0e4eb7a750.jpg
data/Vehicle/Images/0059670bdb468e0a.jpg
data/Vehicle/Images/005e1faed531ae7e.jpg

-----------------------------------------------------------------------RESOURCES---------------------------------------------------------
Darknet:
Yolo_v3 weights:
Yolo_v3 architecture:
OIDv4_Toolkit:
CUDA installation guide:
Youtube Link:
Nvidia Driver:
Visual Studio:
Windows SDK:
CMAKE:
OpenCV:
Youtube_video:
Cuda Installation Guide:
