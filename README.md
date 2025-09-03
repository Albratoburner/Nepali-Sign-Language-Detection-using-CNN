# Nepali Sign Language Recognition

This project explores the use of data mining and deep learning techniques for recognizing Nepali Sign Language (NSL).  
The main goal is to build a system that can accurately classify NSL gestures and support better communication for the deaf and hard-of-hearing community.

## Problem Statement
The deaf community in Nepal primarily relies on Nepali Sign Language (NSL) for communication.  
However, due to a lack of awareness and resources, there is a significant communication gap between sign language users and non-users.  
This project addresses the problem by developing an automated sign language recognition system that can identify NSL gestures.

## Objectives
- To collect and preprocess a dataset of Nepali Sign Language hand signs.  
- To apply and compare data mining and deep learning techniques for recognition.  
- To evaluate model performance using accuracy and classification metrics.  
- To identify the most suitable approach for real-world applications in accessibility and education.

## Dataset
The dataset used in this project is the **[Nepali Sign Language Character Dataset](https://www.kaggle.com/datasets/biratpoudelrocks/nepali-sign-language-character-dataset)** from Kaggle.  
It consists of images representing different Nepali Sign Language characters.

## Implemented Techniques
The following models were applied and compared:  
- Convolutional Neural Network (CNN)  
- Logistic Regression  
- Random Forest Classifier  
- Multilayer Perceptron (MLP)  
- Support Vector Machine (SVM)  

## Summary
- Models were trained and evaluated on a Nepali Sign Language dataset.  
- CNN showed the best performance, highlighting the strength of deep learning in image-based recognition tasks.  
- Other machine learning models such as Logistic Regression, Random Forest, MLP, and SVM were also implemented for comparison.  
- A script for webcam integration has also been added to demonstrate real-time gesture recognition.  

## Future Work
- Extend the system to dynamic gestures (words and sentences).  
- Improve the real-time recognition system for smoother performance.  
- Deploy as a mobile or web application to increase accessibility.  

## Tech Stack
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- OpenCV  
- NumPy, Pandas, Matplotlib  


