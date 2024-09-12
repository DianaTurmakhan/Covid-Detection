# COVID-19 Detection Using Convolutional Neural Networks

This project focuses on detecting COVID-19 from chest X-ray images using Convolutional Neural Networks (CNNs). The models are trained and fine-tuned using Python with TensorFlow/Keras frameworks. 

## Project Overview

The main goal of this project is to develop a deep learning model capable of accurately identifying COVID-19 cases from chest X-ray images. The project uses different CNN architectures, including the Xception model, to improve detection accuracy.

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/DianaTurmakhan/Covid-Detection.git
cd Covid-Detection
pip install -r requirements.txt
```

## Project Structure

- `CNN_train.ipynb`: Jupyter Notebook for training CNN models.
- `covid_xception.ipynb`: Jupyter Notebook implementing the Xception model for COVID-19 detection.
- `data/`: Folder containing the dataset (X-ray images).
- `models/`: Directory to save trained models.

## Dataset

The dataset used for this project consists of chest X-ray images categorized into COVID-19 and non-COVID-19 classes. You can download the dataset from publicly available sources or contact us to get the exact dataset.

Ensure that the dataset is structured as follows:

```bash
data/
    ├── train/
        ├── covid/
        ├── normal/
    ├── test/
        ├── covid/
        ├── normal/

```
## Model architecture
`Custom CNN Model:` A simple convolutional neural network built from scratch in the CNN_train.ipynb notebook.
`Xception Model:` A pre-trained Xception model, fine-tuned for COVID-19 detection, as described in covid_xception.ipynb.

