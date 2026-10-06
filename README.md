# Breast Cancer Classification using ANN

A Deep Learning project that uses an **Artificial Neural Network (ANN)** to classify breast cancer cases based on diagnostic features.

The project demonstrates the process of preparing the data, building an ANN model, training the model, and evaluating its performance for binary classification.

## Project Overview

Breast cancer classification is a common machine learning and healthcare analytics problem where diagnostic measurements can be used to predict whether a tumor is **benign** or **malignant**.

In this project, an Artificial Neural Network is used to learn patterns from the input features and classify the samples into the corresponding cancer categories.

## Objectives

* Understand the fundamentals of Artificial Neural Networks.
* Perform data preprocessing for neural network models.
* Build an ANN for binary classification.
* Train the neural network on breast cancer data.
* Evaluate the model's classification performance.
* Understand how deep learning can be applied to healthcare-related classification problems.

## Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **Artificial Neural Networks (ANN)**

## Project Workflow

```text
Input Dataset
     ↓
Data Preprocessing
     ↓
Feature Selection
     ↓
Feature Scaling
     ↓
Train-Test Split
     ↓
ANN Model
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Cancer Classification
```

## ANN Architecture

The model follows a standard Artificial Neural Network architecture:

1. **Input Layer**
   Receives the diagnostic features used for classification.

2. **Hidden Layers**
   Learns patterns and relationships between the input features.

3. **Activation Functions**
   Introduces non-linearity so the network can learn complex relationships.

4. **Output Layer**
   Produces the final binary classification result.

## Repository Structure

```text
Breast-Cancer-Classification-using-ANN/
│
├── ANN1.ipynb
│   └── Complete ANN implementation, training and evaluation
│
├── .gitignore
│
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Varshh-hub/Breast-Cancer-Classification-using-ANN.git
```

### 2. Navigate to the Project

```bash
cd Breast-Cancer-Classification-using-ANN
```

### 3. Install Dependencies

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook ANN1.ipynb
```

Run the notebook cells sequentially to perform preprocessing, build the ANN model, train the network, and evaluate the classification results.

## Model Evaluation

The model can be evaluated using classification metrics such as:

* Accuracy
* Loss
* Confusion Matrix
* Precision
* Recall
* F1-Score

These metrics help assess how effectively the ANN distinguishes between the two classes.

## Key Learning Outcomes

Through this project, I gained practical experience with:

* Artificial Neural Networks
* Binary classification
* Data preprocessing
* Feature scaling
* TensorFlow/Keras
* Neural network architecture
* Model training and evaluation
* Applying Deep Learning to healthcare classification problems

## Future Improvements

* Add a dedicated prediction script for new patient data.
* Save the trained ANN model for future inference.
* Add detailed confusion matrix visualization.
* Compare ANN performance with traditional machine learning algorithms.
* Build a simple Flask or Streamlit application for predictions.
* Deploy the trained model as a web application.

## Author

**Varsha A**

B.Sc. Artificial Intelligence & Machine Learning

GitHub: https://github.com/Varshh-hub
