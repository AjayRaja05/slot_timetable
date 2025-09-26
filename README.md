# Ex03 Time Table
## Date: 26/09/2025-

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
<html>
<head>
<title>slot Timetable</title>    
</head>
<body bgcolor="white">
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="10" border="7" bgcolor="pink">
<caption><b>SLOT TIME TABLE -Ajayraja Rathinam (212224240006)</b></caption>
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
<td>FWAD</td>
<td>EDM</td>
<td>OS</td>
<td>MATHS FOR AI</td>
<td>FWAD</td>
<td>-</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>OS</td>
<td>INTRO TO ML</td>
<td>EDM</td>
<td>-</td>
<td>AI AND APPLICATIONS</td>
<td>-</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>MATHS FOR AI</td>
<td>MATHS FOR AI</td>
<td>MENTOR</td>
<td>QA</td>
<td>-</td>
<td>-</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>-</td>
<td>-</td>
<td>INTRO TO ML</td>
<td>AI AND APPLICATIONS</td>
<td>-</td>
<td>-</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="4" border="2" bgcolor="lightblue">
<tr align="center">
<th>s. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Appilication Development(WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19CS405</td>
<td>Operating system</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19MA220</td>
<td>Maths for AI</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center"> 19AI810</td>
<td>Artificial intelligence and its applications</th>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI302</td>
<td>Engineering design and modelling</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI410</td>
<td>Introduction to machine learning</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EY710</td>
<td>Quantitative ability<td>
</tr>
</table>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-09-26 090613.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
