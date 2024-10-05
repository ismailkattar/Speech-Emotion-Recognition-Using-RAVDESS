# **Tell Me What You Feel**

## **Project Overview**

**Tell Me What You Feel** is a Speech Emotion Recognition (SER) system designed to detect and classify emotions in human speech using Deep Learning (DL) and Machine Learning (ML) models. The project aims to build a classifier that recognizes emotions such as happiness, sadness, anger, and fear from speech data. The main dataset used for this project is the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS).

## **Project Features**
1. **Dataset:**
   - Utilizes the RAVDESS dataset, containing speech samples from 24 actors (12 male, 12 female) expressing seven different emotions at two levels of intensity.
   
2. **Feature Extraction:**
   - Frequency domain features: MFCC (Mel Frequency Cepstral Coefficient), Chroma-STFT, Spectral Centroid (SC)
   - Time domain features: Zero Crossing Rate (ZCR), Root Mean Square Error (RMSE)

3. **Models:**
   - **Deep Learning (DL) Models:** CNN-based models using different combinations of features for emotion classification.
   - **Machine Learning (ML) Models:** Logistic Regression (LR), Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Decision Tree (DT), Random Forest (RF), XGBoost, AdaBoost, MultiLayer Perceptron (MLP).

4. **Pre-processing:**
   - Data augmentation techniques such as Noise Injection, Time Stretching, and Pitch Shifting were applied to improve the model's performance.

5. **Results:**
   - The performance of the DL and ML models is summarized in the table below:

   | **Model**           | **Test Accuracy** |
   |---------------------|-------------------|
   | CNN Model 1         | 89.58%            |
   | CNN Model 2         | 91.84%            |
   | CNN Model 3         | 95.31%            |
   | SVM                 | 70.03%            |
   | Random Forest       | 40.32%            |
   | Logistic Regression | 48.26%            |
   | KNN                 | 44.16%            |
   | MLP                 | 67.08%            |
   | AdaBoost            | 31.13%            |
   | XGBoost             | 53.44%            |
   | Decision Tree       | 26.67%            |


 
