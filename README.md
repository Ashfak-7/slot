# Ex03 Time Table
## Date:22/09/2025

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
        <title>TimeTable</title>
    </head>
    <body>
        <img src="logo.png" height="100" width="590">
        <h2>SLOT TIMETABLE-ASHFAK N(25003270)</h2>
        <table border="3" cellspacing="3" cellpadding="8" width="550">
            <tr bgcolor="lightgreen">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">8-10</th>
                <td>C</td>
                <td>C</td>
                <td>WEB</td>
                <td>FREE</td>
                <td>DS</td>
                <td>WEB</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">10-12</th>
                <td>FREE</td>
                <td>DS</td>
                <td>WEB</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>C</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">1-3</th>
                <td>DS</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>WEB</td>
                <td>WEb</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">3-5</th>
                <td>FREE</td>
                <td>C</td>
                <td>DS</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>C</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="3" cellpadding="3" width="585">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI403</td>
                <td>Introduction to Data Science</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
        </table>
    </body>
</html>

```
## output

![alt text](<Screenshot (6).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
