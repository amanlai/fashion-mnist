# Project 4 - Fashion Classifier
Data Science Problem:
- Create a Convolutional Neural Network model to classify types of clothing from images.
## Workflow:
1) Basic Neural Network to classify images.
2) Create an Overfit Model
3) Regularize Model
4) Evaluate Performance
### 1) Basic Neural Network
The first model used basic convolution and MaxPooling steps, and then flattened the output to a simple Dense layer and Softmax output. This model produced a ~88.0 validation score.
### 2) Overfit Model
The second model used more complex repeated convolution and MaxPooling steps, and then a multi-layer dense network. This model used many neurons per layer. This model produced ~90.0 validation score.
### 3) Regularization
The third model, after convolution and MaxPooling, utilized Batch Normalization and Weight decay within the dense network. This model produced a test validation of 92.0
### 4) Performance Evaluation
In evaluating the model, the best Accuracy score was 92.0. The model tended to misclassify similar objects, like shirts -vs- pullovers and shoes -vs- boots.