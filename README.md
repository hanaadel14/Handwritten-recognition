# Handwritten-recognition

Image Classification of a dataset of Arabic handwriting, using the convolutional Neural networks. The 
dataset consists of 2 folders: (Test & Training images)

1) Importing Libraries:
• os: a module in python providing a way to interact with the operating system 
• cv2: Open-Source Computer Vision Library) is a popular computer vision and image processing 
library
• Numpy: for numerical computing in Python providing support for multidimensional arrays 
pandas: for data manipulation and analysis 
• Tensorflow: pen-source machine learning framework developed by Google. It provides tools, 
libraries, and resources for building and deploying machine learning models

3) Data processing and preparation :
The code prepares the training and validation data by adjusting image properties, separating a 
portion of the data for validation purposes, and setting up how the data will be fed into the model 
during training to help it learn patterns and make predictions using
ImageDataGenerator and training and Validation Data Loaders

4) Train and evaluate the model :
• Trains the model on the training data for a specified number of epochs, validating against the 
validation data. 
• Evaluates the model's performance on the training data and prints the accuracy

6) Plotting Accuracy and Loss curves:
• Loss: It represents the error or the difference between predicted and actual values during the 
training process. By plotting the loss curve, you can visualize how the model's performance 
changes over epochs. A decreasing loss indicates that the model is learning and improving.
• Accuracy: It signifies the correctness of the model's predictions.
The confusion matrix covers all possible combinations of classes, showing correct and incorrect 
predictions across various classes.
Performance Metrics Derived from the Confusion Matrix:
• Accuracy: Overall correctness of predictions [(TP + TN) / (TP + TN + FP + FN)].
• Precision: Accuracy of positive predictions among total predicted positive instances (TP / 
(TP+ FP)).
• Recall (Sensitivity or True Positive Rate): Ability to correctly identify positive instances (TP / 
(TP + FN)).
Specificity (True Negative Rate): Ability to correctly identify negative instances (TN / (TN + FP)).
F1 Score: Harmonic mean of precision and recall (2 * ((Precision * Recall) / (Precision + Recall))).
