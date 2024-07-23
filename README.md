## Computer Vision: Predicting Customer Age

For this computer vision project, we will be working with a straightforward dataset to predict customer age, which is particularly useful for ensuring legal compliance in alcohol sales. The primary goal of this project is to establish a baseline model that can be used as a foundation for more advanced computer vision applications in the future. Given the constraints of current computational resources, we are initially utilizing CPU processing for model development and training, but the project is designed to be scalable, allowing for significant performance improvements with GPU processing or other advanced hardware. It's important to note that the model training and experimentation were conducted virtually, leveraging cloud-based environments to facilitate collaboration and resource sharing among team members.

Link: https://github.com/jmmelgarejo/15-computer-vision-age-predictive-model/blob/main/15-computer-vision-age-predictive-model.ipynb

## Table of Contents
- Introduction
- Objectives
- Methodology
- Conclusions

### Introduction

This project focuses on developing a computer vision model to predict customer age, which is particularly useful for ensuring compliance with legal regulations in alcohol sales. The dataset for this project comprises approximately 7,600 photos along with a labels.csv file that includes two columns for the image file and the real age of the customer.

### Objectives

- Train a model that predicts customer age based on photos (faces) for use in alcohol sales.
- Measure accuracy (MAE) and determine the usability of the model in real-life scenarios.


### Methodology
- Data Import and Exploratory Data Analysis: Data is imported and checked. EDA is performed to show baseline statistics of the data such as average age and distribution.
- Model Selection and Training: A regression model is trained with various transformations like rescaling, flipping, shifting, and rotation. A validation set is used to measure accuracy in training. A pre-trained ResNet50 as the base model, which is optimized with Adam.

### Conclusions

Computer Vision and the Use Case

- In the specific customer case - monitoring clerks selling alcohol, the computer vision model is not reliable. The MAE is too high, allowing around for 7 years of error. Specifically for alcohol sales, this error is too high.

Other Use Cases for the Model

- The model can be used to inform marketing decisions - using broaded age groups - young, middle age, elderly for example, to identify shopping patterns and adjusting marketing strategies accordingly
- Broad age and shopping data could be used to test sales of products across specific age groups.




