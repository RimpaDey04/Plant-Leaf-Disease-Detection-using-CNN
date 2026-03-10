# Plant-Leaf-Disease-Detection-using-CNN
Plant diseases significantly affect agricultural productivity and crop quality. Early detection of plant diseases can help farmers take preventive measures and reduce crop loss. This project presents a deep learning-based approach using Convolutional Neural Networks (CNN) to automatically detect and classify plant leaf diseases from images.

The system analyzes leaf images and predicts whether the leaf is healthy or affected by a disease. The dataset is divided into training, validation, and testing sets to ensure proper model evaluation and to avoid overfitting.

By leveraging CNN's capability to extract complex visual features, the model learns patterns such as color variation, texture changes, and lesion structures that indicate plant diseases.

# Objectives

- To automatically detect plant leaf diseases using deep learning techniques.

- To build an image classification model using Convolutional Neural Networks (CNN).

- To evaluate the model using training, validation, and testing datasets.

- To achieve reliable accuracy for disease prediction.

# Dataset

The dataset consists of plant leaf images categorized into different classes such as:

- Healthy leaves
- Powdery leaves
- Rust leaves

The dataset is divided into three parts:

1. Training Set – Used to train the CNN model

2. Validation Set – Used to tune model parameters and monitor performance during training

3. Testing Set – Used to evaluate the final performance of the model

# Dataset Structure
Dataset/
│
├── Train/
│   ├── Healthy/
│   └── Diseased/
│
├── Validation/
│   ├── Healthy/
│   └── Diseased/
│
└── Test/
    ├── Healthy/
    └── Diseased/
# Model Architecture

The model is built using Convolutional Neural Networks (CNN) which are widely used for image classification tasks.

Typical CNN layers used in the model:

Convolutional Layer

ReLU Activation

Max Pooling Layer

Flatten Layer

Fully Connected (Dense) Layer

Dropout Layer

Output Layer (Softmax/Sigmoid)

CNN automatically extracts important features from the images such as:

Leaf color variations

Spot patterns

Texture differences

# Technologies Used

- Python

- TensorFlow / Keras

- NumPy

- Matplotlib

- OpenCV / PIL

- Jupyter Notebook

# Data Preprocessing

To improve model performance, the following preprocessing steps were applied:

- Image rescaling (normalization)

- Image augmentation:

- Rotation

- Zoom

- Horizontal flipping

- Shear transformation

- These techniques help increase dataset diversity and reduce overfitting.

# Model Performance

The model was trained for multiple epochs using the training dataset and validated using the validation dataset.

The accuracy trend during training is shown below.

- Training Accuracy: ~91%

- Validation Accuracy: ~83%

This indicates that the model is able to learn meaningful features while maintaining good generalization performance.

Key observations from the graph:

- Training accuracy increases steadily with epochs.

- Validation accuracy also improves, showing that the model generalizes well.

- The gap between training and validation accuracy is moderate, indicating limited overfitting.
