# Animals Classification
This project explores the application of convolutional neural networks (CNNs) for the task of animal image classification. I have curated a dataset of diverse animal images and employed transfer learning to fine-tune pre-trained models on our specific task. The goal is to achieve high classification accuracy and contribute to the field of computer vision.

## Demo
https://huggingface.co/spaces/dielz/animals-classifier-demo

## To Do
- Using a dataset with a total amount of 10000+ data
- Training and test accuracy of at least 95%
- The model was able to classify at least 3 different classes

## Dataset
To support the define objectives, the [dataset](https://www.kaggle.com/datasets/piyushkumar18/animal-image-classification-dataset) was obtained from kaggle with 12 different classes and 17000+ data. However, due to limited resources, only 10 classes were used in this project.

## Model Evaluation
### Training & Validation Accuracy
![image](https://github.com/user-attachments/assets/1ccf2049-66fa-4941-9917-7222057fb3b1)


### Training & Validation Loss
![image](https://github.com/user-attachments/assets/fd0be92f-183b-4ea9-aa96-855121902b37)

### Confusion Matrix
![image](https://github.com/user-attachments/assets/fa203c83-187f-40d1-8db3-52d477531565)

### Summary
| Model | Structure                                     | Data Splitting | Training Accuracy | Validation Accuracy |
|-------|-----------------------------------------------|----------------|-------------------|---------------------|
| 1     | Sequential + MobileNetV2 + Conv2D + MaxPool2D | 80/20          | 98%               | 95%                 |

### Prediction
![image](https://github.com/user-attachments/assets/230cd21d-e3f1-4318-89fe-2dc38f76d2c2)

Seen from the summary and prediction results of the model that has fulfilled all the points that are the objective of this project.
