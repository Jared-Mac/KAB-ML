<p align = "center">
<img align="center" width="400" src="./Images/Logo1.PNG"> 
</p> 

# Project: KAABML 
  - Class: Project Management
  - Professor: Dr. Shaun-inn Wuu 
  - Project: Liter Detection Project
  - Spring 2022

> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [General Info](#general-information)
* [Requirements](#requirements)
* [Timeline](#timeline)
* [System View](#system-view)
* [Dataset](#dataset)
* [Deliverables](#deliverables)
* [Development Process](#development-process)
* [Team](#team)

## General Information
- Create a machine learning algorithm that is able to receive Google Street images, and return the results. The results are an google street
  image with the litter found marked in it. Also, it will show the confidence/accurray in the google street image. Additonally, a json   
  file that textualize the amount litter found in the pictures.
  
- The user will connect to the machine lerning algorithm with a TCP connection through Socket Programming develop in Python language.

## Requirements
- Open the Deep Learning VM Deployment Page in the GCP Marketplace( We selected the n1-highmem-4 which utilized 4 vCPUs and includes 26 GB memory) 
- Add a GPU, the NVIDIA Tesla T4 is the least expensive option and will work for our needs. 
- Verify “Install NVIDIA GPU driver automatically on first startup?” is selected. 
  (A minimum 150 GB persistent boot disk size should be selected,   however more would be better depending on the dataset being used and how much   
  information you plan on working on at once)

- git clone https://github.com/SushiTeam2022/KAAB-ML/tree/main/YOLOv5
  
- cd yolov5
 
- pip install -r requirements.txt 

## Timeline
![plot](./Images/Timeline.PNG)


## System View
<p align = "center">  
  <img width="500" height="500" src="./Images/Network_diagram.png"> 
</p>


## Dataset

<p align = "center">  
  <img align="right" width="300" height="300" src="./SAMPLES/Keith_GS/Image3.jpg">
  <img align="leftt" width="300" height="300" src="./SAMPLES/Keith_GS_1280_Output/Image3.jpg">
</p>
<p align = "center">  
  <img align="right" width="300" height="300" src="./SAMPLES/Keith_GS/Image4.jpg">
  <img align="leftt" width="300" height="300" src="./SAMPLES/Keith_GS_1280_Output/Image4.jpg">
 </p> 
 <p align = "center">  
  <img align="right" width="300" height="300" src="./SAMPLES/Keith_GS/Image6.jpg">
  <img align="leftt" width="300" height="300"" src="./SAMPLES/Keith_GS_1280_Output/Image6.jpg">
</p>
 
## Deliverables
-	Machine Learning code/algorithm that will be compatible and usable with the Web App team.
- Algorithm will produce data that will include:
  - Identification of litter in an image.
  -	The total amount of litter.
  -	Show the detection accuracy in testing (e.g. 90% sure this is a Plastic bottle-Litter). -	Striving for/Conditional features: 
-	Categorize the litter (e.g. Plastic bottle, Paper bag).

## Development Process
Keep America Beautiful is a leading national nonprofit organization that inspires and educates people to take action every day to improve and beautify their community environment. They envision a country in which every community is a clean, green, and beautiful place to live.

The Sushi Team is grateful for the opportunity to work with Keep America Beautiful in developing a machine learning algorithm to detect litter through the colllection of google street images. Also, the Sushi Team partnered up with a web app team which are contributing in developing a web application that send us a google street images as input and the machine learning process it and their application collect them and use them.

The Sushi Team merge two dataset, one develop by fixIT and the other was collected by the web app team. The dataset were annotated, reviewed and submitted for training.  The Sushi Team uses the machines learning Algorithm YoloV5 to detect the amount of litter in the google street images. The YoloV5 uses a customized weights for pre-train and later train the new merged dataset.    
                                                             

## Team
Noah | Juan | Keith | Jordan F. | Miguel M.
