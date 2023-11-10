# Ex03 Time Table
## Date:11.11.2023

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        table {
	    border-style:solid;
            width: 50%;
            border-collapse: separate;
            margin-top: 0px;
	    margin-left: 20px;
 	    margin-bottom: 20px;
	    margin-right: 20px;
	    Background-color:cyan;
        }

        th,td {
            border: 1px solid black;
            text-align: center;
        }

        th {
            background-color: yellow;
        }
	td {
	    
	    background-color: cyan;
	    margin:20px;
	    padding: 1px;
	    
        }
    </style>
</head>
<body>
<center>
	<img src="/static/logo.png" alt="saveetha logo" width="30%" height="50%">
    <h4 align="center">SLOT TIMETABLE-EZHIL SREE J(23012968)</h4>


    <table  align="center">
        <tr>
            <th >Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <td style="background-color:yellow">8-10</td>
            <td>ENGINEERING DESIGN AND MODELLING</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT</td>
            <td>PYTHON AND LINEAR ALGEBRA</td>
        </tr>
        <tr>
            <td style="background-color:yellow">10-12</td>
            <td>CHEMISTRY</td>
            <td>PYTHON AND LINEAR ALGEBRA</td>
            <td>ENGINEERING DESIGN AND MODELLING</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color:yellow">12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr>
            <td style="background-color:yellow">1-3</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
            <td style="background-color:yellow">3-5</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>PYTHON AND LINEAR ALGEBRA</td>
            <td>PYTHON AND LINEAR ALGEBRA</td>
            <td>CHEMISTRY</td>
        </tr> 
    </table>
    <table  style="background-color:transparent">
        <tr>
            <th style="background-color:transparent">S.NO</th>
            <th style="background-color:transparent">Subject Code</th>
            <th style="background-color:transparent ">Subject Name</th>
        </tr>
        <tr>
            <td style="background-color:transparent">1</td>
            <td style="background-color:transparent">19AI301C</td>
            <td style="background-color:transparent;text-align:left">PYTHON AND LINEAR ALGEBRA</td>
        </tr>   
        <tr>
            <td style="background-color:transparent">2</td>
            <td style="background-color:transparent">19AI302</td>
            <td style="background-color:transparent;text-align:left">ENGINEERING DESIGN AND MODELLING</td>
        </tr>
        <tr>
            <td style="background-color:transparent">3</td>
            <td style="background-color:transparent">19AI414</td>
            <td style="background-color:transparent;text-align:left">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
        <tr>
            <td style="background-color:transparent">4</td>
            <td style="background-color:transparent">19CY205</td>
            <td style="background-color:transparent;text-align:left">CHEMISTRY</td>
        </tr>
        <tr>
            <td style="background-color:transparent">5</td>
            <td style="background-color:transparent">19EN101</td>
            <td style="background-color:transparent;text-align:left">COMMUNICATIVE ENGLISH</td>
        </tr>

    </table>
</center>
</body>
</html>
```

## OUTPUT
![OUTPUT]](OUTPUT.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
