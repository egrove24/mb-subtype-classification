# Medulloblastoma Subtype Classification

This repository contains a Jupyter Notebook for classifying medulloblastoma subtypes using radiomic and pathomic features.  
The workflow implements preprocessing, feature selection, and machine learning models for 2-way, 3-way, and 4-way classification tasks.

## Code Organization

The notebook is organized into three main sections:

1. **Classification of Subtype – Radiomic Data**  
   - Loads radiomic feature data for each subject.  
   - Performs feature selection.  
   - Trains classification models (SVM) for 2-way, 3-way, and 4-way classification.  
   - Evaluates performance using accuracy, confusion matrices, and decision scores.

2. **Classification of Subtype – Pathomic Data**  
   - Loads pathomic feature data for each subject.  
   - Applies similar preprocessing and feature selection steps as the radiomic section.  
   - Trains and evaluates models for subtype classification.  

3. **Classification of Subtype – Radiomic + Pathomic Data**  
   - Merges radiomic and pathomic features for each subject.  
   - Performs combined feature selection.  
   - Trains and evaluates models on the combined dataset
