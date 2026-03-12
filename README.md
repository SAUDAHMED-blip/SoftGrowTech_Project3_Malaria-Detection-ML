# SoftGrowTech_Project3_Malaria-Detection-ML
Malaria Parasite Detection using CNN on microscopic blood cell images
# Malaria Parasite Detection using Convolutional Neural Networks (CNN)

## Project Overview

This project implements a Machine Learning model to detect malaria parasites from microscopic blood smear images. The system uses a Convolutional Neural Network (CNN) to classify blood cell images into two categories: **Parasitised** (infected) and **Uninfected** (healthy).

Early detection of malaria is important for effective treatment. This project demonstrates how Artificial Intelligence can assist healthcare professionals in diagnosing malaria using image classification techniques.

---

## Dataset

The dataset consists of microscopic images of blood cells divided into two classes:

* **Parasitised** – Blood cells infected with malaria parasites
* **Uninfected** – Healthy blood cells

Total images in dataset: **~27,000**

The dataset was used to train and evaluate the CNN model.

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Model Architecture

The Convolutional Neural Network (CNN) used in this project consists of:

* Convolution Layers for feature extraction
* MaxPooling Layers for dimensionality reduction
* Flatten Layer to convert feature maps into vectors
* Dense Layers for classification
* Sigmoid Output Layer for binary classification

---

## Project Workflow

1. Load dataset from Google Drive
2. Preprocess and normalize image data
3. Split dataset into training and validation sets
4. Build CNN model architecture
5. Train the model using training data
6. Evaluate model performance
7. Plot training accuracy and loss graphs
8. Save the trained model

---

## Results

Model Performance:

* Training Accuracy: **~93% – 95%**
* Validation Accuracy: **~92% – 94%**

Training graphs show decreasing loss and increasing accuracy during model training.

---

## Project Structure

Malaria-Detection-ML/

dataset/
Contains parasitised and uninfected blood cell images

notebook/
Contains the Google Colab notebook used to train the model

model/
Contains the trained CNN model file

results/
Contains accuracy and loss graphs generated during training

documentation/
Contains project report and supporting documents

requirements.txt
Lists all required Python libraries

README.md
Project description and usage instructions

---

## How to Run the Project

1. Open the notebook in Google Colab
2. Mount Google Drive
3. Load the dataset
4. Run all cells in the notebook
5. Train and evaluate the model

---

## Applications

This project demonstrates how Machine Learning can be used for:

* Medical image classification
* Disease detection using AI
* Automated diagnostic systems
* Healthcare decision support systems

---

## Author

**Saud Ahmed**
BS Artificial Intelligence
COMSATS University Islamabad – Wah Campus
