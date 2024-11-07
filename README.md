# Human Detection and Counting in Classrooms Using YOLOv8

## Description
A human detection and counting solution optimized for classroom environments, leveraging the YOLOv8 model. This project fine-tunes YOLOv8 for improved accuracy in detecting and counting people in an indoor, controlled environment.

## Table of Contents
1. [Overview](#overview)
2. [Motivation](#motivation)
3. [Features](#features)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Limitations and Future Work](#limitations-and-future-work)
9. [References](#references)

## Overview
This project uses a fine-tuned YOLOv8 model to detect and count people in a classroom setting. By adapting a pre-trained YOLO model, we achieved high accuracy in human detection with optimizations for limited lighting and classroom crowd density.

## Motivation
Counting and detecting people in a room efficiently is crucial for monitoring attendance, optimizing space usage, and ensuring security. YOLO's robustness in object detection makes it an ideal choice for real-time applications in fixed environments like classrooms.
          ![image](https://github.com/user-attachments/assets/bcdc2015-c894-49ca-8888-2f3af06a3157)



## Features
- Fine-tuned YOLOv8 model with optimized performance for indoor, classroom conditions.
- Data preprocessing pipeline for annotated dataset preparation.
- Evaluation metrics implemented for model performance comparison.

## Methodology
1. **Model Choice**: Initially experimented with custom models but shifted to fine-tuning YOLOv8 for better results.
2. **Data Preparation**: Annotated classroom-specific dataset for training and validation.
3. **YOLO Fine-Tuning**:
   - Utilized a pre-trained YOLOv8 model from Ultralytics.
   - Applied layer freezing to retain core features while fine-tuning upper layers.
4. **Evaluation**: Compared YOLOv8 fine-tuning results against custom models and alternative YOLO versions, focusing on accuracy and real-time performance.

## Results
The fine-tuned YOLOv8 model achieved high detection accuracy in classroom environments, with a notable improvement over our custom models. Key results:
![image](https://github.com/user-attachments/assets/e2bff66f-aec1-4070-abc7-cc9c0eaac0ab)



- **Model Accuracy**: XX%
- **mAP**: YY%
- **Real-Time Processing Speed**: ZZ FPS

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/harshm2601/People-Detection-Crowd-Counting.git
