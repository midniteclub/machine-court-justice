# Supreme Court Judgment Prediction

## Overview
This project aims to explore, analyze, and predict outcomes of cases based on historical data from the Supreme Court. Ideal for legal scholars, data scientists, and enthusiasts interested in the intersection of law and technology.
This repository contains the work for a project inspired by my Applied Cloud Computing course at Drexel University. The project focuses on predicting the outcomes of Supreme Court cases based on various features extracted from case records. Utilizing logistic regression models, this analysis aims to uncover patterns and insights into the factors influencing case outcomes while achieving a binary classification prediction accuracy of 60% when only considering "the facts".

The dataset used for this project is sourced from Kaggle and comprises records of Supreme Court judgments, including details such as the case facts, issue areas, majority and minority votes, and outcomes.

    https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction
    
The notebook does not need local data files to run unless something went wrong with the GCS bucket. 
Alternatively, code is provided in the notebook for local directory use with the provided .csv data file (or download from Kaggle).
 
## File Structure

    DSCI_632_Final.ipynb: Jupyter notebook containing the project's code, from data preprocessing to model evaluation.
    justice.csv: CSV data file downloaded from Kaggle.
    README.md: This file, providing an overview of the project and guidance for navigating the repository.

## Future Work

While this project provides valuable insights into predicting Supreme Court case outcomes, several avenues for future research and development can enhance our understanding and the model's predictive performance further. Key areas of future work include:

### Ablation Study
An ablation study would be instrumental in better identifying and quantifying the influence of each feature on the model's success. By systematically removing or masking features from the model and observing the impact on performance metrics, we can isolate the contribution of individual features to the prediction accuracy. This approach will allow us to refine our feature set, potentially leading to more streamlined and interpretable models that maintain high levels of accuracy.

### Advanced Text Analysis
Further exploration into advanced natural language processing (NLP) techniques could provide deeper insights from the facts text data. Techniques such as word embeddings, topic modeling, and sentiment analysis using more sophisticated models (e.g., BERT or GPT-based models) could enhance the model's ability to understand and leverage the nuances in legal text for prediction.

### Incorporating Additional Data
Expanding the dataset with more cases, including those from lower courts or incorporating additional metadata such as the background of justices, could enrich the analysis. Additionally, external data sources like legal scholar analyses, public opinion on cases, or media coverage might provide auxiliary information that could be predictive of case outcomes.
