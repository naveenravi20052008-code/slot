# Ex03 Time Table
## Date:05/12/2025
# REF : 25011967

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
~~~

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weekly Timetable</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      text-align: center;
    }
    th, td {
      border: 1px solid #000;
      padding: 8px;
    }
    th {
      background-color: #f2f2f2;
    }
    td {
      height: 40px;
    }
    img.heading {
      display: block;
      margin: 0 auto 20px;
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <!-- Replace the src below with your actual image file or URL -->
  <img src="/static/logo.png" alt="Heading Image" class="heading">

  <h2>Weekly Timetable</h2>
  <table>
    <tr>
      <th></th>
      <th>8-9 AM</th>
      <th>9-10 AM</th>
      <th>10-11 AM</th>
      <th>11-12 PM</th>
      <th>1-2 PM</th>
      <th>2-3 PM</th>
      <th>3-4 PM</th>
      <th>4-5 PM</th>
    </tr>
    <tr>
      <th>Monday</th>
      <td>Data Science</td>
      <td>Data Science</td>
      <td>-</td>
      <td>-</td>
      <td>FWD</td>
      <td>FWD</td>
      <td>Python</td>
      <td>Python</td>
    </tr>
    <tr>
      <th>Tuesday</th>
      <td>Data Science</td>
      <td>Data Science</td>
      <td>Python</td>
      <td>Python</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
    </tr>
    <tr>
      <th>Wednesday</th>
      <td>Data Science</td>
      <td>Data Science</td>
      <td>FWD</td>
      <td>FWD</td>
      <td>-</td>
      <td>-</td>
      <td>FWD</td>
      <td>FWD</td>
    </tr>
    <tr>
      <th>Thursday</th>
      <td>-</td>
      <td>-</td>
      <td>Data Science</td>
      <td>Data Science</td>
      <td>-</td>
      <td>-</td>
      <td>FWD</td>
      <td>FWD</td>
    </tr>
    <tr>
      <th>Friday</th>
      <td>-</td>
      <td>-</td>
      <td>Python</td>
      <td>Python</td>
      <td>-</td>
      <td>-</td>
      <td>Data Science</td>
      <td>Data Science</td>
    </tr>
    <tr>
      <th>Saturday</th>
      <td>Python</td>
      <td>Python</td>
      <td>-</td>
      <td>-</td>
      <td>FWD</td>
      <td>FWD</td>
      <td>Python</td>
      <td>Python</td>
    </tr>
  </table>
</body>
</html>
~~~

## OUTPUT
<img width="1057" height="486" alt="image" src="https://github.com/user-attachments/assets/31d1c50e-d992-4a92-847e-f785a92c220a" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
