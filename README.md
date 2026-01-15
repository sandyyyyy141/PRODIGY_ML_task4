# Hand Gesture Recognition using CNN \| LeapGestRecog Dataset

This project implements a Hand Gesture Recognition system using a
Convolutional Neural Network (CNN) trained on the **LeapGestRecog**
dataset.\
The model can classify different hand gestures from grayscale images and
can be used for gesture-based control systems, HCI (Human-Computer
Interaction), and automation projects.

------------------------------------------------------------------------

## 📌 Dataset

**Dataset Name:** LeapGestRecog\
**Source:** Kaggle\
**Link:** https://www.kaggle.com/gti-upm/leapgestrecog

The dataset contains: - 10 gesture classes\
- 10 subjects\
- 200 images per gesture\
- Total image count: **20,000+** - Image size: **120 × 120 grayscale**

------------------------------------------------------------------------

## 📁 Directory Structure

    project/
     ├── leapGestRecog/
     │     ├── 00/
     │     ├── 01/
     │     ├── ...
     │     ├── 09/
     ├── hand_gesture_model.h5
     ├── README.md
     └── notebook.ipynb

------------------------------------------------------------------------

## 🚀 How to Run in Google Colab

1.  Install Kaggle API\
2.  Upload kaggle.json\
3.  Download and extract dataset\
4.  Load and preprocess images\
5.  Train CNN model\
6.  Evaluate and test predictions\
7.  Save model

------------------------------------------------------------------------

## 🧠 CNN Model Summary

-   Convolution layers for feature extraction\
-   MaxPooling layers\
-   Dense layers\
-   Dropout layer\
-   Softmax output layer

------------------------------------------------------------------------

## 📊 Output

-   Training accuracy graph\
-   Test accuracy\
-   Gesture prediction\
-   Saved `.h5` model

------------------------------------------------------------------------

## 📜 Author

**Sandeep Yadav**\
Machine Learning Intern --- Prodigy InfoTech

------------------------------------------------------------------------
