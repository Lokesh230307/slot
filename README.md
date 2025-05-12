# Ex03 Time Table
## Date:07.05.2025

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
<html>
<head>
    <title>Time Table</title>
    <style>
        body {
            background-color: #FFFDE7;
            font-family: Arial, sans-serif;
        }
        table {
            border-collapse: collapse;
            margin-bottom: 30px;
        }
        table, th, td {
            border: 2px solid #444;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #00BFFF;
            color: white;
        }
        td {
            background-color: #FAFAD2;
        }
        td[rowspan] {
            background-color: #98FB98;
            font-weight: bold;
        }
        h1 {
            color: #333366;
        }
        .subject-table th {
            background-color: #F08080;
            color: white;
        }
        .subject-table td {
            background-color: #FFFACD;
        }
    </style>
</head>
<body>
<center>
    <img src="/static/logo.png" height="100" width="540" alt="Logo">
</center>

<center>
    <h1>Weekly Time Table: Lokesh S (24900098)</h1>
</center>

<center>
    <table>
        <thead>
            <tr>
                <th>Day</th>
                <th>8:00 - 10:00</th>
                <th>10:00 - 12:00</th>
                <th>12:00 - 1:00</th>
                <th>1:00 - 3:00</th>
                <th>3:00 - 5:00</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Monday</td>
                <td>Fundamentals of C Programming</td>
                <td>Physics for Quantum Computing</td>
                <td rowspan="5">Lunch</td>
                <td>Fundamentals of Web Development</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td>Free slot</td>
                <td>Digital Electronics</td>
                <td>EMPD</td>
                <td>Principles of Chemistry</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>Fundamentals of Web Development</td>
                <td>Communicative English</td>
                <td>Mentor Meeting</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td>Python Programming</td>
                <td>Physics for Quantum Computing</td>
                <td>EMPD</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td>Principles of Chemistry</td>
                <td>Free slot</td>
                <td>Communicative English</td>
                <td>Free slot</td>
            </tr>
        </tbody>
    </table>
</center>

<center>
    <table class="subject-table">
        <thead>
            <tr>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>19PH814</td><td>Physics for Quantum Computing</td></tr>
            <tr><td>19EE102</td><td>Digital Electronics</td></tr>
            <tr><td>19AI414</td><td>Fundamentals of Web Development</td></tr>
            <tr><td>19CY119</td><td>Principles of Chemistry</td></tr>
            <tr><td>19EN101</td><td>Communicative English</td></tr>
            <tr><td>19AL130</td><td>Python Programming</td></tr>
            <tr><td>19AI303</td><td>EMPD</td></tr>
            <tr><td>19AI304</td><td>Fundamentals of C Programming</td></tr>
        </tbody>
    </table>
</center>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-05-07 200610.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
