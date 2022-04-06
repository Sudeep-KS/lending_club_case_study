# Lending club case study
> We are a Consumer Finance Company which specializes in lending various types of loans to urban customers.
We must decide for loan approval based on the applicant’s profile.
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company.
We are provided with information about past loan applicants and whether they ‘defaulted’ or not.
The aim is to identify patterns to understand the driving factors (or driver variables) behind loan default to understand the driving factors (or driver variables) behind loan default.



## Table of Contents
* Data Analysis
* Data Cleaning
* Univariate Analysis
* Bivariate Analysis
* Recommendations

<!-- You can include any other section that is pertinent to your problem -->

## Data Analysis
- We first need to analyze the data frame provided to us, that is the Loan.csv file
- For this purpose, we read the file and display the head , this gives me a glimpse into all the data I have in the Data frame
- I also check mode details using info function which gives us the total number of rows in the data frame
- Code from the python book :
	loan= pd.read_csv(r'loan.csv’)
	loan.head()
	loan.info()

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Data Cleaning
- Now that the data is analyzed, and we know the number of columns and entry details
- We must now understand all various columns from the dictionary provided
- Once we have been familiarized with the details of all columns, we must identify and remove unwanted data 
- We must identify outliers or single value data and remove them from the data frame
	Delete columns :
	Remove Outliers/Unique values
	Remove missing values
	Remove duplicates if present
	Filter and optimize entries/rows if required

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Univariate Cleaning
- As data is cleaned and prepared, we will now try to understand the correlation between the different numeric fields
- We now find correlation between different values and fields.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Bivariate Cleaning
- We now try to find correlation and analysis of two or more variables

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Conclusions
- Recommendations 1 from the analysis :
<!---->
	Higher interest rate (above 13%)
	Higher revolving line utilization rate (above 58%)
	Repayment term (5 years)
	Loan grade & sub-grade (D to G)
	Missing employment record
	Loan purpose (small business, renewable energy, educational)
	Derogatory public records (1 or 2)
	Public bankruptcy records (1 or 2)
- Recommendations 2 from the analysis :
<!---->
	Higher interest rate (above 13%)
	Higher revolving line utilization rate (above 58%)
	Repayment term (5 years)
	Loan grade & sub-grade (D to G)
	Missing employment record
	Loan purpose (small business, renewable energy, educational)
	Derogatory public records (1 or 2)
	Public bankruptcy records (1 or 2)
- Recommendations 3 from the analysis:
<!---->
	-Higher loan amount (above 16K)
	-Higher installment amount (above 327)
	-Lower annual income (below 37K)
	-Higher debt to income ratio (above 15%)
	-Applicant’s address state (NV, SD, AK, FL, etc.)
	-Loan issue month (Dec, May, Sep)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook
- Microsoft Office

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [sudeep.ks@hotmail.com] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
