# Ex03 Time Table
# Date:15.10.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Table</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            font-size: 18px;
        }
        th, td {
            border: 2px solid black;
            padding: 15px;
            text-align: center;
        }
        h1 {
            font-size: 24px;
        }
        h2 {
            font-size: 22px;
        }
        img {
            height: 150px;
            width: 100vw;
        }
       
        .monday {
            background-color: lightgray;
        }
        .tuesday {
            background-color: lightgreen;
        }
        .wednesday {
            background-color: lightyellow;
        }
        .thursday {
            background-color: lightblue;
        }
        .friday {
            background-color: pink;
        }
        .saturday {
            background-color: lightsalmon;
        }
        .holiday {
            background-color: lightgoldenrodyellow;
        }
    </style>
</head>
<body>
    <img src="logo.png" alt="logo">
    
    <h1><b>Reference No: 24000656<br>Time Table</b></h1>
    
    <table>
        <tr>
            <th>Day</th>
            <th>Period 1</th>
            <th>Period 2</th>
            <th rowspan="7">Lunch</th>
            <th>Period 3</th>
            <th>Period 4</th>
        </tr>
        <tr class="monday">
            <th>Monday</th>
            <td>Free</td>
            <td>BEEE</td>
            <td>Web Application</td>
            <td>Free</td>
        </tr>
        <tr class="tuesday">
            <th>Tuesday</th>
            <td>Communicative English</td>
            <td>BEEE</td>
            <td>Web Application</td>
            <td>Digital Electronics</td>
        </tr>
        <tr class="wednesday">
            <th>Wednesday</th>
            <td>Free</td>
            <td>IOT</td>
            <td>Mentor Meet</td>
            <td>Free</td>
        </tr>
        <tr class="thursday">
            <th>Thursday</th>
            <td>Quantum Computing</td>
            <td>C Programming</td>
            <td>Digital Electronics</td>
            <td>Free</td>
        </tr>
        <tr class="friday">
            <th>Friday</th>
            <td>Communicative English</td>
            <td>Web Application</td>
            <td>Quantum Computing</td>
            <td>Free</td>
        </tr>
        <tr class="saturday">
            <th>Saturday</th>
            <td>Free</td>
            <td>Web Application</td>
            <td>IOT</td>
            <td>Free</td>
        </tr>
        <tr class="holiday">
            <th>Sunday</th>
            <th colspan="5">Holiday</th>
        </tr>
    </table>

    <h2>Subject Details</h2>

    <table>
        <thead>
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19CS420</td>
                <td>Prototyping of IOT</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EE305</td>
                <td>Basics of Electronics and Electrical Engineering</td>
            </tr>
            <tr>
                <td>7</td>
                <td>SH3214</td>
                <td>Physics for Quantum Computing</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
# OUTPUT
![Screenshot 2024-12-06 231801](https://github.com/user-attachments/assets/e5ca5685-b002-4a3b-91b9-3bbafe68a28d)
![Screenshot 2024-12-06 231823](https://github.com/user-attachments/assets/f3883694-d58d-4d7b-b872-d0ab59642a20)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
