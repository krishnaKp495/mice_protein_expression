Mice Protein Expression Analysis
This project uses machine learning models to analyze the expression levels of 77 proteins in the cerebral cortex of mice. The primary objective is to classify the data into eight distinct classes of mice based on their genotype (control or trisomy), behavior (context-shock or shock-context), and treatment (memantine or saline). The dataset used for this analysis was obtained from Kaggle(https://www.kaggle.com/datasets/ruslankl/mice-protein-expression).

Project Overview
The aim of this project is to classify mice into different categories using their protein expression data, which includes information on control vs. Down syndrome mice, behavior stimulation, and drug treatment. This is done using various machine learning algorithms including:

Random Forest
Decision Tree
K-Nearest Neighbors (KNN)
Gradient Boosting
By training these models, we aim to predict the class of a given mouse based on its protein expression levels.

Key Features
Multi-class classification: The project classifies mice into one of eight distinct classes based on genotype, behavior, and treatment.
77 Protein Features: Protein expression levels measured in the nuclear fraction of cortex are used as features for training.
Diverse ML Models: Multiple machine learning models are employed and compared for performance.
Dataset
The dataset contains the expression levels of 77 proteins for 72 mice, comprising both control and Down syndrome (trisomy) mice, some of which were subjected to associative learning tasks.

Total Measurements: 1,080 measurements per protein.
Classes: 8 different classes based on genotype, treatment, and behavior.
Classes:
c-CS-s: Control mice, stimulated to learn, injected with saline.
c-CS-m: Control mice, stimulated to learn, injected with memantine.
c-SC-s: Control mice, not stimulated to learn, injected with saline.
c-SC-m: Control mice, not stimulated to learn, injected with memantine.
t-CS-s: Trisomy mice, stimulated to learn, injected with saline.
t-CS-m: Trisomy mice, stimulated to learn, injected with memantine.
t-SC-s: Trisomy mice, not stimulated to learn, injected with saline.
t-SC-m: Trisomy mice, not stimulated to learn, injected with memantine.
Dataset Source:
The dataset was sourced from Kaggle(https://www.kaggle.com/datasets/ruslankl/mice-protein-expression) and contains detailed protein expression levels and classifications of mice based on genotype, treatment, and behavior.
Models Used
Random Forest: An ensemble learning method that builds multiple decision trees and combines their outputs for classification.
Decision Tree: A tree-based model that splits data into different branches based on feature values.
K-Nearest Neighbors (KNN): A simple algorithm that classifies data points based on the closest neighbors.
Gradient Boosting: An ensemble method that builds models sequentially, improving predictions at each step.
