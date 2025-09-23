# HgPollution-Modeling
Machine learning models for predicting methylmercury levels in Ghana’s water bodies, addressing the environmental impact of artisanal illegal mining ('galamsey') on communities.

# MercuryML-Ghana

**MercuryML-Ghana** is a machine learning project focused on predicting **methylmercury (MeHg) concentrations** in Ghana’s water bodies.  
The project is motivated by the **galamsey (illegal mining) crisis**, which has led to mercury contamination of rivers, lakes, and groundwater — threatening human health, aquatic life, and sustainable livelihoods.

## Problem 
Illegal small-scale gold mining (galamsey) uses mercury in the extraction process. Mercury often leaches into water bodies, where it is converted by microbes into **methylmercury**, a neurotoxic compound that bioaccumulates in fish and threatens communities who depend on these waters.  
This project seeks to explore **data-driven solutions** to model and predict mercury levels, supporting informed policies and sustainable water management.

## Project Objectives
- Preprocess and analyze environmental datasets relevant to mercury levels in water.  
- Build regression models (starting with Linear Regression) to predict MeHg concentrations.  
- Provide open-source tools and datasets for researchers, NGOs, and policymakers.  
- Contribute to sustainable solutions to Ghana’s galamsey-driven pollution crisis.  

## Dataset
The dataset contains:
- Environmental features (pH, temperature, dissolved oxygen, organic carbon, etc.)  
- Target: **Methylmercury concentration in water (ng/L)**  

Data is sourced from public environmental monitoring repositories.  
*(Preprocessed data is included in `preprocessed_data.csv` for reproducibility.)*

## Methods
- Data preprocessing and cleaning in Python (Pandas, NumPy)  
- Exploratory Data Analysis (EDA)  
- Regression modeling (Linear Regression as baseline)  
- Model evaluation using R² and RMSE  

## Next Steps
- Incorporate more advanced models (Random Forest, XGBoost).  
- Expand dataset with local Ghana water monitoring data.  
- Build a simple web dashboard for policymakers and community groups.  

## Impact
By predicting mercury concentrations, this project supports:
- Cleaner water initiatives in Ghana.  
- Evidence-based policymaking against galamsey.  
- Community-led environmental protection.  

---

## Data Source  

The dataset used in this project was obtained from the [USGS / EPA STORET Data Repository – Englebright Lake Mercury Monitoring Project](https://www.ebi.ac.uk/biostudies/ArrayExpress/studies/E-MTAB-9534?query=cancer) (accessed September 2025).  

All rights and credits belong to the original data providers.  


