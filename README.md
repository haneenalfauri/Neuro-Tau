#Neuro-Tau
This repository contains the code and documentation for my research project utilizing the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset.

**Overview**
This project aims to develop and validate predictive models for tau biomarker proteins in various brain regions associated with Alzheimer's disease. We employed Multi-Layer Perceptron (MLP) models using longitudinal data from the ADNI dataset, specifically the Berkeley version. Implementing stratified splits ensured balanced class distributions and improved model robustness. An ablation study was conducted to evaluate prediction MAE across features such as demographics, tau values, amyloid values, and patient health information.

Multilayer perceptrons have demonstrated promising predictive performance for tau protein accumulation in the brain. We utilized a grid search and nested cross-validation approach to ensure robust predictive performance across different outer folds. An ablation study and feature importance analysis revealed the significance of demographic and regional connectivity features in accurately predicting tau accumulation. However, our results identified outliers requiring further inspection, particularly in younger age groups and patients carrying two copies of the APOE4 gene. Future work aims to enhance noise assessment and refine predictive models to address these discrepancies effectively.

**Repository Structure**
Neuro_Tau.pdf: A comprehensive report detailing the full project description.
Tau_Prediction.ipynb: The Python notebook for the project.

**Data Access**
The raw data used in this project is from the ADNI dataset, which is restricted and requires access approval. To obtain access to the ADNI data, follow these steps:
1. Visit the ADNI Data Access page. https://adni.loni.usc.edu/data-samples/access-data/
2. Apply for access by completing the necessary forms and agreeing to the data use agreement.
3. Once approved, download the relevant data for your analysis.




Feel free to explore the repository and reach out if you have any questions or need further assistance. :)
