
# E-Commerce Dashboard with Tableau

## Tableau Dashboard Output

![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Tableau%20Dashboard.png?raw=true)

## Table of Contents

1.  [Overview](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Overview)
2.  [Motivation](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Motivation)
3.  [Workbook-Layout](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Workbook-Layout)
4.  [Workflow](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Workflow)
5. [Outputs](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Outputs)
6.  [Challenges I Faced](https://github.com/Kens3i/TableauEcommerceDataAnalysis#Challenges-I-Faced)


## Overview
Analyzed an e-commerce database where there has **approx. 5000 columns** using **Tableau Public**. The data is about a website named "GoShopping" and the data contains the information about the incoming traffic by the different users. **Any relevant data added will be updated in the dashboard automatically upon refresh**.
Click **[HERE](https://public.tableau.com/views/EcommerceWebsiteVizualisation/Dashboard?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)** to view the dashboard.

## Motivation

This project helped me develop my **Data Dashboarding and Tableau**. I also got to know how different graphs work and how **KPIs** are set in a dashboard.

## Workbook-Layout

- Data Source.

- One Sheet for each Analysis.

- Dashboard Sheet.


## Workflow

- In the first use case the question that comes to mind when seeing the data is to **Find how many users are from each country** so I have taken the country column in the column section of tableau and inserted the total country count in the row section and the output is this where you can see that there are 4 users from India, 8 users from UK and 11 users from USA.

- In the second use case the question is **How many unique users had searched for product "eyewear"**. So I have plotted a horizontal bar chart and placed a filter which checks if “eyewear” string is present in the URL column or not. In the output we can see that which user has the highest number of searches.

- In the next visualization I have just counted all the **unique users who have searched for the product “eyewear”** and as we can see the answer is 12.

- Next I have calculated the **total spent for each user on the GoShopping website**. So, in the column section I have placed the User IP and in the rows section we have placed the total sum of time spent and as a result you can see the total time spent of each user where darker the color resembles more the time spent by the user.

- Next I have found out the **user which has spent the maximum amount of time on the website**. To make it easier to visualize I have sorted the total timespent in descending order so the first row shows the result that we want to achieve.

- After that I am displaying **which user has spent minimum time in GoShopping website**. This slide is similar to the previous visualization difference is the colour scheme, where the lighter the colour the less time spent that particular user has spent in the website.

- Finally I have created a **Final Dashboard** using all the use cases and displayed it in such a manner that anyone could understand.


## Outputs

- **Users from each Country**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Users%20from%20each%20country.png?raw=true)

- **Users who searched for product "eyewear"**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/All%20users%20searched%20for%20product%20eyewear.png?raw=true)

- **No. of unique users searched for product "eyewear"**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/No.%20of%20unique%20users%20searched%20for%20product%20eyewear.png?raw=true)

- **Time spent by each user in the GoShopping website**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Time%20spent%20by%20each%20user.png?raw=true)

- **The user who has spent max time in GoShopping website**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Max%20time%20spent%20by%20an%20user.png?raw=true)

- **The user who has spent min time in GoShopping website**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Min%20time%20spent%20by%20user.png?raw=true)

- **Final Dashboard**
![](https://github.com/Kens3i/TableauEcommerceDataAnalysis/blob/main/Images/Tableau%20Dashboard.png?raw=true)

## Challenges-I-Faced

- It original data was in .tsv file i.e tab separated value so I used MS Excel to convert the file into .xlsx and then I was able to analyze the data..


### Thankyou For Spending Your Precious Time Going Through This Project!
### If You Find Any Value In This Project Or Gained Something New Please Do Give A ⭐.
