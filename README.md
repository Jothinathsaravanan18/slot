# Ex02 Time Table
## Date:21.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>  
    </head>
<body>
    <center>
        <img src="logo.png" width="800" height="150"><br>
        <h3><font color="black">SLOT TIME TABLE - JOTHINATH S (26012661)</font></h3>
    </center>
    <center>
    <table width="30%" height="200" border="3" cellpadding="5" cellspacing="3" bgcolor="white">
    <tr bgcolor="royalblue">
        <th><font color="White">Day/Time</font></th>
        <th><font color="white">Monday</font></th>
        <th><font color="white">Tuesday</font></th>
        <th><font color="white">Wednesday</font></th>
        <th><font color="white">Thrusday</font></th>
        <th><font color="white">Friday</font></th>
        <th><font color="white">Saturday</font></th>
    </tr>
    <tr>
        <td align="center" bgcolor="pink">8-10</td>
        <td>FCC</td>
        <td>MATH</td>
        <td>PY</td>
        <td>PY</td>
        <td>DE</td>
        <td>PS</td>
    </tr>
        <td align="center" bgcolor="pink">10-12</td>
        <td>PY</td>
        <td>MATH</td>
        <td>FREE SLOT</td>
        <td>FCC</td>
        <td>FREE SLOT</td>
        <td >FWA</td>
    </tr>
    <tr bgcolor="lightyellow">
        <td align="center" bgcolor="pink">12-1</td>
        <td align="center" colspan="6">LUNCH BREAK</td>
    </tr>
    <tr>
        <td align="center" bgcolor="pink">1-3</td>
        <td>FREE SLOT</td>
        <td>DE</td>
        <td>FWA</td>
        <td>PS</td>
        <td>PY</td>
        <td>FCC</td>
    </table>
    </center>

    <br>

<center>
    <table border = "3" cellpadding = "5" cellspacing = "5">

            <tr>
                <th bgcolor ="lime">S.No</th>
                <th bgcolor ="lime">Subject Code</th>
                <th bgcolor ="lime">Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19CS414</td>
                <td>Foundation of Cryptocurrency</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19SE415</td>
                <td>Calculus mathematics</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI416</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19AI417</td>
                <td>Fundamentals of Web Applications</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19SE418</td>
                <td>Public Speaking</td>
            </tr>           
    
        </table>
    </center>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (23).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
