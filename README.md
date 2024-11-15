# Ex04 Time Table
## Date: 01/11/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - Kishore A (212222040078)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>SNLT</td>
<td>CNS</td>
<td>FWAD</td>
<td>CE</td>
<td>CE</td>
<td rowspan="2">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>MERN</td>
<td>VCC</td>
<td>MERN</td>
<td>FREE SLOT</td>
<td>MERN</td>

</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FREE SLOT</td>
<td>MERN</td>
<td>MENTOR MEET</td>
<td>MERN</td>
<td>DBMS</td>
<td rowspan="2">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2">FREE SLOT</td>


<td>DBMS</td>
<td>FWAD</td>
<td>CNS</td>

</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EY710</td>
<td>QUANTITATIVE ABILITY 1(SNLT)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI512C</td>
<td>MERN FULL STACK(MERN))</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EC307</td>
<td>COMMUNICATION ENGINEERING (CE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CS411</td>
<td>VIRTUALIZATION AND CLOUD COMPUTING (VCC)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS412</td>
<td>CRYPTOGRAPHY AND NETWORK SECURITY(CNS)</td>
</tr>
<td align="center">6.</td>
<td align="center">19CS404</td>
<td>DATABASE MANAGEMENT SYSTEM(DBMS) </td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-15 231302.png>)

![alt text](<Screenshot 2024-11-15 231158.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
