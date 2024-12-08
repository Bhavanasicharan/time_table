# Ex03 Time Table
# Date:17-11-2024
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
<html>
    <head>
        <title>MY TIMETABLE</title>
    </head>
    <body>
        <CENTER>
        <IMG SRC="C:\Users\admin\time_table\slottimetable\tableapp\static\logo.png.png"height="100"width="600"><BR>
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
            <TD>BEEM</TD>
            <TD>--</TD>
            <TD>ENGLISH</TD>
            <TD>PHYSICS</TD>
            <TD>--</TD>
            </TR>
        <TR>
            <TD BGCOLOR="LIGHTGREEN">10-12</TD>
            <TD>ENGLISH</TD>
            <TD>PHYSICS</TD>
            <TD>BEEM</TD>
            <TD>MATHS</TD>
            <TD>WEB APPLICATION</TD>
            <TD>WEB APPLICATION</TD>
        </TR>
                <TR>
            <TD COLSPAN="7" ALIGN="CENTER" BGCOLOR="LIGHTBLUE">&LT;12:00-1:00&GT;LUNCH</TD>
        </TR>
        <TR>
            <TD BGCOLOR="LIGHTGREEN">01-03</TD><TD>WEB APPLICATION</TD><TD>COMPUTER ARCHITECTURE</TD><TD>MENTOR MEETING</TD><TD>CAREER DEVELOPMENT</TD><TD>COMPUTER ARCHITECTURE</TD><TD>MATHS</TD>
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
        <td>19MA222</td>
        <td>PROBABILITY AND QUEUENG MODELS (MATHS)</td>
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
        <td>SH3214</td>
        <td>PHYSICS FOR QUANTUM COMPUTING (PHYSICS)</td>
    </tr>
    <tr align="center">
        <td><b>5.</b></td>
        <td>19CS305</td>
        <td>Computer architecture(CA)</td>
    </tr>
    <tr align="center">
        <td><b>6.</b></td>
        <td>19EE305</td>
        <td>BASIC ELECTRICAL,ELECTRONIC
         AND MEASURMENT ENGINEERING (BEME)</td>
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
# OUTPUT
![alt text](<Screenshot 2024-12-08 102627-1.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
