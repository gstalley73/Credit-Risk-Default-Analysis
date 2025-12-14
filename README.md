# Credit-Risk-Default-Analysis
### Project Overview
This project analyzes borrower credit data to identify the primary reasons for loan default risk. Using exploratory analysis and interpretable risk segmentation, this project demonstrates how financial institutions can assess and manage credit risk in a realistic banking context.

### Business Problem
Financial institutions must evaluate borrower risk while balancing growth and the potential of borrowers' defaulting.
This project focuses on:
- Which borrower factors are most associated with default risk?
- How default risk changes across borrower segments?
- How multiple risk factors can be combined into risk tiers

### Dataset
- 6,000 synthetic borrower records
- Realistic credit and loan attributes
#### Key features
- Credit score
- Annual income
- Debt-to-income ratio (DTI)
- Credit Utilization
- Delinquencies

### Tools Used
- Python
    - pandas
    - numpy
    - matplotlib
- Jupyter Notebook
### Steps of Analysis
1. Data exploration and validation
2. Default rate Analysis by key risk factors
   - Credit Score bands
   - Debt-to-income quartiles
   - Credit utilization quartiles
3. Composite risk score creation
4. Risk segmentation

## Key Insights
- Credit score is the strongest predictor of default, with low credit score individuals defaulting at significantly higher rates.
- Debt-to-income ratio shows a steep increase in default rate as a borrower's ratio increases.
- Credit utilization acts as a strong risk indicator and an early warning sign of borrowers' defaulting.
- The composite risk score demonstrates strong discriminatory power, with default rates increasing from ~1% in the lowest-risk decile to 70% in the highest-risk decile.

