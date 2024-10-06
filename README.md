# Ex03 Time Table
## Date:

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
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: lightblue;
            border-color: black;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: black;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: plum;
        }
        .c1{
            background-color: plum;
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - SATHYAA R (212223100052)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th class="c1">Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td class="c1">8-10</td>
            <th>FREE SLOT</th>
            <td>OS</td>
            <td>CN</td>
            <td>ML</td>
            <td>FWAD</td>
            <td>OS</td>
        </tr>
        <tr>
            <td class="c1">10-12</td>
            <td>ML</td>
            <th>FREE SLOT</th>
            <td>FWAD</td>
            <td>DS</td>
            <td>CN</td>
            <td>CD</td>
            
        </tr>
        <tr>
            <td class="c1">12-1</td>
            <th colspan="6">L U N C H</th>
        </tr>
        <tr>
            <td class="c1">1-3</td>
            <td>DS</td>
            <td>CD</td>
            <th colspan="2">FREE SLOT</th>
            <td>RA</td>
            <td>FREE SLOT</td>
            
        </tr>
        <tr>
            <td class="c1">3-5</td>
            <th>FREE SLOT</th>
            <td>FWAD</td>
            <td>SNM</td>
            <th colspan="2">FREE SLOT</th>
            <td>SNM</td>
        </tr>
    </table>
    <br>
    <br>
    <table border="1" class="table2">
        <tr>
            <th>S.No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Applications Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19AI410</td>
            <td>Introduction to Machine Learning (ML)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI408</td>
            <td>Data Structures (DS)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19CS406</td>
            <td>Computer Networks (CN)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19CS409</td>
            <td>Compiler Design (CD)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods (SNM)</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EY709</td>
            <td>Reasoning Ability (RA)</td>
        </tr>
    </table>
</body>
</html>

```


## OUTPUT

![Screenshot 2024-10-06 202704](https://github.com/user-attachments/assets/2e3f324c-5dc4-49e5-a46e-1a2a3dcb9f1e)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
