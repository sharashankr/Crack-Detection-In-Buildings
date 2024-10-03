# Crack-Detection-In-Buildings
Crack detection plays a critical role in structural health monitoring and building inspections, as early identification of cracks can prevent potential failures and costly repairs. It ensures the safety and longevity of structures by enabling timely maintenance, reducing risks, and enhancing the overall reliability of buildings and infrastructure.

## Overview

This project focuses on a **binary classification** problem:

- **Images of Cracked Concrete**
- **Images of Concrete with No Cracks** (`y = 0`)

The dataset consists of **40,000 RGB (color) images**, divided into:

- **20,000 images with cracks** (positives)
- **20,000 images without cracks** (negatives)

### Dataset Split

- **75%** of the images are used for **training**.
- **25%** of the images are used for **validation**.

### Dataset Challenges

- Cracks may be confused with noise in the background texture or foreign objects.
- Inhomogeneous illumination and irregularities, such as exposure of jointing, can complicate crack detection.

### Datasets

The datasets used in this project for training and validation are large (approximately 200MB each). You can download the datasets from the links below:

- [Dataset 1: Concrete Crack Images for Classification](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0321EN/data/images/concrete_crack_images_for_classification.zip)
- [Dataset 2: Concrete Data - Week 2](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0321EN/data/concrete_data_week2.zip)
- [Dataset 3: Concrete Data - Week 3](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DL0321EN-SkillsNetwork/concrete_data_week3.zip)
- [Dataset 4: Concrete Data - Week 4](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0321EN/data/concrete_data_week4.zip)

Please ensure that you have sufficient bandwidth and storage space before downloading.

## Project Flow

Below are the stages and flow of the project:

### 1. Initial Data Exploration
We begin by exploring the data and understanding the images with cracks and those without.

### 2. Data Preprocessing
Images are processed to ensure uniformity and accuracy for model training.

![Screenshot 1](https://github.com/user-attachments/assets/8ff8f347-ec25-4b91-a99d-9c65e1a4866e)

### 3. Feature Engineering
We extract relevant features from the images to better classify cracked vs. non-cracked images.

![Screenshot 2](https://github.com/user-attachments/assets/20f9b35b-eb51-480a-ab4f-49b909fb957b)

### 4. Model Training
Various models are trained to classify the images, and their performances are compared.

![Screenshot 3](https://github.com/user-attachments/assets/92cae870-1cee-4ba7-aef5-2d5f6ffa9ad5)

### 5. Model Evaluation
We evaluate the models using validation data and tune the parameters to achieve optimal performance.

![Screenshot 4](https://github.com/user-attachments/assets/54388c29-654f-4ad1-9dc1-3954b2638934)

### 6. Results Comparison
Finally, we compare the results of different models to identify the most effective approach for crack detection.

![Screenshot 5](https://github.com/user-attachments/assets/06be2ea4-fa5f-4a57-ac1a-fe9c403b3615)

## Conclusion

Through this project, we aim to build a reliable and efficient system for detecting cracks in buildings, enhancing safety, and reducing long-term maintenance costs. We also aim to improve the accuracy of detection by overcoming dataset challenges such as background noise and irregular lighting.
