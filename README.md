# Ex03 Time Table
## Date:18.03.2024

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
<html lang="en">
<head>
    <title>Timetable</title>
</head>
<body bgcolor="cyan">
    <img align="center" src="/static/logo.png" height="200" width="1000">
    <table border="3" cellspacing="4" cellpadding  align="center" bgcolor="beige" height="300" width="500">
        <tr>
        <th>Day/Time</th>
        <th>8 - 10</th>
        <th>10 - 12</th>
        <th>1 - 3</th>
        <th>3 - 5</th>
        </tr>

        <tr>
            <th>Mon</th>
            <th>-</th>
            <th>-</th>
            <th>FWAD</th>
            <th>Adv C</th>
        </tr>

        <tr>
            <th>Tue</th>
            <th>P&LA</th>
            <th>FWAD</th>
            <th>OS</th>
            <th>-</th>
        </tr>

        <tr>
            <th>Wed</th>
            <th>FWAD</th>
            <th>P&LA</th>
            <th>EMPD</th>
            <th>Adv C</th>
        </tr>

        <tr>
            <th>Thu</th>
            <th>OS</th>
            <th>-</th>
            <th>P&LA</th>
            <th>-</th>
        </tr>

        <tr>
            <th>Fri</th>
            <th>P&LA</th>
            <th>EMPD</th>
            <th>Soft Skill</th>
            <th>-</th>
        </tr>

        <tr>
            <th>Sat</th>
            <th>-</th>
            <th>-</th>
            <th>-</th>
            <th>-</th>
        </tr>
        
    </table>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-03-18 114833.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
