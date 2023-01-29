# Stereo-Vision

## Project Description

In this project, I have implemented the concept of Stereo Vision on three data set, each of them contains 2 images of the same scenario but taken from two different camera angles. By comparing the information about the scene from 2 vantage points, we can obtain the 3D information by examining the relative position of the objects. I have also estimated the camera pose using the concept of the Essential matrix (E), Fundamental matrix (F) and triangulation. 

## Pipeline
### 1. Calibration 
- Compare the two images and select the set of matching feature. Tune the Lowe's ration to reject the outliers
- Estimate the Fundamental matrix using the obtained matching feature. Use the RANSAC to make your estimation more robust. Enforce the rank 2 condition for the fundamental matrix.

