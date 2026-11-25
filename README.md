#  Plant Disease Detection Using Deep Learning

##  Project Overview

This project aims to detect and classify plant diseases using Deep Learning and Convolutional Neural Networks (CNNs).

The system analyzes images of plant leaves to identify whether a plant is healthy or affected by a specific disease. The project explores different CNN architectures, compares their performance, and identifies the most accurate model for plant disease classification.

##  Dataset

The dataset is divided into three subsets for model training and evaluation:

- **Training Set:** 70,295 images (79.99%)
- **Validation Set:** 17,572 images (19.99%)
- **Test Set:** 0.04% (as reported in the project presentation)

##  Model Development

Three different CNN architectures were developed and evaluated to compare their classification performance.

### Model Architectures

**1. Custom CNN Model (10 Conv2D Layers)**

A custom CNN architecture consisting of 10 convolutional layers, designed to extract important features from plant leaf images.

**2. Deep CNN Model (9 Conv2D Layers)**

A deeper CNN architecture consisting of 9 convolutional layers, designed to improve feature extraction and classification performance.

**3. CNN with Batch Normalization & Global Average Pooling**

An optimized CNN architecture incorporating Batch Normalization and Global Average Pooling to improve training stability and feature representation.

###  Model Performance Comparison

| Model Architecture | Image Size | Batch Size | Epochs | Accuracy |
|---|---:|---:|---:|---:|
| Custom CNN (10 Conv2D Layers) | 128×128 | 32 | 10 | 95.08% |
| Deep CNN (9 Conv2D Layers) | 256×256 | 1024 | 10 | 96.85% |
| CNN with Batch Normalization & Global Average Pooling | 224×224 | 64 | 25 | **98.73%** |

##  Model Evaluation

The models were evaluated using several performance metrics and visualization techniques:

- Training and Validation Accuracy.
- Training and Validation Loss Curves.
- Confusion Matrix.
- Classification Report.
- Precision.
- Recall.
- F1-Score.

These evaluation methods were used to analyze model performance and compare classification results.

##  Disease Detection Implementation

The project includes an image-based prediction interface that allows users to:

- Upload an image of a plant leaf.
- Process the uploaded image.
- Predict the corresponding plant disease.
- Display the predicted disease class.
- Show the prediction confidence score.

##  Best Performing Model

Among the three developed CNN architectures, **CNN with Batch Normalization & Global Average Pooling** achieved the highest classification accuracy of **98.73%**.

This model outperformed the other two architectures and demonstrated the best overall accuracy in the conducted experiments.

##  Technologies Used

- Python
- TensorFlow / Keras
- Convolutional Neural Networks (CNN)
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Google Colab
- Jupyter Notebook

##  Project Objective

The main objective of this project is to explore the application of Deep Learning in agriculture by developing an automated plant disease classification system that can help identify plant diseases through leaf image analysis.
