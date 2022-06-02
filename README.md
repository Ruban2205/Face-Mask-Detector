# Face-Mask-Detector

A Face Mask detector is a python project developed with some Machine Learning libraries.

Given the trained COVID-19 face mask detector, we’ll proceed to implement two more additional Python scripts used to:

- Detect COVID-19 face masks in images
- Detect face masks in real-time video streams

## Project Structure 

The ```dataset/``` directory contains the data described in the “Our COVID-19 face mask detection dataset” section. Three image ```examples/``` are provided so that you can test the static image face mask detector.

Three python scripts are: 

- ```train_mask_detector.py```: Accepts our input dataset and fine-tunes MobileNetV2 upon it to create our ```mask_detector.model```. A training history ```plot.png``` containing accuracy/loss curves is also produced
- ```detect_mask_image.py```: Performs face mask detection in static images
- ```detect_mask_video.py```: Using your webcam, this script applies face mask detection to every frame in the stream

## Languages and Tools used 

[![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://github.com/Ruban2205/Face-Mask-Detector)
[![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)
[![NumPY](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=whit)](https://github.com/Ruban2205/Face-Mask-Detector)
[![SciKitLearn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)

[![Pycharm](https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)

[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://github.com/Ruban2205/Face-Mask-Detector)


## Licence

This repository is release under MIT Licence. See [LICENCE](LICENCE) for more details. 

## Contact

[![Website](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://rubangino.in/)
[![Mail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@rubangino.in)
