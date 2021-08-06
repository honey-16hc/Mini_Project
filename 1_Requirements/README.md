# Requirements
## Introduction
- With the increase in population, the number of vehicles and traffic on roads are increasing too.
- With increasing vehicular traffic and pollution on roads, managing such an amount of traffic has become very tough.
- Potholes and road surface anomalies are the primary cause of road accidents.
- Road conditions such as potholes, cracks, etc., should be identified to prevent road accidents and significant injuries.
- A pothole can put the life of a driver and fellow passengers in danger.

## Research

- Potholes are a type of road damage caused by climate changes, vehicular traffic, road aging, and low-quality construction materials.
- The major reason for formation of potholes is due to fatigue of the road surface, insufficient pavement thickness, and heavy rainfall.
- In India, 70 percent of road accidents are because of poor road conditions.
- It is a severe risk factor and also create problems for drivers as these can lead to a lot of damage to their vehicles.
- Thus to avoid accidents and vehicle damage, we need first to detect potholes, which calls for pothole image classification.

## Cost and Features

### Cost
- The cost for pothole classification is nill since it uses open source software.
- For pothole detection various tools will be used such as sensors and for deployment of software cost will be accordingly.
### Features

## Defining the System
![alt text](https://github.com/honey-16hc/Pothole_Detection_Mini_Project/blob/main/1_Requirements/swot%20analysis.jpg?raw=true)

## SWOT ANALYSIS

## 4W's and 1'H
### Who:
This will be helpful for drivers in avoiding potholes and a possible accident.  
### What:
A model to classify potholes and normal images to avoid potholes on the road.
### When:
When drivers face difficulty to identify the potholes due to the poor road conditions, which leads to severe accidents.
### Where:
While driving it is crucial to have information about the road surface through which the vehicle travels.
### How:
A machine learning-based pothole classification model to detect potholes in images. Images of roads with pothole and non-pothole are collected and preprocessed. Using CNN architecture the images are classified into normal and pothole images.

## Detail requirements
#### High Level Requirements:
| ID        | Description           | Status   |
| ------------- |:-------------:| -----:|
| 01    | Image Dataset | Implemented |
| 02    | Augmented Dataset |   Implemented |
| 03    | CNN Model      |    Implemented |
| 04    | Confusion matrix | Implemented |
| 05    | Images with location in database      |   Future |
| 06    | Alert on mobile      |    Future |
### Low level Requirements:
| ID        | Description           | Status   |
| ------------- |:-------------:| -----:|
| 01    | Pothole image Dataset | Implemented |
| 02    | Non-Pothole image Dataset |   Implemented |
| 03    | Horizontal-flipped image dataset      |    Implemented |
| 04    | Vertical-flipped image dataset  | Implemented |
| 05    | Zoom image dataset      |   Implemented |
| 06    | Rescale image dataset      |    Implemented |
| 07    | Rotation image Dataset | Implemented |
| 08    | Shear image Dataset |   Implemented |
| 09    | Width-shift image dataset      |    Implemented |
| 10    | Height-shift image dataset  | Implemented |
| 11    | VGG16 Architecture       |   Implemented |
| 12    | Pothole images with location on cloud     |    Future |
| 13    | Vehicle GPS tracking      |   Future |
| 14    | Pothole warning on mobile      |    Future |

