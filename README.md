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
```python
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="https://i.ibb.co/hc30Wwc/WEB-LOGO-01.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - S SANTHOSH (212222100047)</b></caption>
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
<td>FWAD</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>JAPANESE</td>
<td>DBMS</td>
<td>FREE SLOT</td>
<td>CN</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>CN</td>
<td>FWAD</td>
<td>FREE SLOT</td>
<td>CHEMISTRY</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>DBMS</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>JAPANESE</td>
<td>CHEMISTRY</td>
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
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering(CHEMISTRY)</td>
</tr>

<tr>
<td align="center">3.</td>
<td align="center">19CS404</td>
<td>Database Management System and its Applications (DBMS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS406</td>
<td>Computer Networks (CN)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EN615</td>
<td>JAPANESE(Japanese)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![output](timetable.png)
