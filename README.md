# Ex03 Time Table
## Date:25.11.2024

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
<html>
    <body>
        <center>
        <img src ="/static/logo.png" width="700" height="200">
        </center>
        <table align = "center"width="540" border="2" cellspacing="5" cellpadding="1">
         <caption>Weekly schedule-Harini S(24901228)</caption>
         <tr bgcolor="grey">
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
         </tr>
         <tr bgcolor="blue">
            <td >8-10</td>
            <td>Free</td>
            <td>Chem</td>
            <td>Free</td>
            <td>Com.eng</td>
            <td>FWAD</td>
            <td>Free</td>
         </tr>
         <tr bgcolor="blue">
            <td >10-12</td>
            <td>Com eng</td>
            <td>CMA</td>
            <td>C</td>
            <td>B.EEE</td>
            <td>C</td>
            <td>CMA</td>
         </tr>
         <tr bgcolor="yellow">
            <td >12-1</td>
            <td colspan="6">LUNCH</td>
         </tr>
         <tr bgcolor="blue">
            <td ">1-3</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>Mentor meet</td>
            <td>Chem</td>
            <td>B.EEE</td>
            <td>CDS</td>
         </tr>
         <tr bgcolor="blue">
            <td>3-5</td>
            <td colspan="6">FREE</td>
        
         </tr>
        </table>
        <table align ="center" width="540" border="2">
        <caption>SUBJECTS</caption>
        <tr>
            <th>S.No</th>
            <th>Subject code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development(FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN101</td>
            <td>Communicative english</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra(CMA)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI304</td>
            <td>Fundamentals of C programming</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE305</td>
            <td>Basic Electrical,Electronics and Measurment Engineering(B.EEE)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EY708</td>
            <td>Career Development Skills(CDS)</td>
        </tr>


        </table>

         
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (13).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
