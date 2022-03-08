# Lending Club Case Study
> A consumer finance company specializing in lending various types of loans to urban customers wants to analyze the risk of approving loan application based on past data


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The aim is to : Understand the driving factors (or driver variables) behind loan default Identify patterns which indicate if a person is likely to default, for taking actions such as – Denying the loan Reducing the amount of loan Lending (to risky applicants) at a higher interest rate.
- Loan Dataset: Loan status can be of the following two types:

  - Loan accepted: If the company approves the loan, there are 3 possible scenarios described below: Fully paid – Paid back loan amount in full. Current – Loan account is still active. Considered in analysis if >90% of term length has been paid. Charged-off – Defaulted. These two terms have been used interchangeably throughout analysis.
  - Loan rejected: The company had rejected the loan, these records are not considered for analysis


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Exercise caution over loans given to very low and low income groups.
- Reduction of Exposure to Grades D,E,F,G.
- Compare the relative LTAI ratio values from the tables provided above to identify a probable default loan application.
- Instead of providing a loan with a term of 60 months with lower instalments, providing a lesser loan amount with a term of 36 months that matches their LTAI and instalment capacity may reduce default.
- It is better to provide a higher loan amount to high annual income applicant having a lower LTAI at lower interest rate than providing a lower loan amount to low income applicant having a higher LTAI at a high interest rate.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib.pyplot
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@Vedakashyap7] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
