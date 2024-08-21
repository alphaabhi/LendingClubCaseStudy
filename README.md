# EDA Loan Default Analysis

## General Information
This project focuses on conducting an Exploratory Data Analysis (EDA) to identify key factors that contribute to loan defaults. The analysis is performed on a dataset provided by a consumer finance company that specializes in lending various types of loans to urban customers. By understanding the variables influencing loan defaults, the company aims to improve its risk assessment strategies, thereby minimizing financial losses.

### Business Problem
The company must decide whether to approve or reject loan applications based on an applicant’s profile. The risks involved are:
- If the applicant is likely to repay the loan, not approving the loan results in a loss of business.
- If the applicant is likely to default, approving the loan results in a financial loss.

### Dataset
The dataset contains historical loan data from 2007 to 2011, including loan amounts, interest rates, borrower information, and loan status (Fully Paid, Charged Off, or Current).

## Analysis Approach
- **Data Cleaning:** Handle missing data, remove irrelevant columns, and standardize formats.
- **Univariate Analysis:** Examine the distribution of key variables like loan amounts, interest rates, and debt-to-income ratios.
- **Bivariate Analysis:** Explore relationships between the loan status and key variables to identify patterns that correlate with loan defaults.
- **Multivariate Analysis:** Use correlation analysis to identify the most significant drivers of loan defaults.

## Results
The analysis identified the following key factors contributing to loan defaults:
- **Higher Interest Rates:** Loans with higher interest rates are more likely to default.
- **Higher Debt-to-Income Ratio (DTI):** Borrowers with higher DTI are at a greater risk of defaulting.
- **Recent Delinquencies:** Borrowers who have had recent delinquencies are more likely to default on new loans.
- **Loan Amount:** Although the loan amount has some influence, it is less predictive of defaults compared to interest rates and DTI.

## Technologies Used
- Python 3.12
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Repository Structure
- `loan.csv`: The dataset used for analysis.
- `EDA_Loan_Default_Analysis_Presentation.pptx`: A presentation summarizing the analysis results.
- `Group_Facilitator_Abhinav.ipynb`: The Jupyter notebook containing the full analysis.
- `README.md`: This README file.

## Acknowledgements
This project was inspired by the need to enhance risk analytics in the banking sector. The dataset was provided as part of a case study on credit risk analysis.

## Contact
Created by [Abhinav Jha] - feel free to reach out if you have any questions or suggestions.
