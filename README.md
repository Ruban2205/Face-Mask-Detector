# Face-Mask-Detector

A Face Mask detector is a python project developed with some Machine Learning libraries.

Given the trained COVID-19 face mask detector, we’ll proceed to implement two more additional Python scripts used to:

- Detect COVID-19 face masks in images
- Detect face masks in real-time video streams

This repository contains code and resources for a face mask detection system. This system is built using deep learning techniques and is capable of detecting whether a person is wearing a face marsk or not in real-time

## Introduction 

The Face Mask Detector is a computer vision system that can identify whether a person is wearing a facemask or not. It utilizes deep learning techniques to process images and make predictions in real-time. The system can be useful in various applications such as public safety, healthcare, and security. 

This repository provides the code and resources necessary to train and deploy the facemask detection system. 

## Project Structure 

The ```dataset/``` directory contains the data described in the “Our COVID-19 face mask detection dataset” section. Three image ```examples/``` are provided so that you can test the static image face mask detector.

Three python scripts are: 

- ```train_mask_detector.py```: Accepts our input dataset and fine-tunes MobileNetV2 upon it to create our ```mask_detector.model```. A training history ```plot.png``` containing accuracy/loss curves is also produced
- ```detect_mask_image.py```: Performs face mask detection in static images
- ```detect_mask_video.py```: Using your webcam, this script applies face mask detection to every frame in the stream

## Features 

- Real-time face mask detection 
- High accurace and performance 
- Easy to use and integrate into existing systems
- Supports both image and video input 

## Requirements

To run the face mask detector, you need to have the following dependencies installed: 

[![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://github.com/Ruban2205/Face-Mask-Detector)
[![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=whit)](https://github.com/Ruban2205/Face-Mask-Detector)

## Installation 

1. Clone this repository: 
```
git clone https://github.com/Ruban2205/Face-Mask-Detector.git
```

2. Change into the project directory: 
```
cd Face-Mask-Detector
```

3. Install the required dependencies: 
```
pip install -r requirements.txt
```

## Usage

To use the face mask detector, Follow these steps: 

1. Run the detection script: 
```
python detect_mask.py
```
This will start the face mask detection system using your webcam as the input source. 

2. The system will display the live video feed with bounding boxes around detected faces. It will also label each face as "With Mask" or "Without Mask" based on the prediction. 

3. Press 'q' to quit the system. 

## Licence

This repository is release under MIT Licence. See [LICENCE](LICENCE) for more details. 

## Contact

[![Website](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://rubangino.in/)
[![Mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@rubangino.in)
