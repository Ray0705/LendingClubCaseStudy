# Lending Club Case Study
The company is the largest online loan marketplace, facilitating personal loans, and financing of medical procedures. The aim is to identify patterns which indicates if a person is likely to be defaulted or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is the largest online loan marketplace, facilitating personal loans, and financing of medical procedures.
- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- The data contains the information about past loan applicants from the time period 2007 to 2011. and whether they ‘defaulted’ or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We have did Data cleaning and Exploratory data analysis to get better insights of data. We found following driving variable which will gives us inference about the applicant can be default or not.

Following are the driving variables -
   * **Grade** - We have seen that as the grade is lower than the chance of applicant to be defaulter increases.
   * **Annual Income** - We have seen that as the annual income is increasing the chance of applicant being defaulter is decreases.
   * **Revolving Balance** -  We have seen that as the revolving balance is higher then the chance of applicant being defaulter is also high.
   * **Loan Amount** - We have seen that as the loan amount increases, the possiblity of applicant being defaulter increases
   * **Revolving line utilisation rate** - we have seen that if revolving line utilisation rate is higher then higher chance of applicant to be defaulter.
   * **DTI** - We have seen that higher the dti then higher the chance of applicant being defaulter.
   * **Inquiry in last 6months** - We have seen that if the no. of inquires is more than defaulter rate is also more.

Hence, we have analyzed the lending case study with help of various data cleaning and EDA methods.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.1.5
- Numpy - version 1.18.5
- Matplotlib - version 3.1.3
- Seaborn - version 0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad Team



## Contact
Created by [@Ray0705] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
