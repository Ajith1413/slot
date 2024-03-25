## Exp03 Time Table
## Date: 25-03-2024

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
    <head>
        <title>My time table</title>
    </head>
    <body>
       <center> <img   src="/static/logo.png" height="=200" width="500"> </center>
        
        <table align="center" border="2" cellspacing="5" cellpadding="12" height="50" width="40" >
            <center><h3><b>TIME TABLE</b></h3></center>
            <center><h4>AJITH KUMAR.A 212223230009</h4></center>
            <tr>
             <th bgcolor="blue">Day/time</th>
             <th bgcolor="red">Monday</th>
             <th bgcolor="red">Tuesday</th>
             <th bgcolor="red">Wednesday</th>
             <th bgcolor="red">Thursday</th>
             <th bgcolor="red">Friday</th>
             <th bgcolor="red">Saturday</th>
            </tr>
            <tr>
                <td  bgcolor="blue">8-10</td>
                <td bgcolor="yellow">digital electroincs</td>
                <td bgcolor="yellow">free slot</td>
                <td bgcolor="yellow">theory of computation</td>
                <td bgcolor="yellow">statistics</td>
                <td bgcolor="yellow">web application</td>
                <td bgcolor="yellow">free slot</td>
            </tr>
            <tr>
                <td  bgcolor="blue">10-12</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">c programing</td>
                <td bgcolor="pink">Free slot</td>
                <td bgcolor="pink" align="centre">c programing</td>
                <td bgcolor="pink">computer networks</td>
                <td bgcolor="pink">theory of computation</td>
            </tr>
            <tr>
                <td  bgcolor="blue">12-1</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td  bgcolor="blue">1-3</td>
                <td bgcolor="violet">computer networks</td>
                <td bgcolor="violet">web application</td>
                <td bgcolor="violet" rowspan="2">free solt</td>
                <td bgcolor="violet">Web application</td>
                <td bgcolor="violet" rowspan="2">free slot</td>
                <td bgcolor="violet"> statistics</td>
            </tr>
            <tr>
                <td bgcolor="blue">3-5</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">free slot</td>
                <td bgcolor="green">digital electroincs</td>
                <td bgcolor="green">free slot</td>
            </tr>
        </table>
        
        <table align="center" border="2" cellspacing="1" cellpadding="12" height="50" width="600">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td align="center">19AI414</td>
                <td >Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td align="center">19CS406</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td>3.</td>
                <td align="center">19AI304</td>
                <td>Fundamentals of c programming</td>
            </tr>
            <tr>
                <td>4.</td>
                <td align="center">19CS407</td>
                <td>Theory of Computation</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE404</td>
                <td>Digital electroincs</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![image](https://github.com/Ajith1413/slot/assets/139842524/d5403211-d5f4-4906-be21-eed87b62b932)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
