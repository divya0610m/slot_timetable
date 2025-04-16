# Ex03 Time Table
## Date: 16-04-2025

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
    </head>
    <body>
        <center>
            <img src="c:\Users\admin\Documents\web\logo.png" height="100" width="540">
        </center>
        <center>
            <h1> SLOT TIMETABLE </h1>
            <h2> DIVYA LAKSHMI M (Reg no:212224040082)</h2>
            <hr color="black">
        </center>
        <table align="center" width="450" cellspacing="2" cellpadding="4" border="5" bgcolor="pink">
            <tr align="center">
                <th bgcolor="lightblue">DAY/TIME</th>
                <th bgcolor="lightblue">8:00-10:00</th>
                <th bgcolor="lightblue">10:00-12:00</th>
                <th bgcolor="lightblue">12:00-1:00</th>
                <th bgcolor="lightblue">1:00-3:00</th>
                <th bgcolor="lightblue">3:00-5:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">MONDAY</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>LUNCH</td>
                <td>C PROGRAMMING</td>
                <td>FREE SLOT</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">TUESDAY</th>
                <td>FREE SLOT</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>LUNCH </td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                
                
            </tr>
            <tr align="center">
                <th bgcolor="lightblue">WEDNESDAY</th>
                <td>DIGITAL ELECTRONICS</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>LUNCH</td>
                <td>MENTOR MEET</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <TH bgcolor="lightblue">THURSDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>C PROGRAMMING</TD>
                <TD>LUNCH</TD>
                <TD>CHEMISTRY</TD>
                <TD>PROBABILITY</TD>
            </tr>
            <TR align="center">
                <TH bgcolor="lightblue">FRIDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>HUMAN VALUES AND PROFFESIONAL ETHICS</TD>
                <TD>LUNCH</TD>
                <TD>FREE SLOTS</TD>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>

            </TR>
            <TR align="center">
                <TH bgcolor="lightblue">SATURDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>CHEMISTRY</TD>
                <TD>LUNCH</TD>
                <TD>REASONING ABILITY</TD>
                <TD>PROBABILITY</TD>

            </TR>
        </table>
        <BR>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO : </th>
                <TH>SUBJECT CODE :</TH>
                <TH>SUBJECT NAME :</TH>
            </tr>
            <TR align="center">
                <td>1.</td>
                <td>19AI414</td>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
            </TR>
            <TR align="center">
                <TD>2.</TD>
                <TD>19AI304</TD>
                <TD>FUNDAMENTALS OF C PROGRAMMING</TD>
            </TR>
            <TR align="center">
                <TD>3.</TD>
                <TD>19HS801</TD>
                <TD>HUMAN VALUES AND PROFESSIONAL ETHICS</TD>
            </TR>
            <TR align="center">
                <TD>4.</TD>
                <TD>19MA222</TD>
                <TD>PROBABILITY AND QUEUEING MODELS</TD>
            </TR>
            <TR align="center">
                <TD>5.</TD>
                <TD>19CY205</TD>
                <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
            </TR>
            <TR align="center">
                <TD>6.</TD>
                <TD>19EY709</TD>
                <TD>REASONING ABILITY</TD>
            </TR>
            <TR align="center">
                <TD>7.</TD>
                <TD>19EE404</TD>
                <TD>DIGITAL ELECTRONICS</TD>
            </TR>
        </table>
        
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-04-16 141159.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
