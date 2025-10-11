# globaltech
I explain my process for solving the questions with the help of excel
# ans to 1st ques
The Employees who have been with the company for more than 10 years are Henry Wright,John Brown,Daniel Perez,William Davis,Laura Doe,Emily Campbell,Daniel Scott,James Johnson,Sofia Mitchell,Alexander Hall.
I clicked on the dropdown menu of the column "years of experience" and then selected number filters, then selected "greater than" and entered the number 10 in the custom filter
<img width="1920" height="1200" alt="employees w highest experience" src="https://github.com/user-attachments/assets/a7f429e5-9bcf-41ff-b755-957749f686a6" />
# ans to ques 2
I inserted a pivot table in a new worksheet and dragged department to columns and years of experience to values. I changed years of experience as average years of experience by chooosing average from value field settings. I formatted the average years of experience column as "numbers" and then right clicked on a value on the column and sorted it from largest to smallest. now we can see the dept with the highest avg years of experience is operations
<img width="1920" height="1200" alt="employees w highest experience" src="https://github.com/user-attachments/assets/5f020106-18cb-43a8-af39-f87b88e73ca9" />
# ans to ques 3
I select my data and insert a pivot table in the new worksheet. From pivot table fields, I dragged department to rows and salary to values. From the value field settings, I changed 'count of salary' to 'average of salary' and then go to number format to set it as currency. While trying to change it to average of salary we faced an "#div/0!".  I solved the issue by changing the dalary data by cleaning. I did this by clicking on the header of the salary column and then by using text to column, selecting delimited, unchecking all delimiters, then clicking finish. Then I formatted the salary column as numbers. Now I go back to the pivot table to refresh it and find that the error is gone. The average salary per department is shown below.
<img width="1919" height="1134" alt="avg salary dept wise" src="https://github.com/user-attachments/assets/c27eba0b-ad3a-4239-9b39-1fbe82f7f569" />
# ans to ques 4
I calculated the average salary per department via the averageif function after inserting a new column beside salary column and naming it as 'AVG dept salary'.Then I inserted another column called salary class beside the newly created column in column H. In H2 I entered a formula to depict those employees as high class who have their salary higher than the avg dept salary of their respective dept. The image below shows the high class employees
<img width="1919" height="1129" alt="high class employees" src="https://github.com/user-attachments/assets/dc81274d-35de-4b25-bd46-8a1c7c379608" />
# ans to ques 5
I inserted a pivot table in a new worksheet and then dragged country to rows and the dragged city to rows right after that. Then I dragged EmployeeID to values and it is set as count of employees. Then I right clicked on any country name in the pivot table and selected 'sort'. then I selected 'more sort options' and then choose descending and select 'count of employeeID' in the criteria below descending option. The following screenshot depicts that USA is the country with the largest workforce.
<img width="1919" height="1126" alt="country with largest count of workforce" src="https://github.com/user-attachments/assets/a4d801e4-ab0b-4c94-8485-4303c8887e2c" />
Now I removed the country field from the rows section of pivot table.Then I right clicked on any city name in the pivot table and selected 'sort', then I selected 'more sort options' and then choose descending and select 'count of employeeID' in the criteria below descending option. The following screenshot depicts that Toronto, Paris and Berlin are the cities with the largest workforce.
<img width="1919" height="1133" alt="city wiith largest count of workforce" src="https://github.com/user-attachments/assets/8fe639c1-f6f1-4b34-aa2e-84c7c27eca30" />
# ans to ques 6
I inserted a pivot table in a new worksheet and then dragged Department field to rows and Country field to columns. Then i dragged empID to values. The following image shows the summary table showing department distribution by country.
<img width="1914" height="1134" alt="Screenshot 2025-10-12 030126" src="https://github.com/user-attachments/assets/4c22d878-7ecc-4c57-bc5d-441b7714608b" />
# ans to ques 7
I selected the data (years Experience and Salary columns) and then went to the insert tab to select the scatter chart from the chart icon. The scattered chart that appeared shows a positive relation. Then I clicked on the chart and chart elements option appear af This means salary is increased slightly due to years of experience but there are other factors which make the two entities having twso selfish
<img width="777" height="487" alt="Screenshot 2025-10-12 034524" src="https://github.com/user-attachments/assets/8d0332d8-a803-4cb8-8a60-eb8683445fa1" />
