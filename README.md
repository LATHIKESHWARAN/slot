# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - LATHIKESHWARAN J (22008895)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>TRANS&APP</td>
<td>FREE SLOT</td>
<td>PHY</td>
<td>SNM</td>
<td>CP</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FREE SLOT</td>
<td> FWAD </td>
<td>CHE</td>
<td>TRANS&APP</td>
<td>SNM</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>CP</td>
<td>FREE SLOT</td>
<td>CODE PRACT</td>
<td>FWAD</td>
<td>CODE PRACT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>SNM</td>
<td>SS</td>
<td>FWAD</td>
<td>PHY</td>
<td>CHE</td>
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
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF PROGRAMMING IN C (CP)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH216</td>
<td>Physics for quantum computing (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA219</td>
<td>Transforms and its application (TRANS&APP)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills (SS)</td>
<tr>
<td align="center">7.</td>
<td align="center">19MA211</td>
<td>Statistics and numerical methods (SNM)</td>
</tr>
</table>
</body>
</html>
```
# OUTPUT
![OUTPUT](http://lathikeshwaran.student.saveetha.in:8000/static/images/out.png?raw=true)

# HTML VALIDATOR
![HTML VALIDATOR](http://lathikeshwaran.student.saveetha.in:8000/static/images/valid.png?raw=true)

# RESULT
The program for creating slot timetable is completed successfully