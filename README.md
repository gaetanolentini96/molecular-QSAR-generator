# Virtual Molecular Library & MolLogP Prediction

This project generates a virtual library of molecules from chemical scaffolds, 
computes molecular descriptors, and predicts lipophilicity (MolLogP) using machine learning.

## Steps
1. Scaffold-based combinatorial library generation (RDKit)
2. Descriptor calculation and Lipinski filter
3. Random Forest regression for MolLogP prediction
4. Feature importance analysis
5. Tanimoto similarity & chemical diversity visualization

## Results
- Total molecules: 1452  
- R² (test): 0.87  
- MAE: 0.50  
- Top features: TPSA, NumHAcceptors, MolWt

## Tools
Python · RDKit · scikit-learn · pandas · seaborn

## Author
Gaetano Lentini — Drug discovery & data science enthusiast
