# Skin Cancer Detection System using CNN  

## Overview  
This project focuses on the **automated classification of skin cancer** using **Convolutional Neural Networks (CNN)**. Early detection of skin cancer is crucial for timely medical intervention, and deep learning models can assist in accurate diagnosis.  

## Objectives  
- Develop a **CNN-based model** for skin cancer classification.  
- Achieve high accuracy while maintaining computational efficiency.  
- Plan future improvements to handle dataset imbalance and implement more advanced deep learning models.  

## Model Implemented  
- **Convolutional Neural Network (CNN)**  

## Dataset  
The project uses the **HAM10000 dataset**, which contains **10,000 labeled dermoscopic images**.  
Classes include:  
1. **Actinic keratoses** (AKIEC)  
2. **Basal cell carcinoma** (BCC)  
3. **Benign keratosis-like lesions** (BKL)  
4. **Dermatofibroma** (DF)  
5. **Melanoma** (MEL)  
6. **Melanocytic nevi** (NV)  
7. **Vascular lesions** (VASC)  

## Methodology  
1. **Data Preprocessing**  
   - Resized images to **224x224 pixels**.   
   - Normalized pixel values for better convergence.  

2. **Model Training**  
   - Implemented a **CNN architecture** for feature extraction and classification.  
   - Trained the model using **Adam optimizer** and **categorical cross-entropy loss**.  
   - Used **batch normalization and dropout** to reduce overfitting.  

3. **Evaluation Metrics**  
   - **Accuracy**  
   - **Precision, Recall, and F1-score**  

## Results  
- **Achieved 78% accuracy** on the validation set.  
- The model performs well but struggles with **dataset imbalance**, affecting some class predictions.  
