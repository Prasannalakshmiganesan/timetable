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

# CODE:
```<!DOCTYPE html>
<html lang="en">
<head>
  <title>TIMETABLE</title>
   <style>
    table {
      width: 700px;
      border-spacing: 10px;
      border: 3px solid;
    }

     td, th {
      border: 3px solid;
      padding: 10px;
    }
  </style>
  
</head>
<body>
   
    <img src="/static/images/LOGO.png" alt="saveethalogo" height="100" width="600">
   <table> 
    <tr>
      <th colspan="6">TIMETABLE</th>
    </tr>
    <tr>
      <th colspan="2" >Reference Number</th>
      <th>22008696</th>
      <th>Name</th>
      <th colspan="2">Prasannalakshmi G</th>
    </tr>
        <tr>
           <td>DAYS</td>
           <td> Reg number: </td>
           <td> 22008696  </td>
           <td>LUNCH</td>
           <td>Name</td>
           <td>Prasannalakshmi G</td>
        </tr>
        <tr>
            <td>Class Hours</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
        </tr>
                <tr>
            <td>MONDAY</td>
            <td>19MA219</td>
            <td>19AI414</td>
            <td>-</td>
            <td>19EN101</td>
            <td>19MA221</td>
        </tr>
                 <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>19MA220</td>
            <td>-</td>
            <td>19AI414</td>
            <td>-</td>
        </tr>
                 <tr>
            <td>WEDNESDAY</td>
            <td>19MA221</td>
            <td>-</td>
            <td>19AI414</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>19MA219</td>
            <td>ECA-M-AIDS</td>
            <td>19MA220</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>19EY701</td>
            <td>-</td>
            <td>19AI301</td>
            <td>19EN101</td>
            <td >-</td>
        </tr>
    </table>
    <ol>
        <li>SUBJECT CODE - SUBJECT - FACULTY</li>
        <li>19AI414 - Fundamentals of Web App Development - C.Obed Otto</li>
        <li>19EN101 - Communicative English - A.Anne Dorathy</li>
        <li>19AI301 - Python Programming - E.T.Jaba Jasphin</li>
        <li>19MA221 - Linear Algebra Laboratory - E.T.Jaba Jasphin</li>
        <li>19MA220 - Maths for Artificial Intelligence - E.T.Jaba Jasphin</li>
        <li>ECA-M-AIDS - Mentor Meet - S.Surya</li>
        <li>19EY701 - Soft Skills - V.David Raja</li>
        <li>19MA219 - Transform and Its Applications - H.Prathab</li>
    </ol>
</body>
</html>

```

# OUPUT:
![TIMETABLE](./images/timetable.png)

# HTML VALIDATION:
![WEBPAGEVALIDATION](./images/webpagevalidation.png)
