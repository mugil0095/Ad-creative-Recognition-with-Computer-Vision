# Ad Creative Recognition with Computer Vision

### Problem Description:

In the digital landscape, advertisements play a crucial role in delivering content and engaging users. Your challenge is 
to develop an advanced computer vision solution capable of identifying whether an image is an advertising creative or 
not. This task involves detecting visual patterns and features commonly associated with advertisements.

## Key Objectives:

### 1. Ad Creative Detection Model:
- Implement a computer vision model that can accurately classify images into two categories: ad creatives and non-ad 
creatives.
### 2. Feature Extraction and Analysis:
- Identify and extract key visual features that distinguish ad creatives from non-ad creatives.
- Develop a mechanism to analyze the presence of specific elements such as logos, text overlays, product images, 
and color schemes indicative of advertisements.
### 3. False Positive Reduction:
- Implement strategies to minimize false positives by considering contextual information and additional cues in the 
images.
- Enhance the model's accuracy in distinguishing between promotional content and non-promotional visual elements

Sorry For Not uploading the build model. Due to the Large Size, it is not possible to upload in Github.

# Process of the Assignment (Ad_Creatives_Detection.ipynb)
## 1. Collection of Dataset - Two different dataset that are defined as Ad_Creative and None_Ad_Creative.
## 2. Load the ad and non_ad creatives datasets and label them correctly.
## 3. Then Augment the images in both the folders and save in separate folders.
## 4. Balance the augmented images by deleting the excess images.
## 5. Split the augmented images into training and testing data.
## 6. Load the base model ResNet50.
## 7. Compile the model with better optimization algorithm.
## 8. Train the compiled model.
## 9. Visualize the model's evaluation metrics.
## 10. Save the model.
## 11. Test the trained model with different samples.
## 12. Test with any images by getting as input from the user.

