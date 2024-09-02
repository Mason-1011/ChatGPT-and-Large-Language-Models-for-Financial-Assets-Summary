# ChatGPT-and-Large-Language-Models-for-Financial-Assets-Summary
Degree project in Informatics School, University of Edinburgh

Two annual reports folders contian the folders of companies in each there are annual report pdf and the middle output of the model.

Knowledge folder contain the Key metrics information in MSCI ESG methodology.

Output folder contain all csv output from the model.

Dataset:

- MSCI-Weight.csv, Weights of each Key issues in different Industries for ESG Rating
- Union_Scores_of_companies_in_FTSE-allshares&RUSSELL-3000_from_MSCI_SP_Sustainalytics.csv , more detail see Data Sources-ESG Performance.pdf
- Companies_Industry folder, a spider to gain the industry of the company and a dataset
- Three ipynb files, spider to gain ESG information from three agencies, result is Union_Scores_of_companies_in_FTSE-allshares&RUSSELL-3000_from_MSCI_SP_Sustainalytics.csv

Get_Governance_text.ipynb: Model do PDF -> Governance information

Get_Summary&Score.ipynb: Model do Governance information -> Summary and Score

Scores_analysis.ipynb: analys the correaltion between scores
