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

## Training

If you want to tran the face mask detection model on your own dataset, you can follow these steps: 

1. Prepare your dataset with two classes: "With Mask" and "Without Mask". The dataset should be organized into separate directories for each class. 

2. Update the `config.py` file to specify the paths to your dataset and other configuration settings. 

3. Run the training script: 
```python train_mask_detector.py```
This will train the face mask detection model using the specified dataset and save the trained model to the disk. 

4. Once training is complete, you can use the trained model for face mask detection by running the `detect_mask.py` script. 

## Dataset

The dataset used to train the face mask detection model is not included in this repository. You can use your own dataset or find suitable datasets from public sources. Ensure that your dataset contains a sufficient nuber of images for both "With Mask" and "Without Mask" classes to achieve good performance. 

## Model 

The face mask detection model is based on a deep neural network architecture. It is trained using the TensorFlow and Keras frameworks.
The model takes an input image and predicts whether the person in the image is wearing a face mask or not. 

## Results 

The face mask detection system achieves high accuracy on the test dataset. The performance may vary depending on the quality and diversity of the training dataset. It is recommended to train the model on the large and representative dataset for optimal results. 

## Contributing

Contributions to the Face Mask Detetor project are welcome and encouraged. If you want to contribute, please follow these steps: 

1. Fork the repository and create your own branch. 
2. Make the desired changes and additions. 
3. Test your changes thoroughly. 
4. Submit a pull request describing the changes you made. 

Please ensure that your contributions align with the project's codeing standards, maintain code quality, and provide clear documentation when necessary. 

## Licence

The Face Mask Detector project is licensed under the [MIT License](/LICENSE). You are free to use, modify, and distribute the code for personal and commerical purposes. See the [LICENSE](/LICENSE) file for more details. 

## Contact

If you have any questions, suggestions, or concerns about the Face Mask Detector project, please feel free to reach out to me. 

You can Contact me at: 

- Email: [info@rubangino.in](https://mailto:info@rubangino.in/)
- GitHub Issues: [https://github.com/Ruban2205/Face-Mask-Detector/issues](https://github.com/Ruban2205/Face-Mask-Detector/issues)

I appreciate your feedback and contributions! 

[![Website](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://rubangino.in/)
[![Mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@rubangino.in)
