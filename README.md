# Ex03 Time Table
## Date:09/04/2025

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
timetable.html
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - Karthic (212224040151)</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="200"WIDTH="1500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - Karthic (212224040151)</h3>

    <table border="1">
        <tr align="center" BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
	    <th>Saturday</th>
        </tr>
        <tr align="center" BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>ENG</td>
            <td>FREE SLOT</td>
            <td>CDS</td>
            <td>C PROG</td>
            <td>C PROG</td>
 	    <td></td>
        </tr>
        <tr align="center" BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>FWAD</td>
            <td>EVS</td>
            <td>FWAD</td>
            <td>EDM</td>
            <td>DE</td>
 	    <td></td>
        </tr>
        <tr align="center" BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr align="center" BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>EDM</td>
            <td>MATHS</td>
            <td>MENTOR</td>
            <td>ENG</td>
            <td>MATHS</td>
 	    <td></td>
        </tr>
        <tr align="center" BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>CHEM</td>
            <td>DE</td>
            <td>CHEM</td>
            <td>FREE SLOT</td>
 	    <td></td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19EN101</td>
            <td>Communicative English (ENG)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI304</td>
            <td>C Programming (C PROG)</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHEM)</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td>19MA222</td>
            <td>Probability and Queueing Models (MATHS)</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td>19EY708</td>
            <td>Career Skill Development (CDS)</td>
        </tr>
        <tr align="center">
            <td>7.</td>
            <td>19AI302</td>
            <td>Engineering Design (EDM)</td>
        </tr>
        <tr align="center">
            <td>8.</td>
            <td>19CY801</td>
            <td>Environmental Science and Sustainability (EVS)</td>
        </tr>
        <tr align="center">
            <td>9.</td>
            <td>19EE404</td>
            <td>Digital Electronics (DE)</td>
        </tr>
        <tr align="center">
            <td>10.</td>
            <td>ECA-M</td>
            <td>Mentor Meet (MENTOR)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (26).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
