# Hand Gesture Recognition
This project implements a hand gesture recognition model to accurately identify and classify various hand gestures from image data. The model enables gesture-based control systems for more intuitive human-computer interaction. This is the fourth task of my Machine Learning internship at Prodigy InfoTech.

## 📁 Files in this Repository
`Prodigy_ML_Task_4.ipynb:` Jupyter Notebook containing the full implementation of the hand gesture recognition model.

## 📊 Dataset Overview
The **LeapGestRecog** dataset contains a large number of hand gesture images. The dataset includes multiple categories of gestures, which are used to train the recognition model.

The dataset includes:
- **Hand Gesture Images:** Images of different hand gestures from various angles and positions.
- **Classes:** Multiple gesture classes for classification.

## 🚀 Project Workflow
1. **Data Loading and Exploration:**
    - Loaded the dataset consisting of thousands of hand gesture images.
    - Explored the structure of the dataset, analyzing gesture categories and class distribution.

2. **Image Preprocessing:**
    - Resized images to a fixed size (e.g., 128x128 pixels) for consistency.
    - Applied image normalization and data augmentation techniques such as rotation, flipping, and zooming to improve model performance and prevent overfitting.

3. **Model Development:**
    - Used a Convolutional Neural Network (CNN) for feature extraction and classification of hand gestures.
    - The CNN architecture includes convolutional layers, pooling layers, and fully connected layers for effective learning.

4. **Model Training:**
    - Trained the model using the preprocessed images with gesture labels.
    - Applied cross-validation to ensure the model generalizes well on unseen data.
    - Tuned hyperparameters such as learning rate, batch size, and number of epochs.

5. **Evaluation:**
    - Evaluated the model using metrics such as accuracy, precision, recall, and F1 score on the test set.
    - Visualized the performance using confusion matrices and classification reports.

6. **Gesture Classification:**
    - The model is capable of classifying hand gestures into different categories, enabling potential use in gesture-based control systems.

## 📈 Results
The model successfully classified different hand gestures with high accuracy, providing a strong foundation for gesture-based human-computer interaction applications.

**Dataset Used**- [Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
