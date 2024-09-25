# Pneumonia Detection Using AWS Rekognition
This project is part of the Building a Model course under my Nanodegree in AI Product Manager Program
## Project Overview
In this project, I focused on building a classification model to detect pneumonia in children's chest X-ray images. The goal was to create a diagnostic aid for doctors to quickly identify serious cases, flag healthy cases, and generally assist in the pneumonia diagnosis process.

The project involved building the following four Models: 

1. **Binary Classifier for Pneumonia Detection**: I trained a binary classifier using 100 "normal" and 100 "pneumonia" chest X-ray images.
2. **Unbalanced Binary Classifier**: I trained a binary classifier using 100 "normal" and 200 "pneumonia" chest X-ray images, creating an unbalanced dataset.
3. **Classifier with Dirty Data**: I trained a binary classifier using the original 100 "normal" and 100 "pneumonia" images, but with 30% of the data mislabeled.
4. **Three-Class Classifier**: I trained a three-class classifier using 100 "normal", 100 "bacterial pneumonia", and 100 "viral pneumonia" chest X-ray images.

For each model, I evaluated various performance metrics, such as the confusion matrix, precision, and recall.

## Dataset
The dataset I used in this project was the [Kaggle Chest X-Ray Images (Pneumonia) dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia), which contained chest X-ray images of children classified as "normal" and "pneumonia".

## Tools and Technologies

- **AWS Rekognition**: An automated machine learning (AutoML) tool that allowed me to build and host the classification model in the cloud.

## Project Tasks
1. **Binary Classifier for Pneumonia Detection**
   - I evaluated the train/test split, confusion matrix, precision, and recall.

2. **Unbalanced Binary Classifier**
   - I evaluated the confusion matrix, precision, and recall and discussed the impact of unbalanced classes.

3. **Classifier with Dirty Data**
   - I evaluated the confusion matrix, precision, and recall and discussed the impact of dirty data.

4. **Three-Class Classifier**
   - I evaluated the confusion matrix, precision, and recall.
   - I explored ways to improve the model's performance by adding more data to each class.

## Deliverables
1. **AutoML Modeling Report**: A report documenting my findings and insights from each model I built.

## Conclusion
This project provided me with hands-on experience in building classification models using an AutoML platform (AWS Rekognition) and understanding the impact of various properties of the training data on model performance. By exploring different scenarios, I gained insights into how to develop robust and effective diagnostic tools for pneumonia detection.

## Contact 
If you have any questions, feedback, or inquiries regarding this project, please feel free to reach out to me through my Email: NouvAlqahtani@gmail.com.
