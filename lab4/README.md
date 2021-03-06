# Lab 4 

Lab 4 is a big project that contains different parts. 

## Part 1
For the first part the following should be handed in:

* EER-diagram as a pdf file
* Relational Model as a pdf file
* Functional dependencies for all relations as .txt or .pdf

**Please mark your courseCode_GroupNumber, name, and liU-id on the file (the GroupNumber can be found on Webreg, where you registered the lab)**

e.g.,<br/>
TDDD37_GroupA1:<br/>
YOURNAME (liU-id)<br/>
XXXXXXXX (liU-id)

### EER-diagram and Relational Model
Same as in lab 2, do it in draw.io and add it to gitlab

### Functional depdencies 
Find the Candidate keys, primary keys and whether the table is in BCNF or not. If it is not in BCNF, motivate why! 

## Part 2
This is the coding phase of the project. **Do not start coding until your EER and RM is approved!**

When you make sure that all test scripts could output expected result on your project, the following should be handed in: 

* EER-diagram as .pdf
* Relational Model as .pdf
* Functional dependencies for all relations as .txt or .pdf
* Project code as one file named lab4.sql, which should be executable directly without any error
* Answers to the non code questions as SQL-comments in the lab4.sql file, place them at the end of the file
* An identified secondary index as SQL-comments in the lab4.sql file (do not implement it), place at the end of the file
* A file named q10b.sql that is your modified version of Question10MakeBooking.sql

### Code
Please delete all your created tables and views in the beginning of the file!

You can do this by temporarily disabling Foreign Keys in MySQL. Do not forget to enable it again!

`
SET FOREIGN_KEY_CHECKS=0;
DROP TABLE XXX;
SET FOREIGN_KEY_CHECKS=1;`

#### The test scripts

**Question 3** 

Confirm that you have 208 flights in your database


**Question 6**

Confirm that the output is correct. 

Confirm that the change has actually been done in the database. i.e. in Test 13, confirm that the reservation was actually delete. 


**Question 7**
This test is correct if there is no output at all. If you get output it means something is wrong. See which rows are different to the result. 
Common errors are rounding errors and route errors


#### Issues
You will most likely run into problems during the coding phase! Create issues, tag your lab assistant and reference where in the code you are having problems! 

## Part 3
Send in the code to urkund. Change the file ending from lab4.sql to lab4.txt! Send it to urkund when you have passed lab4c) on WebReg! Details are on course website.


