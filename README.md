
  <table align = "center" ><tr align = "center" height = "200" ><td align = "center" width="1200">
    <img align = "center" width="300" src="./Images/Logo1.PNG">
  </td></tr></table>


# ML Project: Keep America Beautiful Litter Processor 

  - Class: CIS 490 - Project Management & Practice
  - Professor: Dr. Shaun-inn Wuu 
  - Client: Jared Macshane
  - Spring 2022
</div>
<!-- Live demo [_here_](https://www.example.com).--> <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [General Info](#general-information)
* [Requirements](#requirements)
* [Timeline](#timeline)
* [System View](#system-view)
* [Main Dependencies](#main-dependencies)
* [Implementation](#implementation)
* [Deliverables](#deliverables)
* [Development Process](#development-process)
* [Team](#team)

## General Information
Keep America Beautiful is a leading national nonprofit organization that inspires and educates people to take action every day to improve and beautify their community environment. They envision a country in which every community is a clean, green, and beautiful place to live.

The Sushi Team is grateful for the opportunity to work with Keep America Beautiful in developing a Machine Learning algorithm that will detect instances of litter in Google Street images. While the aimed general usage of the algorithm is for Keep America Beautiful's Web App team, the algorithm can be used without them. 

## Requirements
<p align = "center">
  <img src="./Images/Requirements.png">
</p>

## Timeline
![plot](./Images/timeline.png)



## System View
<p align = "center">
  <img width="400" height="400" src="./Images/System_Overview.png">
</p>

## Main Dependencies
- [Google Cloud Platform](https://cloud.google.com/).
- [YOLOv5 Object Detection Model](https://github.com/ultralytics/yolov5).
- [RoboFlow](https://roboflow.com/).

- [Our documentation for Google Cloud](https://github.com/SushiTeam2022/KAB-ML/blob/main/Documentation/Machine%20Requirements.pdf).
- [Our documentation for YOLOv5](https://github.com/SushiTeam2022/KAB-ML/blob/main/Documentation/YOLOv5%20Documentation.pdf).
- [Our documentation for RoboFlow](https://github.com/SushiTeam2022/KAB-ML/blob/main/Documentation/RoboFlow%20Guide.pdf).


## Implementation
The boneworks of our system comes through the utilization of a Google Cloud server, the integration of the the YOLOv5 object detection model - with training and testing to detect litter in Google Street images, and the development of a Python script to formulate the process of our system - pertaining to inputs, outputs, and it’s ability to do frequent operations of processing Google Street images.

In order to train the YOLOv5 model to be able to detect litter in Google Street images, we also had to utilize Roboflow, a general purpose Machine Learning site, in order to create a Google Street image dataset.

### Dataset Example
<p align = "center">  
  <img height="500" src="./Images/Roboflow_dataset.png">
</p>

Once the YOLOv5 model had been trained with the Google Street image dataset, 

<p align = "center">  
  <img align="right" width="300" height="300" src="./SAMPLES/Keith_GS/Image3.jpg">
  <img align="leftt" width="300" height="300" src="./SAMPLES/Keith_GS_1280_Output/Image3.jpg">
</p>
<p align = "center">  
  <img align="right" width="300" height="300" src="./SAMPLES/Keith_GS/Image4.jpg">
  <img align="leftt" width="300" height="300" src="./SAMPLES/Keith_GS_1280_Output/Image4.jpg">
 
 
## Deliverables
-	Machine Learning code/algorithm that will be compatible and usable with the Web App team.
- Algorithm will produce data that will include:
  - Detection of litter in an image.
  -	Track total amount of litter.
  -	Show the detection accuracy in testing (e.g. 90% sure this is a Plastic bottle-Litter). -	Striving for/Conditional features: 
-	Categorize the litter (e.g. Plastic bottle, Paper bag).

## Development Process
Keep America Beautiful is a leading national nonprofit organization that inspires and educates people to take action every day to improve and beautify their community environment. They envision a country in which every community is a clean, green, and beautiful place to live.

The Sushi Team is grateful for the opportunity to work with Keep America Beautiful in developing a machine learning algorithm to detect litter through the colllection of google street images. Also, the Sushi Team partnered up with a web app team which are contributing in developing a web application that send us a google street images as input and the machine learning process it and their application collect them and use them.

The Sushi Team merge two dataset, one develop by fixIT and the other was collected by the web app team. The dataset were annotated, reviewed and submitted for training.  The Sushi Team uses the machines learning Algorithm YoloV5 to detect the amount of litter in the google street images. The YoloV5 uses a customized weights for pre-train and later train the new merged dataset.    
                                                             

## Team
Noah | Juan | Keith | Jordan F. | Miguel M.
