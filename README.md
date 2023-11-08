# Ex03 Time Table
## Date:31.10.2023

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
<title> Time Table </title>
</head>

<body>

<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="800" cellspacing="3" cellpadding="14" border="2" bgcolor="blue">
<caption> <b> SLOT TIME TABLE - SHANMUGA VASANTH M (23008968) </b> </caption>

<tr align="center">
<th bgcolor="Charcoal"> Day / Time </th>
<th bgcolor="Charcoal"> 8 - 10 </th>
<th bgcolor="Charcoal"> 10 - 12 </th>
<th bgcolor="Charcoal"> 12 - 1 </th>
<th bgcolor="Charcoal"> 1 - 3 </th>
<th bgcolor="Charcoal"> 3 - 5 </th>
</th>

<tr align="center">
<th bgcolor="Charcoal"> Monday </th>
<td colspan="2" align="center" bgcolor="Lavender"> Free Slot </td>
<td rowspan="5" bgcolor="Lavender"> Lunch </td>
<td bgcolor="Lavender"> Principle's of Chemistry in Engineering </td>
<td bgcolor="Lavender"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="Charcoal"> Tuesday </th>
<td bgcolor="Lavender"> Free Slot </td>
<td bgcolor="Lavender"> Calculus and Matrix Algebra </td>
<td bgcolor="Lavender"> Communicative English </td>
<td bgcolor="Lavender"> Soft Skill </td>
</tr>

<tr align="center">
<th bgcolor="Charcoal"> Wednesday </th>
<td bgcolor="Lavender"> Fundamentals of Web Application Development </td>
<td bgcolor="Lavender"> Computer Architecture </td>
<td bgcolor="Lavender"> Principle's of Chemistry in Engineering </td>
<td bgcolor="Lavender"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="Charcoal"> Thursday </th>
<td bgcolor="Lavender"> Calculus and Matrix Algebra </td>
<td bgcolor="Lavender"> Fundamentals of Web Application Development </td>
<td bgcolor="Lavender"> Communicative English </td>
<td bgcolor="Lavender"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="Charcoal"> Friday </th>
<td bgcolor="Lavender"> Free Slot </td>
<td bgcolor="Lavender"> Computer Architecture </td>
<td bgcolor="Lavender"> Fundamentals of Web Application Development </td>
<td bgcolor="Lavender"> Free Slot </td>
</tr>
</table>
<br>
<br>

<table align="center" cellspacing="3" cellpadding="15" border="2" bgcolor="blue">

<tr align="center">
<th bgcolor="Charcoal"> S.No. </th>
<th bgcolor="Charcoal"> Subject Code </th>
<th bgcolor="Charcoal"> Subject Name </th>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 1. </th>
<td align="center" bgcolor="Lavender"> 19AI414 </td>
<td bgcolor="Lavender"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 2. </th>
<td align="center" bgcolor="Lavender"> 19CS305 </td>
<td bgcolor="Lavender"> Computer Architecture </td>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 3. </th>
<td align="center" bgcolor="Lavender"> 19CY205 </td>
<td bgcolor="Lavender"> Principle's of Chemistry in Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 4. </th>
<td align="center" bgcolor="Lavender"> 19MA201 </td>
<td bgcolor="Lavender"> Calculus and Matrix Algebra </td>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 5. </th>
<td align="center" bgcolor="Lavender"> 19EN101 </td>
<td bgcolor="Lavender"> Communicative English </td>
</tr>

<tr>
<th align="center" bgcolor="Lavender"> 6. </th>
<td align="center" bgcolor="Lavender"> 19EY701 </td>
<td bgcolor="Lavender"> Soft Skill </td>
</tr>

</body>
</html>
```

## OUTPUT

![Alt text](<Screenshot 2023-11-08 090749.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
