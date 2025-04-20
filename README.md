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

Name : Rohit GP
Reg No : 212224220082

```
<!DOCTYPE html>
<head>
    <style>
       body {
        text-align: center;
        /* background: linear-gradient(to left, white, rgb(227, 222, 82)); */
        background-color: rgb(227, 222, 82);
       }
        h1 {
            text-align: center;
            padding: 15px;
        }
        td, th {
            text-align: center;
            padding: 20px 30px;
            /* border-radius: 10px; */
        }
        td {
            background-color: white;
            font-size: large;
        }
        #mentor {
            background-color: rgb(126, 220, 86);
        }
        th {
            background-color: rgb(125, 184, 235);
            font-size: larger;
        }
        table {
            border: solid;
            margin-left: auto;
            margin-right: auto;
            border-radius: 20px;
            overflow: hidden;
        }
    </style>
</head
<body>
    <img src="/static/logo.png" width="45%">
    <h1>PRIME TIMETABLE - MAR</h1>
    <table>
        <tr>
            <th>Time/Days</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr>
            <th>8 - 10</th>
            <td>Web Development</td>
            <td>Task Completion</td>
            <td>Assessment Hour</td>
            <td>Module Completion</td>
            <td>Task Comletion</td>
        </tr>
        <tr>
            <th>10 - 12</th>
            <td>Task Assignment</td>
            <td>Web Development</td>
            <td>Task Presentation</td>
            <td>Fundamentals of AI</td>
            <td>Web Development</td>
        </tr>
        <tr>
            <th>1 - 3</th>
            <td>Fundamentals of AI</td>
            <td>Module Completion</td>
            <td id="mentor">Mentors Meet</td>
            <td>Task Presentation</td>
            <td>Task Completion</td>
        </tr>
    </table>
</body> 
</html>
```

## OUTPUT

![Output](<Screenshot 2025-04-02 111912.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
