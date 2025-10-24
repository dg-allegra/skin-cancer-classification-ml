# skin-cancer-classification-ml
This project focuses on the automatic classification of skin lesions (moles) as **benign** or **malignant**, using classical **machine learning algorithms** combined with different **feature extraction techniques**.  
The goal is to evaluate the performance of multiple model–feature extractor combinations and identify the most effective pipeline for skin cancer detection.

# Objectives
- Develop a machine learning pipeline for **skin lesion classification**.  
- Compare the performance of three ML models:
  - Support Vector Machine (SVM)  
  - k-Nearest Neighbors (KNN)  
  - Random Forest (RF)  
- Evaluate the impact of different **feature extraction methods**:
  - HOG (Histogram of Oriented Gradients)  
  - BLP (Binary Local Pattern or similar local descriptor)  
  - Color Histogram 
- Analyze accuracy and overall model behavior through a comparative study

# Workflow
1. **Dataset loading**  
   - The dataset contains dermoscopic images of skin lesions (benign and malignant)
   - Images are preprocessed (resized, normalized) before feature extraction

2. **Feature extraction**  
   - Extract HOG, BLP, and Color Histogram features for each image
   - Concatenate or normalize feature vectors when needed

3. **Model training**  
   - Train SVM, KNN, and Random Forest classifiers on the extracted features 
   - Evaluate on validation or test data

4. **Evaluation**  
   - Compute and compare accuracy, precision, recall, F1-score
   - Plot performance comparison by model and feature extractor
  
# How to run
You can run the notebook directly on [Google Colab](https://drive.google.com/drive/folders/1mP6mV6O5IQBDFuKXdgk3ZiVVW5C2ABK9?usp=sharing):

1. Open the notebook `skin_cancer_classification.ipynb`
2. Run all cells to train and evaluate the models
3. View accuracy comparisons and generated plots

# Google Colab Project
[Google Colab Project](https://drive.google.com/drive/folders/1mP6mV6O5IQBDFuKXdgk3ZiVVW5C2ABK9?usp=sharing)
