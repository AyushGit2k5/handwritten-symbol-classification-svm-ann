# Handwritten Symbol Classification (SVM vs ANN)

## Problem
Developed an image classification system to recognize handwritten mathematical symbols, with a focus on analyzing how different feature extraction techniques and classifiers impact performance.

## Dataset
Custom dataset of grayscale handwritten mathematical symbols across multiple classes. The dataset includes variations in writing styles, leading to intra-class variability and inter-class similarity.

## Approach
- Implemented two classifiers:
  - Support Vector Machine (SVM)  
  - Artificial Neural Network (ANN)  
- Extracted and compared three feature representations:
  - Histogram of Oriented Gradients (HOG)  
  - Local Binary Patterns (LBP)  
  - Raw pixel values  
- Performed a systematic comparison by training each classifier on all feature types to evaluate feature–model interactions.

## Evaluation
Evaluated models using classification accuracy across all feature–classifier combinations. Confusion matrices were generated for the best-performing setup to analyze misclassification patterns.

## Results
HOG-based features consistently achieved the best performance, highlighting the importance of edge and shape-based representations in image classification. Raw pixel inputs performed хуже, demonstrating the limitations of unprocessed features in traditional ML models.

## Key Learnings
- Feature engineering plays a critical role in traditional machine learning pipelines.  
- Structured features such as HOG significantly improve classifier performance compared to raw inputs.  

## Future Improvements
- Perform hyperparameter tuning for SVM and ANN  
- Explore additional feature extraction methods  
- Apply dimensionality reduction (e.g., PCA)  
- Extend to CNN-based models for end-to-end feature learning

## Visualizations
- Accuracy comparison across feature–classifier combinations  
- Confusion matrix for best-performing model  
