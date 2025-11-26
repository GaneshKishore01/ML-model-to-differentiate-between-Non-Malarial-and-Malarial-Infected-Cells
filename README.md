# malaria-ml-model
A **TensorFlow 2 binary classification model** trained on the NIH Malaria Cell Image Dataset   to distinguish between **infected** and **non-infected red blood cells**.
# Machine Learning Model for Malaria Diagnosis

## Overview
A **TensorFlow 2 binary classification model** trained on the NIH Malaria Cell Image Dataset  
to distinguish between **infected** and **non-infected red blood cells**.
this is an replication study of https://github.com/mdhabibi/CNN-Predictor-for-Malaria_Cells-LIME-CAM?tab=readme-ov-file
![Image Alt](https://github.com/GaneshKishore01/ML-model-to-differentiate-between-Non-Malarial-and-Malarial-Infected-Cells/blob/main/Sample_Images.png)

## Features
- Preprocessing and data augmentation  
- Convolutional Neural Network (CNN) architecture  
- Accuracy evaluation on validation set

## 🧬 How We Trained the Model

We first converted all images to grayscale, resized them to a fixed shape, flattened them into 1-D vectors, and normalized the pixel values. After preparing the dataset, we split it into training and testing sets.

We then trained a simple TensorFlow neural network on these flattened grayscale images to classify them as malarial or non-malarial. The model learned basic patterns directly from the pixel intensities, and we evaluated its performance using the testing dataset

## Results
![Image Alt](https://github.com/GaneshKishore01/ML-model-to-differentiate-between-Non-Malarial-and-Malarial-Infected-Cells/blob/main/Model_predictions.png)
✅ Achieved reliable classification accuracy on test samples  
⚠️ Requires more training data for clinical-level reliability  

## Tech Stack
- Python
- TensorFlow

## Future Directions
- Model optimization for mobile/low-power devices  
- Integration with Raspberry Pi for **point-of-care diagnostics**  
- Expansion to other blood-borne diseases  

---

*This is a showcase repo. Dataset not included (NIH dataset publicly available).*
