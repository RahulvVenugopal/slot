# Ex03 Time Table
## Date:08.11.2023

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
<title>slot timetable</title>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
 <table border="7" cellspacing="4"cellpadding="15"bgcolor="lightblue">
<caption><h2>SLOT TIMETABLE Rahul V (23012304)</h2></caption>
<tr>
<th bgcolor="red">Day/Time</th>
<th bgcolor="green">8-10</th>
<th bgcolor="green">10-12</th>
<th bgcolor="green">12-1</th>
<th bgcolor="green">1-3</th>
<th bgcolor="green">3-5</th>
</tr>
<tr>
<th bgcolor="pink">MON</th>
<td>C</td>
<td>C ENGLISH</td>
<td>BREAK</td>
<td>FREE SLOT</td>
<td>PHYSICS</td>
</tr>
<tr>
<th bgcolor="pink">TUE</th>
<td>PYTHON</td>
<td>C</td>
<td>BREAK</td>
<td>FREE SLOT</td>
<td>SOFT SKILLS</td>
</tr>
</tr>
<th bgcolor="pink">WED</th>
<td>FWAD  </td>
<td>FREE SLOT   </td>
<td>BREAK</td>
<td>FREE SLOT   </td>
<td>PYTHON  </td>

</tr>
<th bgcolor="pink">THURS</th>
<td> FREE SLOT  </td>
<td>FWAD   </td>
<td>BREAK</td>
<td>C ENGLISH</td>
<td>MATHS</td>
</tr>
</tr>
<th bgcolor="pink">FRI</th>
<td>MATHS</td>
<td>PHYSICS</td>
<td>BREAK</td>
<td>FWAD</td>
<td>FREE SLOT   </td>
</tr>

<table border="7" cellspacing="2"cellpadding="15">
<tr>
<th>S.NO</th>.
<th>COURSE CODE</th>
<th>COURSE NAME</th>
</tr>
<tr>
<th>1.</th>.
<th>19AI304</th>
<th>Fundamentals of C Programming</th>
</tr>


<tr>
<th>2.</th>
<th>19AI414</th>
<th>Fundamentals of Web Applications(FWAD)</th>
</tr>


<tr>
<th>3.</th>
<th>19PH214</th>
<th>Physics for Quantum Computing</th>
</tr>


<tr>
<th>4.</th>
<th>19AI301</th>
<th>Python Programming</th>
</tr>


<tr>
<th>5.</th>
<th>19EY701</th>
<th>Soft Skills</th>
</tr>


<tr>
<th>6.</th>
<th>19MA201</th>
<th>Calculus and Matrix Algebra</th>
</tr>

<tr>
<th>7.</th>
<th>19EN101</th>
<th>Communicative English</th>
</tr>
</center>
</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (20).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
