# Handwritten-Digit-Recognition-Using-Deep-Learning
## Introduction
This project involves building, training, and evaluating multiple deep learning models for handwritten digit recognition using the MNIST dataset. The models will be tested for performance, and the best-performing model will be selected for deployment in a real-time application using a Tkinter GUI. The code implements several steps, including data preprocessing, model building, training, evaluation, and deployment.

## Project Steps
### 1. Data Preprocessing
Load the MNIST dataset: Import the dataset containing images of handwritten digits.
Normalize the pixel values: Scale the pixel values to the range [0, 1] to improve model performance.
Reshape the data: Adjust the data shape to fit the input requirements of convolutional neural networks (CNNs).
### 2. Model Building
Build and compile multiple models: Create different model architectures using CNNs.
Train and evaluate the models: Identify the best-performing model through training and evaluation.
### 3. Model Evaluation
Evaluate performance: Measure each model's accuracy and loss on the test set.
Select the best model: Choose the model with the highest accuracy and lowest loss for deployment.
### 4. Deployment
Deploy the best model using Tkinter GUI: Implement a graphical user interface for real-time handwritten digit recognition.
## Model Architectures
### 1. Baseline CNN Model
#### Structure:
Three convolutional layers followed by max-pooling layers.
Fully connected dense layers at the end.
#### Activation:
ReLU activation for hidden layers.
Softmax activation for the output layer.
### 2. Improved CNN Model
#### Structure:
Additional convolutional layers with different filter sizes.
Dropout layers to prevent overfitting.
#### Complexity: 
Similar structure with increased complexity.
### 3. Simplified CNN Model
#### Structure:
Fewer convolutional layers.
#### Purpose:
Test if a simpler architecture performs better or worse.
## Data Preprocessing
### Normalization: 
Scale pixel values to [0, 1].
### Reshape: 
Adjust image data to fit the CNN input shape.
## Model Building
### Architectures:
Define three CNN models (baseline, improved, simplified).
### Training and Testing:
Train each model and evaluate performance on the test set.
### Result Storage: 
Store evaluation results for comparison.
## Deployment
### Tkinter GUI: Create a graphical interface for digit recognition.
## Conclusion
This project demonstrates the process of building and deploying a deep learning model for digit recognition, from data preprocessing to real-time application, highlighting model evaluation to choose the best-performing model.

