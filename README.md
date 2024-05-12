# Ex03 Time Table
## Date: 14.03.2024

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
```c
<html>
<head>
<title> TIME TABLE </title>   
</head>
<body>
<center>
<img src="/static/logo.png"height="100"width="540">
</center>
<br>
<table align="centre" border="6" bgcolor="Lavender" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE - Ragul E (212221043005) </caption>

<tr bgcolor="CornflowerBlue">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday </th>
</tr>
<tr align="center">
   <th bgcolor="CornflowerBlue"> 8-10 </th>
   <td> Fundamentals of Web Application Development</td>
   <td> Free Slot </td>
   <td> Problem Solving and Python Programming</td>
   <td> Free Slot </td>
   <td> Free Slot </td>
   <td> Free Slot </td>
</tr>
<tr align="center">
    <th bgcolor="CornflowerBlue"> 10-12 </th>
    <td> Free Slot</td>
    <td> Problem Solving and Python Programming </td>
    <td> Parallel Computing Arhitecture</td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Algebra and Number Theory </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 1-3 </th>
    <td > Algebra and Number Theory </td>
    <td> Intellectual Property Rights </td>
    <td>  Free Slot </td>
    <td> Fundamentals of Web Application Development </td>
    <td> Fundamentals of Web Application Development </td>
    <td> Advanced Quantitative and Logical Reasoning </td>
</tr>
<tr align ="center">
    <th bgcolor="CornflowerBlue"> 3-5 </th>
    <td> Free Slot </td>
    <td> Problem Solving and Python Programming </td>
    <td> Intellectual Property Rights</td>
    <td> Free Slot </td>
    <td> Free Slot </td>
    <td> Free Slot </td>
</tr>
</tr>
</table>
<br>
<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>
<tr align="center">
<td> 1. </td>
<td> 19CS301 </td>
<td> Problem Solving and Python Programming </td>
</tr>
<tr align="center">
<td> 2. </td>
<td> 19AI414 </td>
<td> Fundamentals of Web Application Development </td>
</tr>
<tr align="center">
<td> 3. </td>
<td> 19MA212 </td>
<td> Algebra and Number Theory </td>
</tr>
<tr align="center">
<td> 4. </td>
<td> 19AI407 </td>
<td> Parallel Computing Arhitecture </td>
</tr>
<tr align="center">
<td> 5. </td>
<td> 19ME531 </td>
<td> Intellectual Property Rights </td>
</tr>
<tr align="center">
<td> 6. </td>
<td> 19EY704 </td>
<td> Advanced Quantitative and Logical Reasoning  </td>
</tr>
</html>

```
## OUTPUT

![alt text](<Screenshot 2024-03-22 133704.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
