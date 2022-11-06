<h1>SQL Injections</h1>
An overview of different types of SQL injecitons 

<br />
<br />

<h2>Retrieving Hidden Data</h2>

- <b>-- : A comment indicator in SQL and means rest of query interpreted as comment<b>
- <b>Add '-- to the end of a url to display all items within the category
- <b>'+OR+-- : returns all items since 1=1 is always true

<h2>Subverting Application Logic</h2>

- <b>Adding '-- to the end of a username will cause the password to be disregarded
-<b>The query will then return the account of the username and logs the attacker in as them<b>

<h2>Retrieving Data from other Database Tables

- <b>UNION : Keyword in SQL which lets you execute an additionall SELECT query and appends results to original<b>
- <b>
