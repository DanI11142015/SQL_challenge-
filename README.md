# SQL_challenge-

#1 we used the inner join query on the salaries table because we needed to pull the salary data for each employee and emp_no was the foreign key on this table that correlated with the employees table 

#2 hire date was the highlight of this anaylsis. to get the hire dates of employees we used the date range within the year of 1986 in the where query. 

#3 and #4 this was a more complex query because we needed to join the employees tables and the department tables to get the employee number and the department number. in the select statement we had to make sure to use the corresponding alias with the collumn we want to return. 

#5 the significance here in the where statement was finding the employees with first name hercules and any last name that began with a B. since our main focal point was the first name we used the B% in the statemnt for last name to return the corresponding last name that began with a B with Hercules first name. 

#6 Here we have another complex query. Although not listed we did find another way to return sales in the departmnet name and we could have listed "sales" vs. how we have the correspodning department number. (We also could have done this for question 7 fo return the sales and development)

#8 We ran this query to return all of the employees last name in descending order and also count how many employees had the same last name. here we used the count query and statemnet "frequency counts" to name the collumn we are extablishing to show how many times this last name is repeating. We used the group by query to only pull last_names and the order by and count query together to count in desecding order of the last names. We can say there are many employees with the same last name in our data. 

