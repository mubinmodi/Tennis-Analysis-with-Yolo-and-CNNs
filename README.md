# Tennis-Analysis-with-Yolo-and-CNNs
## Introduction
This project focuses on analyzing tennis players in video footage to evaluate their speed, ball shot speed, and the total number of shots. Using YOLO for player and ball detection, along with CNNs to extract court keypoints, this hands-on project is an excellent opportunity to enhance your machine learning and computer vision skills.

## Output Videos
Below is a screenshot from one of the output videos:
![Screenshot](output_videos/screenshot.jpeg)

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

* Trained YOLOV5 model: https://drive.google.com/file/d/1UZwiG1jkWgce9lNhxJ2L0NVjX1vGM05U/view?usp=sharing
* Trained tennis court key point model: https://drive.google.com/file/d/1QrTOF1ToQ4plsSZbkBs3zOLkVt3MBlta/view?usp=sharing

## Training
* Tennis ball detetcor with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
