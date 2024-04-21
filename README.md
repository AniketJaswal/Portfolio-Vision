<h3>This project involves using the loan application records of a bank for the year 2021 in order to gain information about the following key performance indicators:</h3>  
                       <li> Total Loan Applications
                       <li> Total Funded Amount
                       <li> Total Amount Received
                       <li> Average Interest Rate
                       <li> Average Debt-to-Income Ratio (DTI)      

<h3>The following steps were followed while developing this project:</h3>

<I><B>Data preparation phase</B></I>
<br/>In order to prepare the dataset for use in the project, data exploration was done to find fields of interest and data cleaning was done to ensure that invalid/missing data was corrected so to eradicate the possibility of incorrect insights in the final report. 

<I><B>Working with SQL</B></I>
<br/>The clean data obtained from the data preparation phase was loaded into MySQL Workbench.SQL queries were created and executed for the creation of KPIs and various fields of interest to find patterns and trends in the data.

<I><B>Working with Power BI</B></I>
<br/>In order to represent the data visually , the cleansed data from preparaion phase was loaded into Power BI and underwent furthur exploration. DAX measures were used to create new attributes from the existing attributes.

<h3>The project consists of different dashboards with each performing a different task. They are as follows: </h3>

<B><I>Summary dashboard</I></B>

In order to evaluate the performance of the bank, a comprehensive report that distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria was created which involved the usage of the following KPIs wrt to Good Loans and Bad Loans: 

<B>Good Loan KPIs:</B>
<li>Good Loan Application Percentage
<li>Good Loan Applications
<li>Good Loan Funded Amount
<li>Good Loan Total Received Amount

<B>Bad Loan KPIs:</B>
<li>Bad Loan Application Percentage
<li>Bad Loan Applications
<li>Bad Loan Funded Amount
<li>Bad Loan Total Received Amount


<br/><B><I>Overview Dashboard</I></B>

Here we visually represent critical loan-related metrics and trends using a variety of chart types. These charts will provide a clear and insightful view of operations, facilitating data-driven decision-making and enabling us to gain valuable insights into various loan parameters. Below are the specific chart requirements:
<li>Monthly Trends by Issue Date (Line Chart):
<li>Regional Analysis by State (Filled Map):
<li>Loan Term Analysis (Donut Chart):
<li>Employee Length Analysis (Bar Chart):
<li>Loan Purpose Breakdown (Bar Chart):
<li>Home Ownership Analysis (Tree Map):

                     
In order to make the dashboard interactive and easy to use, filters were added that allow the dashboard to be changed as per various parameters such as pizza category, the range of day in which the pizzas were sold or to check for sales' records for a specific day.

<I><B>Comparison phase</B></I>
<br/>This was the final step of the project where the created dashboard was compared with the outputs received from the SQL queries in order to ensure that the dashboard created provided correct insights .
