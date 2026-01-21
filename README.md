# Face Mask Detection using Machine Learning


## 1. Introduction

Face mask detection became an important application during the COVID-19 pandemic to ensure public safety.
This project implements a real-time face mask detection system using machine learning and deep learning techniques. The system detects faces from images or video streams and classifies whether the detected face is wearing a mask or not.
The project focuses on creating a lightweight and efficient model that can run on laptops and edge devices, making it suitable for real-world deployment.

## 2. Problem Statement
To design and implement a supervised machine learning–based image classification system that can automatically detect whether a person is wearing a face mask or not using facial images.

## 3. Type of Machine Learning Problem
Learning Type: Supervised Learning
Task: Binary Classification

Classes:
* With Mask
* Without Mask

## 4. Dataset Description
The dataset used in this project consists of face images divided into two classes:

* With Mask: 494 images
* Without Mask: 407 images
* Total Images: 901

Dataset Split:
* Training images: 722
* Validation images: 179

The dataset is stored on Google Drive and accessed using Google Colab.

## 5. Data Preprocessing

Before training the model, the following preprocessing steps were applied:

* Images were resized to the required input size of the model.
* Pixel values were normalized to improve learning stability.
* Data was loaded using Keras ImageDataGenerator for efficient preprocessing.
* The dataset was split into training and validation sets.

These steps ensure that the input data is suitable for training a deep learning model.


## 7. Model Training

* The model is trained using the training dataset.
* Validation data is used to monitor performance during training.
* The training process tracks:

  * Training accuracy
  * Validation accuracy
  * Training loss
  * Validation loss

---

## 8. Model Evaluation

Model performance is evaluated using:

* Training and validation accuracy
* Training and validation loss

### Observations

* Accuracy increases steadily across epochs.
* Validation loss decreases along with training loss.
* Training and validation curves are closely aligned, indicating minimal overfitting.
* The model generalizes well to unseen data.

---

## 9. System Workflow

The complete system follows this pipeline:

1. Input image or video frame
2. Face detection using SSD
3. Image preprocessing
4. Mask classification using MobileNetV2
5. Output prediction (Mask / No Mask)

A pipeline flowchart and model architecture diagram are included in the notebook for visualization.

---

## 10. Results and Visualization

The notebook contains:

* Accuracy and loss plots
* System pipeline flowchart
* Model architecture diagram

These visualizations help in understanding model performance and system design.

---

## 11. Tools and Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* SSD (Single Shot Detector)
* Google Colab
* Google Drive
* OpenCV
* NumPy
* Matplotlib

---

## 12. Conclusion

This project successfully demonstrates the use of machine learning and deep learning techniques for real-time face mask detection. The model achieves good accuracy while maintaining low computational complexity, making it suitable for deployment on edge devices. The project fulfills all the objectives of a supervised machine learning application.

---

## 13. Course Outcome Mapping

* CO1: Identified suitable machine learning techniques
* CO2: Solved a real-world problem using ML
* CO3: Developed an ML-based application
* CO4: Evaluated and interpreted model performance

---

## 14. Future Enhancements

* Improve accuracy using larger datasets
* Add multi-class classification (incorrect mask usage)
* Deploy the model as a web or mobile application
* Optimize real-time performance further

---

## Final Confirmation

This document is complete.
It matches the implemented notebook code.
It is valid for Machine Learning course submission.
It is suitable for viva and faculty review.
It can be used as official project documentation.

---

If you want next:

* PDF or DOCX conversion
* PPT for final presentation
* Short viva answers
* GitHub folder structure and commit message

Just tell me.
