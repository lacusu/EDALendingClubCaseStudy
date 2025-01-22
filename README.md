# Lending Club Case Study

---

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The goal is to reduce **credit loss** by identifying **risky loan applicants (defaulters)** based on patterns in the data. Using EDA, you will analyze consumer and loan attributes to uncover the driving factors behind loan defaults. This information will help the company make better decisions on loan approvals, such as:
- Rejecting risky applications
- Reducing loan amounts
- Increasing interest rates for specific categories of borrowers

### **Classify Loan Outcomes**:
1. **Fully Paid**: Applicants who repaid the loan successfully.
2. **Current**: Applicants still paying their loan installments (not defaulted yet).
3. **Charged-Off**: Applicants who defaulted on the loan, causing financial losses.

> **Applicants in the "Charged-Off" category are considered defaulters.**

### **Identify Driver Variables**
- Analyze consumer demographics, credit attributes, and loan attributes to determine the factors contributing to defaults.
- These insights will guide the company to:
  - Target low-risk applicants
  - Avoid financial losses

## Conclusions

#### Dynamic Risk-Based Pricing
- Adjust interest rates for borrowers in the 10%-15% range to better balance risk and profitability.

#### Enhanced Screening for Debt Consolidation Loans
- Strengthen risk assessment protocols for borrowers applying for debt consolidation, which accounts for the majority of charged-off loans.

#### Income-Driven Assessments
- Incorporate robust income-based criteria to identify high-risk borrowers, particularly those earning below $100K.

#### Refined Loan Structuring
- Introduce caps on debt-to-income ratios to minimize default risks.
- Offer tailored loan amounts and terms based on borrower profiles and repayment history.

#### Employment Tenure Evaluation
- Reassess reliance on employment length as a primary stability factor and consider additional financial metrics.

#### Portfolio Monitoring and Policy Adjustments
- Continuously analyze trends in loan purposes, borrower demographics, and repayment behaviors.
- Utilize predictive modeling to proactively refine risk management strategies.

The notebook for this project can be found [here](https://github.com/lacusu/EDALendingClubCaseStudy/blob/main/Huy_Vo.ipynb).

Presentation slides can be found [here](https://github.com/lacusu/EDALendingClubCaseStudy/blob/main/LendingClubCaseStudyPresentation.pdf).

## Technologies Used
- Python version: 3.12.7 | packaged by Anaconda, Inc.
- Pandas version: 2.2.2
- NumPy version: 1.26.4
- Matplotlib version: 3.9.2
- Seaborn version: 0.13.2

## Acknowledgements
Give credit here.
- This project was inspired by upGrad and IIITB Machine Learning & AI Program
- This project was based on [Exploratory Data Analysis Lesson](https://learn.upgrad.com/course/7715/segment/53501/348418/1051925/5255692).

## Contact
Created by [Huy Vo](https://github.com/lacusu) and [Zoeb Murthuza](mailto:zoeb4s@gmail.com ) - feel free to contact us!
<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->