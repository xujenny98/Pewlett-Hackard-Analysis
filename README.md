# Pewlett-Hackard-Analysis
# Overview of the Analysis
<br/>Pewlett Hackard is a large corporation with large number of employees who is going to be retired soon and its important for the management to see and analyze this upcoming "Silver Tsunami". In particular, the management want to see the number of retiring employees per title and to identify employees eligible to participate in a mentorship program.

# Results:
# 1.Retiring Employees per Title Analysis
- A table showing titles wise employees who were born between 1952 and 1955 and are retiring. The snapshot of the table is below:
<img width="783" alt="Screen Shot 2021-04-03 at 11 22 56 PM" src="https://user-images.githubusercontent.com/77771292/113497610-c17ae880-94d3-11eb-895f-7cf3aa00fb81.png">
<br/>The total number of entries or employees as per this data is 133776 but there is one issue with this table that there are many duplicate entries where one employee got promoted over the time and his/her name appeared more than once with old and new title. So we did further filtering on the data.

- <br/>Next table shows data from 1st table without duplicate entries meaning a single employee is mentioned only once with his/her latest title. This time we got the correct figure of these retiring employees. Their number is 90398. The snapshot of this table is below:
<img width="626" alt="Screen Shot 2021-04-03 at 11 29 04 PM" src="https://user-images.githubusercontent.com/77771292/113497701-6e556580-94d4-11eb-83f6-7977069cf3a7.png">

- Then we further filtered the data to show the title wise number of employees retiring and below is the complete table.
<img width="505" alt="Screen Shot 2021-04-03 at 11 29 59 PM" src="https://user-images.githubusercontent.com/77771292/113497713-862ce980-94d4-11eb-9852-7aa1d39f5556.png">
This table tells us that highest number of employees are retiring under the title of Senior Engineer. The sum of all these retiring employees is 90398 as earlier mentioned.

# 2.Eligible Mentorship Analysis
- <br/>Next we analyzed the data to provide the details of the employees who might be eligible for Mentorship. The criteria for this selection was the employees who were born in 1965 and they are still the employees of the firm. Again this data also contain the information of their titles. The snapshot of this table is below:
<img width="868" alt="Screen Shot 2021-04-03 at 11 17 53 PM" src="https://user-images.githubusercontent.com/77771292/113497744-b83e4b80-94d4-11eb-8097-82e13078a8b5.png">

# Summary:
<br/>The summary addresses the two questions and contains two additional queries or tables that may provide more insight. 
<br/>Q1- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
<br/>Ans-Based on the analysis of the retiring employees who were born between 1952 and 1955. 
<br/>Number of Roles/Titles of these retiring employees: 7 
<br/>Number of people retiring : 90398. 
<br/>**No of Retireing Employees**
<br/><img width="468" alt="Screen Shot 2021-04-05 at 1 26 38 AM" src="https://user-images.githubusercontent.com/77771292/113540387-0ecb8880-95ae-11eb-911c-d1f110af658c.png">

<br/>Q2-Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
<br/>Ans- The total number of employees who are retiring are 90398 and employees eligible for Mentorship are 1549. Further analysis has been done under each title to see whether there are enough people in Retirement Ready list to provide mentorship in Mentorship Eligibility list and the result shows us that there are more than enough people under each title who are retiring and can give mentorship
<br/>**Employees Eligible for Mentorship**
<br/><img width="762" alt="Screen Shot 2021-04-05 at 1 20 48 AM" src="https://user-images.githubusercontent.com/77771292/113540098-5d2c5780-95ad-11eb-8a46-ecb2ddb7f42c.png">
<br/> **Employees Ready for Retirement**
<br/><img width="314" alt="Screen Shot 2021-04-05 at 1 24 55 AM" src="https://user-images.githubusercontent.com/77771292/113540283-cb711a00-95ad-11eb-8348-dd7c887589f1.png">



