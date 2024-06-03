# Brain Tumor Detection in Medical Images Using Object Detection Models

## Overview
Object Detection (OD) or object recognition in images is a profound aspect of Computer Vision. It refers to the ability of computer systems and software to locate objects in an image and identify each object, which can be used in various fields such as security, healthcare, etc., with many functions such as face detection, smart cars, license plate recognition, anomaly detection, foreign object detection, etc.

This project, **“Experimenting with Object Detection Models for Brain Tumor Detection in Medical Images”**, focuses on experimenting with Object Detection models like R-CNN, Fast R-CNN/ Faster R-CNN, and YOLOv7 to address the problem of detecting brain tumors in medical images.

## Input
- Image data from MRI or CT scanners containing information on the presence, location, and characteristics of brain tumors.
- The object to be detected: brain tumor in the images.

## Output
- Bounding box around the brain tumor in the image.
- Information about the location and characteristics of the tumor.

## Objective
- Experiment with Object Detection models: R-CNN, Fast R-CNN, Faster R-CNN, and YOLOv7.
- Automatically identify brain tumors in images to support early diagnosis and treatment planning.

## Data Requirements
- MRI or CT image data with labeled (bounding box) brain tumors.
- Data must be diverse in terms of the size, location, and characteristics of the tumors.

## Model Requirements
- The model must be capable of detecting tumors not only in easy cases but also in difficult cases such as small tumors, closely located tumors, occluded tumors, etc.
- The model needs to achieve high accuracy and fast processing speed.

## Input Requirements
- MRI or CT images containing brain tumors.

## Output Requirements
- Marked region containing the tumor and information about the tumor.

## Data

**“Brain Tumor Object Detection Datasets”** is an image and label training dataset for detecting brain tumors. The set includes training image sets and labels/bounding box coordinates for brain cancer detection in MRI images.

**Source:**
- Derived from the RSNA-MICCAI Brain Tumor competition data.

**Collection Method:**
- JPG datasets were exported at their original size, manually labeled using makesense.ai, and split by plane (Axial, Coronal, and Sagittal).
- Positive/Negative MGMT status and bounding box were labeled to classify tumor type.

**License Information:** CC0: Public Domain.

**Data Information:**
- Training set: 878 image files.
- Test set: 223 image files.

** Coronal_t1wce_2_class:**
- Training set: 319 images + 318 labels
- Test set: 78 images + 78 labels

** Axial_t1wce_2_class:**
- Training set: 310 images + 296 labels
- Test set: 75 images + 75 labels

** Sagittal_t1wce_2_class:**
- Training set: 264 images + 264 labels
- Test set: 70 images + 70 labels

### Dataset Link:
- The dataset can be accessed on Kaggle: [Brain Tumor Object Detection Datasets](https://www.kaggle.com/datasets/davidbroberts/brain-tumor-object-detection-datasets)

## Getting Started

### Prerequisites
- Python 3.x
- TensorFlow or PyTorch
- OpenCV
- Other dependencies 

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## Acknowledgments
- Thank you to all contributors and the open-source community.
- Special thanks to the developers of the R-CNN, Fast R-CNN, Faster R-CNN, and YOLOv7 models.
