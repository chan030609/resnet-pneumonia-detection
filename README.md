# resnet-pneumonia-detection
Date: Jan 4, 2021

<img src = 'https://images.emedicinehealth.com/images/article/main_image/bacterial-pneumonia-1.jpg' width="400">

## Introduction

Pneumonia is an inflammatory condition of the lung primarily affecting the small air sacs known as alveoli. Symptoms typically include some combination of productive or dry cough, chest pain, fever and difficulty breathing. Although pneumonia is most likely to be caused by viral infections, bacterial infections, or fungi, COVID-19 is becoming a rising factor especially among the elderly. For some people, COVID-19 causes more severe symptoms like high fever, severe cough, and shortness of breath, which often indicates pneumonia. Nowadays, with this increasing importance of accurately detecting diseases, deep learning is often presented as a possible solution.

This project uses Residual Network (ResNet) via transfer learning, a popular neural network model for image classification. The dataset was obtained from Kaggle, consisting of around 6,000 images. The problem in this dataset is data class imbalance due to the difference between the number of 'normal' images and 'pneumonia' images, which has to be overcome by using weighted loss.

## Content
- Click [here](https://github.com/chan030609/resnet-pneumonia-detection/resnet-pneumonia-detection.ipynb) to view the project (.ipynb).
- Click [here](https://github.com/chan030609/resnet-pneumonia-detection/resnet-pneumonia-detection.py) to view the raw code (.py).
- Click [here](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) to view the Kaggle dataset.

## Technology Used
- Google Colab Jupyter Notebook with GPU Acceleration
  - PyTorch
