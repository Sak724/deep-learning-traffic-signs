
# Deep Learning Traffic Signs

Traffic sign recognition is a fundamental task in the development of autonomous driving systems. Accurate detection and classification of road signs such as speed limits, stop signs, and warning indicators are essential for ensuring vehicle safety and compliance with traffic regulations.

While many traffic signs are standardized globally, some include local language components that pose additional challenges for general-purpose recognition systems.

![Traffic Sign Examples](assets/road-signs.gif)

## Introduction

This repository provides an end-to-end implementation of a deep learning model trained on the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset. The project involves:

- Preprocessing and organizing over 50,000 labeled traffic sign images
- Training a Convolutional Neural Network (CNN) using TensorFlow
- Evaluating the model’s accuracy on 43 different traffic sign classes
- Saving the trained model for future inference or deployment

The GTSRB dataset is widely used in traffic sign recognition research and includes 39,209 training images and 12,630 test images, all categorized into 43 classes.

![43 Classes](assets/43classes.png)

## Project Structure

```bash
├── assets/
│   ├── 43classes.png
│   ├── road-signs.gif
│   ├── stop_sign.jpg
│   └── tomare.jpg
├── data/
│   ├── Meta/
│   ├── Train/
│   ├── Test/
│   ├── Meta.csv
│   ├── Train.csv
│   └── Test.csv
├── models/
├── traffic_sign_detection.ipynb
├── requirements.txt
