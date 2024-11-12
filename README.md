# Ex03 Time Table
## Date:12/11/2024

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
    <body>
        <img src="logo.png">
        <table border="5" bgcolor="red" cellspacing="10" cellpadding="10">
            <caption><B>SLOT TIME TABLE - ENBANATHAN V (24001750)</B></caption>
            <tr>
                <th bgcolor="blue">Day/Time</th>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="blue">Thurday</th>
                <th bgcolor="blue">Friday</th>
                <th bgcolor="blue">Saturday</th>
            </tr>
            <tr>
                <th bgcolor="blue">8-10</th>
                <td>Free slot</td>
                <td>CD</td>
                <td>Free Slot</td>
                <td>Phy Of QC</td>
                <td>Fun Of WA</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <th bgcolor="blue">10-12</th>
                <td>DE</td>
                <td>MAT</td>
                <td>C program</td>
                <td>BEEE</td>
                <td>C program</td>
                <td>Phy Of QC</td>
            </tr>
            <tr>
                <th bgcolor="blue">12-01</th>
                <th colspan="6" >LUNCH BREAK </th>
            </tr>
            <tr>
                <th bgcolor="blue">01-03</th>
                <td colspan="2">Fun Of WA</td>
                <td>MM</td>
                <td>DE</td>
                <td>BEEE</td>
                <td>MAT</td>
            </tr>
        </table>
        <br>
        <table border="5" cellpadding="5">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
            <td>1.</td>
            <td>19AI304</td>
            <td>Fundamental of C Programming</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamental of Web Application</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EE305</td>
                <td>Basic Electrical,Electronics and Measurement Engineering</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
    <td>5.</td>
   <td>19EY708</td>
    <td>Career Development Skills</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19MA201</td>
                <td>Calculas and matrix Algebre</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>

            </tr>
            <tr>
                <td>8.</td>
                <td>SH3214</td>
                <td>Physics of quantum Computing</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (48).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
