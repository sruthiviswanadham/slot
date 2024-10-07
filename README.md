# Ex03 Time Table
## Date: 07-10-2024

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
<html>
   <title> TIME TABLE </title>
   <body>
   <center>
   <img src="/static/logo.png"height="100"width="540">

<br>
<table border="6" bgcolor="cyan" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE - VISWANADHAM VENKATA SAI SRUTHI(212223100061)</caption>
<br>

<tr bgcolor="blue">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
     <th> Saturday</th>
</tr>

<tr align="center">
   <th bgcolor="red"> 8-10 </th>s
   <td> FREE SLOT</td>
   <td> INTRODUCTION TO MACHINE LEARNING </td>
   <td> ADVANCED C PROGRAMMING</td>
   <td> FREE SLOT </td>
   <td> ADVANCED C PROGRAMMING</td>
   <td>FWAD</td>
</tr>

<tr align="center">
    <th bgcolor="red"> 10-12 </th>
    <td> THEORY OF COMPUTATION</td>
    <td> DIGITAL IMAGE PROCESSING TECHNIQUES </td>
    <td> INTRODUCTION TO MACHINE LEARNING</td>
    <td> FWAD</td>
    <td> SOFTWARE ENGINEERING</td>
    <td> FREE SLOT</td>
</tr>

<tr align ="center">
    <th bgcolor="red"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH </td>
</tr>

<tr align ="center">
    <th bgcolor="red"> 1-3 </th>
    <td>  FREE SLOT </td>
    <td>  FREE SLOT </td>
    <td>  MENTOR MEETING</td>
    <td>  SOFTWARE ENGINEERING</td>
    <td>  FREE SLOT</td>
    <td>  THEORY OF COMPUTATION</td>
</tr>

<tr align ="center">
    <th bgcolor="red"> 3-5 </th>
    
    <td>  FWAD</td>
    <td> OPERATING SYSTEM</td>
    <td> DIGITAL IMAGE PROCESSING TECHNIQUES </td>
    <td> QUANTITATIVE ABILITY </td>
    <td> FREE SLOT</td>
    <td> OPERATING SYSTEM </td>
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
<td> 19AI414 </td>
<td> Fundamentals of Web Applicaton Development(FWAD) </td>
</tr>

<tr align="center">
<td> 2. </td>
<td> 19AI410 </td>
<td> Introduction To Machine Learning </td>
</tr>

<tr align="center">
<td> 3. </td>
<td> 19CS405</td>
<td> Operating System</td>
</tr>

<tr align="center">
<td> 4. </td>
<td> 19CS407 </td>
<td> Theory Of Computation  </td>
</tr>

<tr align="center">
<td> 5. </td>
<td> 19AI406</td>
<td> Digital Image Processing Techniques </td>
</tr>

<tr align="center">
<td> 6. </td>
<td> 19CS408 </td>
<td> Software Engineering</td>
</tr>

<tr align="center">
<td> 7.</td>
<td> 19AI305</td>
<td> Advanced C Programming</td>
</tr>

<tr align="center">
<td> 8.</td>
<td> 19EY710</td>
<td> Quantitative Ability</td>
</tr>
</html>



## OUTPUT
![image](https://github.com/user-attachments/assets/709eec2f-8b2b-42ae-bcab-ac63ce0d94a8)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
