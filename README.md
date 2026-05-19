# Ex02 Time Table
## Date:19-05-2026

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
    <body>
        <center>
        <img src="c:\Users\acer\Downloads\logo.jpeg"height" height="200" width="800">
        </center>
        <br>
        <table align="center" width="800" cellspacing="2" cellpadding="4" border="6" bgcolor="CYAN">
            <caption><b>SLOT TIME TABLE: VINODHARANI V </b></caption>
            <tr align="center">
                <th bgcolor="MAGENTA">Time/Day</th>
                <th bgcolor="MAGENTA">Monday</th>
                <th bgcolor="MAGENTA">Tuesday</th>
                <th bgcolor="MAGENTA">Wednesday</th>
                <th bgcolor="MAGENTA">Thursday</th>
                <th bgcolor="MAGENTA">Friday</th>
                <th bgcolor="MAGENTA">Saturday</th>
            </tr>
            <tr align="center">
                <td bgcolor="MAGENTA">8-10</td>
                <td>PYTHON</td>
                <td>CARRER DEVELOPMENT SKILLS</td>
                <td>PYTHON</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="MAGENTA">10-12</td>
                <td>FREE SLOT</td>
                <td>Web</td>
                <td>Web</td>
                <td>PYTHON</td>
                <td>web</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="MAGENTA">12-1</td>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>
            <tr align="center">
                <td bgcolor="MAGENTA">1-3</td>
                <td>FREE SLOT</td>
                <td>Web</td>
                <td>Mentor Meet</td>
                <td>PYTHON</td>
                <td>CARRER DEVELOPMENT SKILLS</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <td bgcolor="MAGENTA">3-5</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            </table>
            <br>
            <table align="center" cellspacing="2" cellpadding="4" border="6">
            <tr align="center">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td align="center">Fundamentals of web application development</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI301</td>
                <td align="center">PYTHON PROGRAMMING</td>
            </tr>
             <tr>
                <td align="center">3.</td>
                <td align="center">19EY708</td>
                <td align="center">CARRER DEVELOPMENT SKILLS</td>
            </tr>
            
            <tr>
                <td align="center">4.</td>
                <td align="center">ECA-M</td>
                <td align="center">Mentor Meet</td>
            </tr>
            </table>
        </body>
    </html>

## OUTPUT
c:\Users\rahul\Pictures\Screenshots\Screenshot 2026-05-19 160211.png


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
