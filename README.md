# Lending Club Case Study
The aim is to identify patterns which indicates if a person is likely to be defaulted or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is the largest online loan marketplace, facilitating personal loans, and financing of medical procedures.
- The aim is to identify patterns which indicate if a person is likely to be a default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- The data contains the information about past loan applicants from the time period 2007 to 2011 and whether they ‘defaulted’ or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have done Data cleaning and Exploratory data analysis to get better insights of data. We found following driving variable which will give us inference about the applicant can be default or not.

Following are the driving variables -
   * **Grade** - We have seen that as the grade is lower then the chance of applicant to be defaulter increases.
   * **Annual Income** - We have seen that as the annual income is increasing, the chances of applicant being a defaulter decreases.
   * **Revolving Balance** -  We have seen that if the revolving balance is higher then the chance of applicant being defaulter is also high.
   * **Loan Amount** - We have seen that as the loan amount increases, the possibility of applicant being defaulter also increases.
   * **Revolving line utilization rate** - we have seen that if revolving line utilization rate is higher then there is a  higher chance of applicant being a defaulter.
   * **DTI** - We have seen that higher the dti, higher is the chance of applicant being defaulter.
   * **Interest Rate** - We have seen that as the interest rate increases, then the possibility of applicant being defaulter also increases.
   * **Inquiry in last 6months** - We have seen that if the no. of inquires is more, then defaulter rate is also high.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.1.5
- Numpy - version 1.18.5
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.



## Contact
Created by [@Ray0705](https://github.com/Ray0705) and [@AmitPRADH](https://github.com/AmitPRADH) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
