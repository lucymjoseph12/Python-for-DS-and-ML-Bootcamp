## Loan Default Prediction using Random Forest

In this project, we use the publicly available LendingClub dataset for the period of 2007-2010. We use Random Forest Classifier to predict whether a customer with pay back the loan or not. The dataset has the following columns:

**credit.policy**: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.<br />
**purpose**: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").<br />
**int.rate**: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.<br />
**installment**: The monthly installments owed by the borrower if the loan is funded.<br />
**log.annual.inc**: The natural log of the self-reported annual income of the borrower.<br />
**dti**: The debt-to-income ratio of the borrower (amount of debt divided by annual income).<br />
**fico**: The FICO credit score of the borrower.<br />
**days.with.cr.line**: The number of days the borrower has had a credit line.<br />
**revol.bal**: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).<br />
**revol.util**: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).<br />
**inq.last.6mths**: The borrower's number of inquiries by creditors in the last 6 months.<br />
**delinq.2yrs**: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.<br />
**pub.rec**: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).<br />
**not.fully.paid**: 0 if the customer has fully paid the loan, and 1 otherwise.

The model got the following scores (weighted avg):<br />
**Precision: 0.79<br />
Recall: 0.85<br />
F1-score: 0.78**
