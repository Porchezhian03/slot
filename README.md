# Ex03 Time Table
## Date:13/3/2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
    <title>Semester Timetable</title>
    <img src="saveetha.jpg" style="height: 2%; width: 50%;">
</center>
    <style>
        body {
        table {
            width: 60%;
            margin: 10px auto;
            border-collapse: collapse;
            background: lavender;
        }
        th, td {
            border: 1px solid #000;
            padding: 10px;
            text-align: center;
        }
        th {
            background: plum;
        }
        .free-slot {
            background: lavender;
        }
    }
    </style>
</head>
<body>
    <center>
    <h1>Semester Timetable</h1>
</center>
    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>GER</td>
            <td Class="free-slot">FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td Class="free-slot">FREE SLOT</td>
            <td Class="free-slot">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td class="free-slot">FREE SLOT</td>
            <td Class="free-slot">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development(FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN612</td>
            <td>GERMAN BASICS</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH206</td>
            <td>Physics for Information Technology(PHY)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CY205</td>
            <td>Principle of Chemistry in Engineering(CHE)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra(MAT)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY701</td>
            <td>Soft Skills</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![Screenshot 2025-04-02 211930](https://github.com/user-attachments/assets/e67eca75-d0c0-4ce0-a53c-8ba299fcec7a)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
