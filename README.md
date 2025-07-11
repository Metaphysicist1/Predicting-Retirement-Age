# Predicting Retirement Age

## Repository Link

[https://github.com/Metaphysicist1/Predicting-Retirement-Age/]

## Description

About
This is a data science project focused on predicting retirement age using advanced machine learning techniques applied to the Survey of Health, Ageing and Retirement in Europe (SHARE) Wave 6 dataset. This longitudinal micro-data infrastructure provides rich information on health, socio-economic factors, and retirement behaviors of individuals aged 50+ across 17 European countries and Israel. The project aims to uncover insights into the aging process and inform policy by developing robust classification models to predict retirement age categories (e.g., early, normal, late). Key steps include comprehensive data preprocessing, model development, and evaluation, with a focus on bio-medical and socio-economic predictors.

**Acknowledgment**: This project uses data from SHARE Wave 6 (DOI: [insert relevant DOI]), see Börsch-Supan et al. (2013) for methodological details.

### Task Type

Classification

### Results Summary

- **Best Model**: XGBoost Classifier
- **Evaluation Metric**: Accuracy, AUC-ROC
- **Result**: 85% Accuracy, 0.88 AUC-ROC

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**  
   Overview of existing research on aging, retirement, and machine learning applications, including key references for SHARE (Börsch-Supan et al., 2013; Malter & Börsch-Supan, 2017).

2. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)**  
   Exploratory data analysis (EDA) of SHARE Wave 6, including visualizations of demographic, health, and socio-economic variables.

3. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**  
   Implementation and evaluation of a baseline logistic regression model for predicting retirement age categories.

4. **[Model Definition and Evaluation](3_Model/model_definition_evaluation.ipynb)**  
   Development and evaluation of advanced models (Random Forest, XGBoost) with feature importance analysis and performance metrics.

5. **[Presentation](4_Presentation/README.md)**  
   Presentation slides summarizing the project methodology, results, and policy implications.

## Cover Image
![Sharelogos50+_rz-2](https://github.com/user-attachments/assets/3331ab31-42b3-4ce7-8ca6-ce56ad597236)

## Citations

- Börsch-Supan, A., Brandt, M., Hunkler, C., Kneip, T., Korbmacher, J., Malter, F., Schaan, B., Stuck, S., & Zuber, S. (2013). Data Resource Profile: The Survey of Health, Ageing and Retirement in Europe (SHARE). _International Journal of Epidemiology_, DOI: 10.1093/ije/dyt088.
- Malter, F., & Börsch-Supan, A. (Eds.) (2017). _SHARE Wave 6: Panel innovations and collecting Dried Blood Spots_. Munich: Munich Center for the Economics of Aging (MEA).

## Notes

- **Data Access**: The SHARE Wave 6 dataset is available through the SHARE Research Data Center (http://www.share-project.org) upon registration and compliance with data usage agreements.
- **Ethical Use**: Ensure 
ethical handling of sensitive health and socio-economic data as per SHARE guidelines.
- **Dependencies**: Python (pandas, scikit-learn, XGBoost, matplotlib, seaborn) for analysis and modeling.
