# Pneumonia Detection in CXRs using Computer Vision

## Introduction
India faces a substantial burden from pneumonia, particularly with children under 5 years. According to 2022-23 data available from the Health Management Information System (HMIS), over <b>473,780 childhood pneumonia cases</b> were reported across the country, resulting in <b>16,068 deaths</b>. The real number could be higher due to undetected cases.

Pneumonia is primarily detected by radiologists with the help <b>Chest X-Rays (CXRs)</b> using the presence of <b>lung opacities</b>. However, radiologists work with large number of patient scans other than CXRs like CT and MRI on the daily basis which could lead to overwork. 

To aid radiologists in this task, AI models could be developed to <b>automate initial detection</b> (imaging screening) of potential pneumonia cases in order to <b>prioritize and expedite</b> their review. This project aims to build such a model!

## Dataset
The dataset used to train the models is created by the Radiological Society of North America (RSNA) in collaboration with US National Institutes of Health, The Society of Thoracic Radiology, and MD.ai. It has <b>30K CXR sample images</b>, with <b>10K pneumonia cases</b>. This dataset was uploaded on Kaggle in 2018 as part of the competition for building the pneumonia classifer model.

More information about the competition could be found here: https://www.kaggle.com/competitions/rsna-pneumonia-detection-challenge/overview

The processed dataset from this competition used in this project could be found here: https://www.kaggle.com/datasets/iamtapendu/rsna-pneumonia-processed-dataset

## Project Details
The project is divided into 5 notebooks,<br>
a) <b>EDA</b> - to do basic analysis of the dataset, display differnet CXRs and divide dataset for training and testing<br>
b) <b>CNN Model Training</b> - for training different CNN models from scratch to detect pneumonia<br>
c) <b>Transfer Learning</b> - to use already trained models like ResNet50, InceptionV3, MobileNet and ResNet152 to detect pneumonia<br>
d) <b>Model Performance Analysis</b> - to compare performance of all the trained models in one place and choose the best model for testing<br>
e) <b>Caliberation and Model Testing</b> - to caliberate prediction threshold of the best model and get its performance on the test set
