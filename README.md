# Lending Club Case Study


## Table of Contents
* [Introduction to Problem Statement](#Introduction)
* [Business Understanding](#Understanding)
* [Business Objectives](#Objectives)
* [Results Expected](#Results)
* [Why this Project](#Why)



#### Introduction to Problem Statement <a name="Introduction"></a> 

<p style='color:Purple'>
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:</p><li style='color:Purple'>If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company </li>
<li style='color:Purple'>If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company </li>
<p style='color:Purple'>
</br>
    As a part of this case-study, we will utilize EDA to understand how consumer attributes and loan attributes influence the tendency of default.
</p>
<b> ================================================================================================================================================================================</b>

#### Business Understanding <a name="Understanding"></a>

<p style='color:purple'>
When a person applies for a loan, there are two types of decisions that could be taken by the company: </br>
1. <b>Loan accepted:</b> If the company approves the loan, there are 3 possible scenarios described below: </br>
2. <b>Fully paid:</b> Applicant has fully paid the loan (the principal and the interest rate) </br>
3. <b>Current:</b> Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'. </br>
4. <b>Charged-off:</b> Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan  </br>
5. <b>Loan rejected:</b> The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
</p> 
<b> ================================================================================================================================================================================</b>


#### Business Objectives <a name="Objectives"></a>

<p style='color:purple'>
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. </br> </br>
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, <b>the customers labelled as 'charged-off' are the 'defaulters'.</b>  </br></br>
If one is able to identify these risky loan applicants, then such loans can be reduced thereby <b>cutting down the amount of credit loss</b>. Identification of such applicants using EDA is the aim of this case study. </br></br>
In other words, <b>the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.</b> </br></br> 
To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough). </br>

 
</p> 
<b> ================================================================================================================================================================================</b>
#### Results Expected <a name="Results"></a>
<p style='color:purple'>
1. Write all your code in one well-commented Python file; briefly mention the insights and observations from the analysis </br>
2. Present the overall approach of the analysis in a presentation: </br>
3. Mention the problem statement and the analysis approach briefly </br>
4. Explain the results of univariate, bivariate analysis etc. in business terms</br>
5. Include visualisations and summarise the most important results in the presentation</br>
 
</br>
You need to submit one Ipython notebook which clearly explains the thought process behind your analysis (either in comments of markdown text), code and relevant plots. 
</p>
<b> ================================================================================================================================================================================</b>

#### Why this project?

This project is a case-study which is done as a part of Executive PG program offered by IIIT- Bengaluru.
<b> ================================================================================================================================================================================</b>


## Contact
Created by [@palashbaranwal] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->