# Loan Data Analysis – Onyx September DataDNA Challenge
A project to analyze loan risk and customer behavior machine learning on the Onyx DataDNA dataset. The insight then can be used to build a Power BI dashboard

## Dataset
Link: https://docs.google.com/spreadsheets/d/1yh0fJhXUvzZ5ZRagJHTbKa2E7bOgHRQX/edit?usp=sharing&ouid=117486058648754460757&rtpof=true&sd=true
## Overview
This project demonstrates a data-driven approach to segment customers based on loan risk and identify potential default patterns. Machine learning models were used to estimate default probabilities and get Feature Importance / SHAP Values, and as an added bonus: Thompson Sampling demo was applied to optimize risk mitigation strategies per segment.

## Dataset
- Source: Onyx DataDNA Challenge  
- Data includes 30,000+ customers with features such as demographics, account information, and financial metrics.  
- Each customer is labeled with loan outcomes (default / non-default).

## Notebook
- datadna.ipynb: contains the analysis and ML
- thompson_sampling.ipynb: contains the code for prescriptive thompson sampling. This part isn't needed for DataDNA, just for self exploration and learning.

## Results
- Segmented customers into meaningful clusters based on risk and behavior.  
- Estimated default probabilities per customer to inform risk strategies.  
- Applied Thompson Sampling to prioritize interventions, improving decision-making efficiency.

## License
This project is for educational purposes only. Contact the author for reuse or commercial purposes.
