# Plant Disease Detection Using Deep Learning

## Project Overview
This project focuses on detecting and classifying plant diseases using Deep Learning and Convolutional Neural Networks (CNN). It analyzes leaf images to identify whether a plant is healthy or affected by a disease.

## Dataset
The dataset is divided into three subsets:
- Training Set: 70,295 images (79.99%)
- Validation Set: 17,572 images (19.99%)
- Test Set: 0.04% (as shown in the project presentation)

## Model Development
Three CNN architectures were developed and compared based on their performance.

### Model Comparison

| Model | Image Size | Batch Size | Epochs | Accuracy |
|---|---|---|---|---|
| Model 1 | 128×128 | 32 | 10 | 95.08% |
| Model 2 | 256×256 | 1024 | 10 | 96.85% |
| Model 3 | 224×224 | 64 | 25 | 98.73% |

## Model Evaluation
The models were evaluated using:
- Training and validation accuracy.
- Loss curves.
- Confusion matrix.
- Classification report.
- Precision, Recall, and F1-score.

## Disease Detection Implementation
The project includes an image-based prediction interface that allows users to upload a plant leaf image and receive a disease classification prediction with its confidence score.

## Best Model
Model 3 achieved the highest reported accuracy of 98.73% among the three compared architectures.
