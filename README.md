# Credit-Risk-Analysis
Detailed EDA done using python libraries pandas, numpy, matplotlib, seaborn and Scipy.

![image](https://user-images.githubusercontent.com/76435558/133157941-972d531c-c96e-4da6-9e3c-c40de0ee1cd7.png)


# Problem Statement
Good applicants applied for loan are not rejected and to understand how consumer attributes and loan attributes influence the tendency of default. 
To develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending 
to customers. As part of this study we need to perform below tasks:

- Data Understanidng,Cleansing and quality check.
- Univariate and Bi-variate analysis through graphical and statistical analysis.

# Business Objectives
To analyse the patterns in the data to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as 
denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the 
loan are not rejected.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. 
The company can utilise this knowledge for its portfolio and risk assessment.

# Dataset Description
The dataset provided contains all the information of the client at the time of application whether a client has payment difficulties or not and it contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.


![image](https://user-images.githubusercontent.com/76435558/133158033-aa0eaaab-901d-4c75-a162-9c2c998d0df3.png)

# Credit range distribution as per the gender

![image](https://user-images.githubusercontent.com/76435558/133158207-54f3d19d-b317-4008-b1ab-dc821547a61c.png)

### Points to be concluded from the above graph.
- Female counts are higher than male.
- Very low range to medium range have more number of credits.
- This graph show that females are more than male in having credits for that range.
- Very less count of income above medium range and above.

# Distribution of days employed as per occupation

![image](https://user-images.githubusercontent.com/76435558/133158414-1c4a2c9d-6d3c-4f49-a4fd-4e8391b723c2.png)

# Distribution of organization type

![image](https://user-images.githubusercontent.com/76435558/133158587-e546689e-e4d5-45c9-ae2a-c7310f3212b3.png)

# Correlation for target 0

![image](https://user-images.githubusercontent.com/76435558/133159290-5b0334b2-d3c6-4692-b8b5-943604948ab9.png)

### Points to be concluded from above graph
- We observe that there is a high correlation between credit amount and goods price for both the targets.
- Total income is inversely proportional to the date of birth, which means total income is less for low age and vice-versa for both the targets.
- Total income is inversely proportional to the days employed, which means total income is less for low employment number of days and vice-versa for both the targets.

# Education status Vs Credit amount for defaulters

![image](https://user-images.githubusercontent.com/76435558/133159996-7150be10-ad08-4429-8cec-1e45243cde1d.png)

### From above boxplot.
- For Education type 'Higher education' the income amount is mostly equal with family status. It does contain many outliers.
- Less outlier for Academic degree but income amount is higher for Higher education.
- Lower secondary of civil marriage family status have less income amount than others.

# Previous credit amount Vs Housing type

![image](https://user-images.githubusercontent.com/76435558/133160200-89192f61-d5f9-42d4-b27c-d7ab072f25f9.png)

### Points to be concluded from above graph
- For Housing type, office apartment is having higher credit of target 0 and co-op apartment is having higher credit of target
- So, we can conclude that bank should avoid giving loans to the housing type of co-op apartment as they are having difficulties in payment. Bank can focus mostly on housing type with parents or House\apartment or municipal apartment for successful payments.

# CONCLUSION

1. Car ownership doesn't have any effect on application approval or rejection. But we did see earlier that the people who has a car has lesser chances of default. The bank can add more weightage to car ownership while approving a loan amount.

2. Code gender doesn't have any effect on application approval or rejection. But we saw earlier that female have lesser chances of default compared to males. The bank can add more weightage to female while approving a loan amount.

3. We can see that the people who were approved for a loan earlier, defaulted less often where as people who were refused a loan earlier have higher chances of defaulting.

4. Banks should focus more on contract type ‘Student’ ,’pensioner’ and ‘Businessman’ with housing ‘type other than ‘Co-op apartment’ for successful payments.

5. Banks should focus less on income type ‘Working’ as they are having most number of unsuccessful payments.

6. Also with loan purpose ‘Repair’ is having higher number of unsuccessful payments on time.

7. Get as much as clients from housing type ‘With parents’ as they are having least number of unsuccessful payments.
