<h1>Apply filters to SQL queries</h1>


<h2>Project description</h2>
For this project I played the part of a Cybersecurity Analyst working on a security team for an organization. It was my job to examine logs in a timely fashion using SQL queries to filter log data for user logins and employee computers for updates.<br/><br/>

<h2>Retrieve after hours failed login attempts</h2>
I was charged to investigate a potential security incident that occurred after 18:00 which is after normal business hours. The following code demonstrates how I filtered failed logon attempts after normal business hours using a SQL query.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/R1OgQmL.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

 In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all collumns from log_in_attempts table. Then it uses the WHERE clause with an AND operator to filter the results to output all of the logon attempts that occured after 18:00 and were not successful.</br></br>
 
<h2>Retrieve login attempts on specific dates</h2>

A suspicious event occurred on 2022-05-09. To investigate this event, I wanted to review all login attempts which occurred on that day and the day before. I used filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 and 2022-05-08.</br></br>

<p align="center">
<img src="https://i.imgur.com/pAPISSU.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all columns from log_in_attempts table. Then it uses the WHERE clause with an OR operator to filter the results to output all of the logon attempts that occured between '2022-05-09' and '2022-05-08'.</br></br>

<h2>Retrieve login attempts outside of Mexico</h2>

There’s was suspicious activity with login attempts, but the team has determined that this activity didn't originate in Mexico. I needed to investigate login attempts that occurred outside of Mexico. I used filters in SQL to create a query that identified all login attempts that occurred outside of Mexico.</br></br> 

<p align="center">
<img src="https://i.imgur.com/6BhvCIo.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all columns from log_in_attempts table. Then it uses the WHERE clause with an NOT operator to filter the results to output all of the logon attempts that did not occurred in Mexico.</br></br>

<h2>Retrieve employees in Marketing</h2>

My team wanted to perform security updates on specific employee machines in the Marketing department. I was responsible for getting information on the specific employee machines and needed to query the employees table. I used filters in SQL to create a query that identified all employees in the Marketing department for all offices in the East building.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/12T6bRK.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all columns from the employees table. Then it uses the WHERE clause with an AND operator to filter the results to output all of the employees in the Marketing department that work in offices in the East Building.</br></br>


<h2>Retrieve employees in Finance or Sales</h2>

My team needed to perform a different security update on machines for employees in the Sales and Finance departments. I used filters in SQL to create a query that identified all employees in the Sales or Finance departments.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/u0ZR5x9.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all columns from the employees table. Then it uses the WHERE clause with an OR operator to filter the results to output all of the employees in the Marketing department and the Finance department.</br></br>

<h2>Retrieve all employees not in IT</h2>

My team needed to make one more update to employee machines. The employees who were in the Information Technology department already had this update, but employees in all other departments needed it. I used filters in SQL to create a query which identified all employees not in the IT department.<br/><br/>

<p align="center">
<img src="https://i.imgur.com/9z5H27r.png" height="80%" width="80%" alt="Connection Attempt"/>
<br />
<br />
</p>

In the screenshot, you will see the SQL query I used and the output from that query. The query starts by selecting all columns from the employees table. Then it uses the WHERE clause with an NOT operator to filter the results to output all of the employees not in the IT department.</br></br>
<h2>Summary</h2>

In this excerise, I demonstrated the use of SQL used by a Cybersecurity Analyst. Several examples displayed how SQL queries can be used to return information on user logins and user computer names.
