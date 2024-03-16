# Plant-Pathology-Detection-Deep-Learning

Objective:The primary objective is to develop a deep-learning model that can classify plant diseases based on images. I used the provided training dataset, which consists of images resized to a maximum dimension of 600 pixels while maintaining the aspect ratio. The challenge is to use these images to train models that can accurately classify plant diseases in the test set.

Data Description:
Source: Derived from the Plant Pathology 2021 - FGVC8 Kaggle competition (https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8).
Training Set: Publicly available images, resized with the largest dimension capped at 600 pixels. The dataset includes various classes of plant diseases. 
Test Set: A separate set of images, similarly processed, to be used for evaluating the models.

Datasets: 
Train_Datset = 13,000 

Test_Datset = 5,590 

One csv file with train_img name and labels

Unique Labels:
powdery_mildew
scab
scab frog_eye_leaf_spot
complex
rust
frog_eye_leaf_spot
healthy
frog_eye_leaf_spot complex
rust frog_eye_leaf_spot
powdery_mildew complex
scab frog_eye_leaf_spot complex
rust complex


Acknowledgement:
Source: https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8

For the original Kaggle Competition, details and background information on the dataset and Kaggle competition ‘Plant Pathology 2020 Challenge’ were published as a peer-reviewed research article.

Thapa, Ranjita; Zhang, Kai; Snavely, Noah; Belongie, Serge; Khan, Awais. The Plant Pathology Challenge 2020 data set to classify foliar disease of apples. Applications in Plant Sciences, 8 (9), 2020.


