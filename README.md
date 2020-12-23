# eyediseaseclass
Goal: design models and methods to predictively detect pathological images and explain the pathology sites in the image data.

## Data for this assignment is taken from a Kaggle contest: https://www.kaggle.com/c/vietai-advance-course-retinal-disease-detection/overview
Explanation of the data set:
The training data set contains 3435 retinal images that represent multiple pathological disorders. The patholgy classes and corresponding labels are: included in 'train.csv' file and each image can have more than one class category (multiple pathologies).
The labels for each image are

```
-opacity (0), 
-diabetic retinopathy (1), 
-glaucoma (2),
-macular edema (3),
-macular degeneration (4),
-retinal vascular occlusion (5)
-normal (6)
```
The test data set contains 350 unlabelled images.

# For this project, I am working with Diabetic Retinopathy and Glaucoma only, and I am building a predictive learning model along with feature explanability and self-learning for Diabetic Retinopathy and Glaucoma vs. Normal images.

## Task 1: Build a classification model for Diabetic Retinopathy and Glaucoma vs normal images. 
```
a. Perform 70/30 data split and report performance scores on the test data set.
b. Data augmentation. 
c. Show Training-validation curves.
```
## Task 2: Visualize the heatmap to demonstrate what regions of interest contribute to Diabetic Retinopathy and Glaucoma, respectively. 


## Task 3: Using the unlabelled data set in the 'test' folder augment the training data (semi-supervised learning) and report the variation in classification performance on test data set.

