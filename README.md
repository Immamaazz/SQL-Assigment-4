# SQL-Assigment-4
Suppose you have used scripts in Assignment 2 to create tables. Please write ananonymous PL/SQL program for each the following problems. 

Problem 1:  Please write an anonymous PL/SQL program to print out the first10 numbers of the following sequence F(n).F(0) = 2, F(1)=5. F(n)=5*F(n-1)-4*F(n-2).E.g., F(3) = 5*F(2) - 4 F(1) = 5*5-4*2=17,....Your program will print out F(0),F(1),..., F(9).
Hint: use three variables, the first storing F(n), the second storing F(n-1), and the thirdstoring F(n-2). Think of how to compute the first variable from the other two and how toupdate the other two variables in each iteration.

Problem 2:  Write anonymous PL/SQL Please write an anonymous PL/SQLprogram to do ALL of the following:
1) check whether there is a ticket with ID 1.
2) Print out name of the client who submitted the ticket with ID 1, submission time,description and status.
3) print out all rows in ticket_detail that is associated with this ticket (with ID 1),including name of support staff who entered the information, time of the record, andcontent.
Hint: use select count(*) and if then else for step 1.use an implicit cursor to do 
step 2.Use an explicit cursor for step 3.
