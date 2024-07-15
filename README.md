
# 3D UNet Model for Brain Tumor Segmentation

This repository contains code and resources for training and evaluating a 3D UNet model for brain tumor segmentation using the BraTS2020 dataset.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

This project implements a 3D UNet model for segmenting brain tumors in MRI images. The model is trained and evaluated on the BraTS2020 dataset, which contains multi-modal MRI scans with annotated brain tumors.

## Features

- Preprocessing of MRI images
- Data augmentation techniques
- 3D UNet architecture for segmentation
- Model training and evaluation
- Visualization of predictions

## Requirements

- Python 3.6
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn

Install the required packages using:
```bash
pip install -r requirements.txt
```

## Usage

1. **Data Preparation**: Download the BraTS2020 dataset and organize the data as follows:
   ```
   /path/to/data/
       ├── train/
       │   ├── images/
       │   └── masks/
       └── val/
           ├── images/
           └── masks/
   ```


## Results

The Mean IoU (Intersection over Union) metric is used to evaluate the model's performance on the validation set.

## License

This project is licensed under the MIT License.
