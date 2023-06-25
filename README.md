# FingerPrint-Classification
classify fingerprint by using three features: Cann edge, Harris key points, and SIFT key points were extracted separately, Then merge them to final classification
# Dataset
The dataset used in this work is private but this dataset https://github.com/robertvazan/fingerprint-datasets.git is similar which have 4 folders each represent direction of fingerprint

The following snapshot from dataset before and after feature extracting:

Original 

<img width="250" alt="Screen Shot 2023-06-25 at 4 09 18 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/0aab0c52-61a3-4f6f-8f04-2144f3f0df59">

Canny Edge

<img width="250" alt="Screen Shot 2023-06-25 at 4 09 51 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/a286b758-cc9c-4e06-a350-df32be2a537b">

Harris corner


<img width="250" alt="Screen Shot 2023-06-25 at 4 10 09 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/96fcfe2a-59b0-42b1-9d28-c7107a974d54">


SIFT key point

<img width="250" alt="Screen Shot 2023-06-25 at 4 10 32 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/5aadf020-bf7c-4876-a3fe-a558b599703e">

# Result
by using Random Forest Model 
- canny edge :

Precision: 29.49 %
- Harris corner:

Precision: 35.22 %
- SIFT key point:

Precision: 35.32 %

# After Merge
by using three ML models: Random Forest, Decision Tree, KNN

<img width="400" alt="Screen Shot 2023-06-25 at 4 15 59 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/c986ba8e-ee52-442c-870c-15bee503f0c6">

# Actual VS Predicted
<img width="400" alt="Screen Shot 2023-06-25 at 4 17 12 AM" src="https://github.com/raghaddii/FingerPrint-Classification/assets/68879499/4f31d5a4-8e6f-437c-98d0-4e504335a8c2">


