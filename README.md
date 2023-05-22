# Data-Augmentation

This repository contains my implementations and practice for various data augmentation techniques used in machine learning and computer vision tasks.

## Cutout Augmentation on Car Object Detection Dataset

In this project, I applied Cutout augmentation on the Car Object Detection dataset obtained from Kaggle ([Car Object Detection Dataset](https://www.kaggle.com/datasets/sshikamaru/car-object-detection)). The dataset consists of images of cars along with corresponding bounding box annotations.

To evaluate the effectiveness of Cutout augmentation, I trained a YOLO (You Only Look Once) model using two different sets of data: one without augmentation and the other with Cutout augmentation. By comparing the performance of the model on both sets, we can assess the impact of Cutout augmentation on object detection accuracy.

## Mixup Augmentation on Car Object Detection Dataset

In this project, I applied Mixup augmentation on the Car Object Detection dataset obtained from Kaggle ([Car Object Detection Dataset](https://www.kaggle.com/datasets/sshikamaru/car-object-detection)). Similar to the previous experiment, the dataset contains images of cars with corresponding bounding box annotations.

Using the Mixup augmentation technique, I trained a YOLO model on two sets of data: one without augmentation and the other with Mixup augmentation. The goal is to compare the performance of the model trained on both sets and determine the impact of Mixup augmentation on object detection accuracy.

## Cutmix Augmentation on Dogs vs. Cats Dataset

In this project, I applied Cutmix augmentation on the Dogs vs. Cats dataset obtained from Kaggle ([Dogs vs. Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats)). The dataset comprises images of dogs and cats, and the task is to classify them correctly.

By employing the Cutmix augmentation technique, I trained a YOLO model on two sets of data: one without augmentation and the other with Cutmix augmentation. The objective is to analyze the performance of the model on both sets and determine the impact of Cutmix augmentation on the accuracy of dog and cat classification.

Feel free to explore the code and results in each project folder. The implementations aim to provide a hands-on understanding of different data augmentation techniques and their effects on model performance in specific tasks.