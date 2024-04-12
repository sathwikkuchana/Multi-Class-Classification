# MultiClass Image Classification using TensorFlow

This project is aimed at building a multi-class image classification model using TensorFlow. The model is designed to classify images into nine different categories: airplanes, bonsai, chandelier, faces_easy, hawksbill, ketch, leopards, motorbikes, and watch.

![image](https://github.com/sathwikkuchana/Multi-Class-Classification/assets/37955149/518ad39d-57f2-4ea2-ad5c-a80a280f02b8)


# Project Structure
README.md: This file provides an overview of the project.
image_classification.ipynb: This Jupyter Notebook contains the Python code for data preparation, model creation, training, and evaluation.
9_objects.zip: The compressed file containing the image dataset for training and testing.
Getting Started
# Dataset Preparation:

Upload the 9_objects.zip file to your Google Drive in the specified location (drive/My Drive/9_objects.zip).
Extract the contents of the ZIP file to the /tmp directory in Google Colab.
# Running the Code:

Open the image_classification.ipynb notebook in Google Colab.
Execute each cell sequentially to perform data splitting, model building, training, and evaluation.
Results:

The code generates plots for training and validation accuracy and loss.
Check the plots to analyze the performance of the trained model.
# Dependencies
Python 3.x
TensorFlow
NumPy
Matplotlib
Google Colab (for running the notebook)
Data Splitting
The split_data function is used to split the dataset into training and testing sets. It ensures that each class has an equal representation in both sets.

# Model Architecture
The neural network model consists of convolutional layers followed by max-pooling layers and dense layers. Dropout regularization is applied to prevent overfitting.

![image](https://github.com/sathwikkuchana/Multi-Class-Classification/assets/37955149/781c784d-7b07-4116-b6a2-fdb0e7c92135)


# Training
The training data is augmented using ImageDataGenerator to improve model generalization.
RMSprop optimizer is used with categorical cross-entropy loss for model training.
The training process is visualized using plots for accuracy and loss over epochs.
![image](https://github.com/sathwikkuchana/Multi-Class-Classification/assets/37955149/440ba901-e5b6-4863-b3af-702ad40cb585)

# Evaluation
The trained model is evaluated on the validation set to assess its performance.
The final accuracy and loss metrics are displayed in the output.
