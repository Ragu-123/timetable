# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
<head>
    <style>
        .container {
            width: 1000px; 
            margin: 0 auto; 
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #f2f2f2;
        }

        img {
            max-width: 100%; 
            height: auto; 
            display: block; 
            margin: 0 auto; 
        }
    </style>
</head>
<body>

<div class="container">
    <img src="logo_1.png" alt="Logo">
<table>
    <tr>
        <th colspan="9">Timetable</th>
    </tr>
    <tr>
        <th colspan="9">Register Number:212222240081</th>
    </tr>
    <tr>
        <th>Days</th>
        <th>1</th>
        <th>2</th>
        <th>3</th>
        <th>4</th>
        
    </tr>
    <tr>
        <td>Monday</td>
        <td>Fundamentals of Web</td>
        <td>English</td>
        <td>Digital Electronics</td>
        <td>Fundamentals of Web</td>
    </tr>
    <tr>
        <td>Tuesday</td>
        <td>Digital Electronics</td>
        <td>Statistics</td>
        <td>Communicative English</td>
        <td>Fundamentals of Web</td>
    </tr>
    <tr>
        <td>Wednesday</td>
        <td>Fundamentals of Web</td>
        <td>Communicative English</td>
        <td>Digital Electronics</td>
        <td>Statistics</td>
    </tr>
    <tr>
        <td>Thursday</td>
        <td>Digital Electronics</td>
        <td>Statistics</td>
        <td>Communicative English</td>
        <td>Fundamentals of Web</td>
    </tr>
    <tr>
        <td>Friday</td>
        <td>Fundamentals of Web</td>
        <td>Communicative English</td>
        <td>Digital Electronics</td>
        <td>Statistics</td>
    </tr>
    <tr>
        <td>Saturday</td>
        <td>Digital Electronics</td>
        <td>Statistics</td>
        <td>Communicative English</td>
        <td>Fundamentals of Web</td>
    </tr>
</table>

</body>
</html>
```

# OUPUT
![image](https://github.com/Ragu-123/timetable/assets/113915622/97808dd3-a200-4d38-87b6-13b78bee0a99)

