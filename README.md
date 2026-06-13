# AI-Based Intrusion Detection System for Network Traffic Classification

## Overview

The AI-Based Intrusion Detection System (IDS) is a deep learning-based cybersecurity solution designed to classify network traffic and detect potential cyber attacks. Traditional intrusion detection systems often struggle to identify new and evolving threats, whereas deep learning models can learn complex patterns from network traffic and improve detection accuracy.

This project utilizes a Deep Neural Network (DNN) implemented using TensorFlow and Keras to classify network traffic into different attack categories and distinguish malicious activities from normal network behavior.

---

## Features

* Network Traffic Classification using Deep Learning
* Detection of Cyber Attacks and Malicious Activities
* Data Preprocessing and Feature Engineering
* Deep Neural Network (DNN) Architecture
* Model Evaluation using Multiple Performance Metrics
* User-Friendly Gradio Interface
* Real-Time Attack Prediction from User Input

---

## Dataset

The project uses a network intrusion detection dataset containing:

* 41 Input Features
* 1 Output Label

Features include:

* Protocol Type
* Service Type
* Connection Duration
* Source and Destination Bytes
* Error Rates
* Connection Counts
* Network Traffic Statistics

The output label represents normal traffic or a specific attack category.

---

## Technologies Used

* Python
* TensorFlow
* Keras
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Gradio

---

## Deep Learning Model Architecture

### Input Layer

* 41 Network Traffic Features

### Hidden Layers

* Dense Layer (128 Neurons, ReLU)
* Dropout Layer (0.3)
* Dense Layer (64 Neurons, ReLU)
* Dropout Layer (0.3)
* Dense Layer (32 Neurons, ReLU)

### Output Layer

* Softmax Activation for Multi-Class Classification

---

## Data Preprocessing

The following preprocessing steps were applied:

1. Data Cleaning
2. Removal of Unnecessary Features
3. Label Encoding
4. Feature Normalization
5. Train-Test Split

Dataset Split:

* Training Data: 80%
* Testing Data: 20%

---

## Training Configuration

| Parameter     | Value                    |
| ------------- | ------------------------ |
| Optimizer     | Adam                     |
| Loss Function | Categorical Crossentropy |
| Epochs        | 50                       |
| Batch Size    | 32                       |

---

## Performance Evaluation

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Visualization includes:

* Training Accuracy Curve
* Validation Accuracy Curve
* Loss Curve
* Confusion Matrix

---

## System Workflow

1. Load Network Traffic Dataset
2. Perform Data Preprocessing
3. Train Deep Neural Network Model
4. Evaluate Model Performance
5. Deploy Prediction Interface using Gradio
6. Predict Network Attack Type from User Input

---

## Gradio User Interface

A user-friendly Gradio interface has been developed that allows users to:

* Enter Network Traffic Parameters
* Click the Predict Button
* View the Predicted Attack Category

The interface simplifies interaction with the model and enables practical deployment without requiring programming knowledge.

---

## Results

Experimental results demonstrate that the Deep Neural Network effectively classifies network traffic and identifies malicious activities with high accuracy. Performance metrics and visualization graphs indicate that the model can successfully learn patterns associated with different network attacks.

---

## Future Enhancements

Future improvements may include:

* Integration with Real-Time Network Monitoring Systems
* Implementation of CNN and LSTM Architectures
* Deployment on Cloud Platforms
* Advanced Threat Detection Mechanisms
* Larger and More Diverse Cybersecurity Datasets

---

## Authors

**Umara Maqsood**
2022-EE-254

**Muhammad Rauf**
2022-EE-273

Department of Electrical, Electronics & Telecommunication Engineering
University of Engineering and Technology (UET), Lahore

---

## Supervisor

**Dr. Umar Rashid**

Department of Electrical, Electronics & Telecommunication Engineering
University of Engineering and Technology (UET), Lahore

---

## License

This project is developed for academic and educational purposes.

