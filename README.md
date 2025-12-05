# Ex03 Time Table
## Date: 27/11/2025
## Ref: 25013019

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
<<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="white">
    <caption><b>SLOT TIME TABLE - PRANITHA S (25013019)</b></caption>
    <tr align="center">
      <th bgcolor="orange">Day/Time</th>
      <th bgcolor="yellow">Monday</th>
      <th bgcolor="yellow">Tuesday</th>
      <th bgcolor="yellow">Wednesday</th>
      <th bgcolor="yellow">Thursday</th>
      <th bgcolor="yellow">Friday</th>
      <th bgcolor="yellow">Saturday</th>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">8-10</th>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="coral">C.E.</td>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="blueviolet">C PROGRAMMING</td>
        <td bgcolor="lime">FREE SLOT</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">10-12</th>
        <td bgcolor="coral">C.E.</td>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="cornflowerblue">F.W.A.D.</td>
        <td bgcolor="cornflowerblue">F.W.A.D.</td>
        <td bgcolor="cornflowerblue">F.W.A.D.</td>
        <td bgcolor="cornflowerblue">F.W.A.D.</td>
    </tr>
    <tr>
        <th bgcolor="yellow">12-1</th>
        <td colspan="6" align="center" bgcolor="cyan">L U N C H</td>
    </tr>
    <tr align="center">
        <th bgcolor="yellow">1-3</th>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="coral">C.E.</td>
        <td bgcolor="red">MENTOR MEET</td>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="lime">FREE SLOT</td>
        <td bgcolor="coral">C.E.</td>
    </tr>
        <tr align="center">
        <th bgcolor="yellow">3-5</th>
        <td bgcolor="blueviolet">C PROGRAMMING</td>
        <td bgcolor="blueviolet">C PROGRAMMING</td>
        <td bgcolor="blueviolet">C PROGRAMMING</td>
        <td bgcolor="blueviolet">C PROGRAMMING</td>
        <td bgcolor="cornflowerblue">F.W.A.D.</td>
        <td bgcolor="lime">FREE SLOT</td>
    </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19AI304</td>
            <td>Fundamentals of C Programming(C Prog)</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19EN101</td>
            <td>Communicative English(CE)</td>
        </tr>
    </table>
</body>
</html>
~~~

## OUTPUT
<img width="1919" height="967" alt="slot 1" src="https://github.com/user-attachments/assets/56b39ef9-bfb1-4278-88b8-f389fcf7594f" />
<img width="1093" height="522" alt="slot 2" src="https://github.com/user-attachments/assets/18fe4223-4e61-4eaa-b507-1ba6bc35ce83" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
