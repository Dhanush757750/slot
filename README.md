# Ex03 Time Table
## Date:17-11-2024

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
        <title>MY TIMETABLE</title>
    </head>
    <body>
        <CENTER>
        <IMG SRC="\static\logo.png" WIDTH="700"><BR>
        <TABLE BORDER="4" CELLPADDING="5" BGCOLOR="VIOLET">
            <TR >
                <TD COLSPAN="7" ALIGN="CENTER" BGCOLOR="PINK">SLOT TIME TABLE DHANUSH(24009885) </TD>
            </TR>
        <tr BGCOLOR="LIGHTGREEN">
            <TH>TIME/DAY</TH>
            <th>MONDAY</th>
            <TH>THUESDAY</TH>
            <TH>WEDNESDAY</TH>
            <TH>THURSDAY</TH> 
            <TH>FRIDAY</TH>
             <TH>SATURDAY</TH>
        </tr>
        <TR>
            <TD BGCOLOR="LIGHTGREEN">08-10</TD>
            <TD>--</TD>
            <TD>COMPUTER ARCHITECTURE</TD>
            <TD>--</TD>
            <TD>--</TD>
            <TD>CHEMISTRY</TD>
            <TD>--</TD>
            </TR>
        <TR>
            <TD BGCOLOR="LIGHTGREEN">10-12</TD>
            <TD>WEB APPLICATION</TD>
            <TD>MATHS</TD>
            <TD>WEB APPLICATION</TD>
            <TD>COMPUTER ARCHITECTURE</TD>
            <TD>PYTHON PROGRAMME</TD>
            <TD>MATHS</TD>
        </TR>
                <TR>
            <TD COLSPAN="7" ALIGN="CENTER" BGCOLOR="LIGHTBLUE">&LT;12:00-1:00&GT;LUNCH</TD>
        </TR>
        <TR>
            <TD BGCOLOR="LIGHTGREEN">01-03</TD><TD>PYTHON PROGRAMME</TD><TD>CHEMISTRY</TD><TD>MENTOR MEETING</TD><TD>CAREER DEVELOPMENT</TD><TD>----</TD><TD>WEB APPLICATION</TD>
        </TR>
    </CENTER>
        </TABLE>
    </body>
</html>
<TABLE BORDER="4" CELLPADDING="5" BGCOLOR="white">
    <tr align="center">
        <th>S.No</th>
        <th>Course Code</th>
        <th>Course Name</th>
    </tr>
    <tr align="center">
        <td><b>1.</b></td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra (MATH)</td>
    </tr>
    <tr align="center">
        <td><b>2.</b></td>
        <td>19EY708</td>
        <td>Career Development Skills (CDS)</td>
    </tr>
    <tr align="center">
        <td><b>3.</b></td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application and Development(FWAD)</td>
    </tr>
    <tr align="center">
        <td><b>4.</b></td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering (CHE)</td>
    </tr>
    <tr align="center">
        <td><b>5.</b></td>
        <td>19CS305</td>
        <td>Computer architecture(CA)</td>
    </tr>
    <tr align="center">
        <td><b>6.</b></td>
        <td>19AI301</td>
        <td>Python Programming(Pyth prog)</td>
    </tr>
    <tr align="center">
        <td><b>7.</b></td>
        <td>ECA-M-SCOFT</td>
        <td>Mentor Meet (MEET)</td>
    </tr>

</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-17 220001.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
