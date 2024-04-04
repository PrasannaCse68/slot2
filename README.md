# slot2

# Ex03 Time Table
## Date:04-04-2024

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
<html>
<body>
<center><img src="/static/logo.png" height="100" width="540">
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
<caption><b>SLOT TIME TABLE - PRASANNA G.R (212221040129)</b></caption>
<tr align="center">
    <th bgcolor="orange">Day/Time</th>
    <th bgcolor="orange">Monday</th>
    <th bgcolor="orange">Tuesday</th>
    <th bgcolor="orange">Wednesday</th>
    <th bgcolor="orange">Thursday</th>
    <th bgcolor="orange">Friday</th>
    <th bgcolor="orange">Saturday</th>
</tr>

<tr align="center">
<th bgcolor="orange">8-10</th>
<td>BEE</td>
<td>C</td>
<td>Web</td>
<td>free</td>
<td>free</td>
<td>free</td>
</tr>

<tr align="center">
<th bgcolor="orange">10-12</th>
<td>Robotics</td>
<td>Web</td>
<td>Phy</td>
<td>C</td>
<td>AI</td>
<td>free</td>
</tr>

<tr>
<th bgcolor="orange">12-1</th>
<td colspan="6">Lunch</td>

</tr>

<tr>
<th bgcolor="orange">1-3</th>
<td>Web</td>
<td>AI</td>
<td>HRM</td>
<td>Software</td>
<td>HRM</td>
<td>BEE</td>

</tr>

<tr>
<th bgcolor="orange">3-5</th>
<td>Software</td>
<td>Phy</td>
<td>free</td>
<td>CS</td>
<td>Robotics</td>
<td>free</td>
</tr>


<tr>

</tr>

</table>
<br>
<table border="4" align="center">

<tr>
<th>S.no</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td>1</td>
<td>19AI305</td>
<td>Advanced C Programming</td>
</tr>

<tr>
<td>2</td>
<td> 19EE305</td>
<td>Basic Electrical, Electronics and Measurement Engineering</td>
</tr>

<tr>
<td>3</td>
<td>19AI414 </td>
<td>Fundamentals of Web Application Development</td>
</tr>

<tr>
<td>4</td>
<td>19AI533</td>
<td>Introduction to Robotics</td>
</tr>


<tr>
<td>5</td>
<td>19CS408</td>
<td>Software Engineering</td>
</tr>

<tr>
<td>6</td>
<td>19PH214</td>
<td>Physics for Quantum Computing</td>
</tr>
 
<tr>
<td>7</td>
<td>19MS156</td>
<td>Human Resource Management and Team Building</td>
</tr>

<tr>
<td>8</td>
<td>19AI405</td>
<td>Fundamentals of Artificial Intelligence</td>
</tr>

<tr>
<td>9</td>
<td>19EY702 </td>
<td>Creative Skills for Communication</td>
</tr>

</table>
</body>
</html>
```

## OUTPUT

![Screenshot 2024-04-04 103330](https://github.com/PrasannaCse68/slot2/assets/127935950/f7534bdc-b284-4815-9261-1fe6b5f4be6c)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
