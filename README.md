Brain Tumor Detection Using MRI Images

Overview

This project implements a binary classification model to detect brain tumors from MRI images. The model uses a convolutional neural network (CNN) to predict whether a given MRI scan indicates the presence of a tumor. The system achieves an accuracy of approximately 90% on the validation dataset.

Project Structure

The project is organized into the following components:

Dataset: MRI images labeled as "Tumor" (1) or "No Tumor" (0). The dataset is split into 80% training data and 20% validation data.

Model Architecture: A convolutional neural network (CNN) built using TensorFlow/Keras.

Evaluation Metrics: Validation accuracy, precision, recall, and F1-score.

Prediction: The trained model can predict the tumor presence for new MRI images.



Results

Validation Accuracy: ~90%

Validation Loss: Consistently low, indicating good generalization.

Confusion Matrix:

High true positive and true negative rates.
