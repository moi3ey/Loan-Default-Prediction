# Loan Default Prediction

## Capstone Project: Loan Default Prediction

### Context

A significant portion of retail bank profits comes from interests on home loans, which are typically borrowed by regular income or high-earning customers. Banks are particularly concerned about defaulters, as bad loans (Non-Performing Assets or NPAs) can significantly erode their profits. Therefore, it is crucial for banks to be prudent when approving loans for their customers.

The loan approval process is multifaceted, involving a manual assessment of various aspects of the application to evaluate the applicant's creditworthiness. This process is not only labor-intensive but also prone to errors and biases.

Many banks have attempted to automate this process using heuristics. However, with the advent of data science and machine learning, the focus has shifted to building models that can learn the approval process, making it more efficient and free of biases. It is also important to ensure that these models do not inherit the biases that may have existed in the manual approval process.

### Problem Statement

A bank's consumer credit department aims to simplify the decision-making process for approving home equity lines of credit. To achieve this, they will adopt the Equal Credit Opportunity Act's guidelines to establish an empirically derived and statistically sound model for credit scoring. This model will be based on data obtained from the existing loan underwriting process for recent applicants who have been granted credit. The model should be interpretable enough to provide justifications for any adverse decisions (e.g., rejections).

### Objective

Build a classification model to predict clients who are likely to default on their loan and provide recommendations to the bank on the important features to consider during the loan approval process.

### Data Dictionary

The Home Equity dataset (HMEQ) contains baseline and loan performance information for recent home equity loans. The target variable, `BAD`, is a binary indicator of whether an applicant has defaulted or been severely delinquent. There are 12 input variables recorded for each applicant:

- `BAD`: 1 = Client defaulted on loan, 0 = Loan repaid
- `LOAN`: Amount of loan approved
- `MORTDUE`: Amount due on the existing mortgage
- `VALUE`: Current value of the property
- `REASON`: Reason for the loan request (`HomeImp` = Home Improvement, `DebtCon` = Debt Consolidation)
- `JOB`: Type of job held by the loan applicant (e.g., manager, self-employed)
- `YOJ`: Years at present job
- `DEROG`: Number of major derogatory reports (indicating serious delinquency or late payments)
- `DELINQ`: Number of delinquent credit lines (credit lines that are 30 to 60 days past due)
- `CLAGE`: Age of the oldest credit line in months
- `NINQ`: Number of recent credit inquiries
- `CLNO`: Number of existing credit lines
- `DEBTINC`: Debt-to-income ratio (all monthly debt payments divided by gross monthly income)
