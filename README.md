# Student_Report_Management_System
1.INTRODUCTION

This Student Report card project is written in C language . This is a simple menu-driven console based application.In this application you can store student marks and accordingly their percentage and grades.The application is made very user-friendly so that everyone can use it without any problem.This. A Student Report Card Management system is a system of organizing Student marks in well organized order for college or schools  purposes. 
This project Student Report Card Management System includes facilities of registration,search,display,modification,deletion of student information about the marks and their name and roll numbers.This software search the student information on the basis of roll number which is store in the record.This System used for schools and colleges for maintaining their records related to report card and marks of student and cost savings.This System will automatically arrange the students name according to their marks i.e the one who scored more will have his or her name on the top of the records.This Report Card Management System also provide facilities for any kind of modification or change in records of student.











2.OVERALL DESCRIPTION
This Student Report Card Management System is a console based application developed in C using Turbo-C++.It basically provides user with a menu of various actions which can be performed in the application.The user can enter his choice from the menu provided, which will further give ask the user more inputs .
This Report Card Mnagement System has following features :-
- Create /Modify / Delete Student Record
- Display all the Student record
- Search Student record
- Student Report Card
- Class Result
User can perform any of these actions multiple times  A separate ‘EXIT’ choice is also provided for user when he is done using the Student Report Card Management System.
2.1 Header Files used –
-stdio.h - The C programming language provides many standard library functions for file input and output. These functions make up the bulk of the C standard library header <stdio.h>.The functionality descends from a "portable I/O package" written by Mike Lesk at Bell Labs in the early 1970s, and officially became part of the Unix operating system in Version 7
-conio.h - is a C header file used mostly by MS-DOS compilers to provide console input/output. It is not part of the C standard library or ISO C, nor it is defined by POSIX.
This header declares several useful library functions for performing "console input and output" from a program. Most C compilers that target DOS have this header and supply the associated
library functions in the default C library. Most C compilers that target UNIX and Linux do not have this header and do not supply the library functions. Some embedded systems or cc65 use a conio-compatible library. 
-process.h- is a C header file which contain fuction declarations and macros used in working with threat and processes.It is used to use some predefined function like abort(),exit(),system().

2.2 User-defined Functions made  –
	void write_student()
	void display_student()
	void display_sp(intn)
	void modiy_student()
	void delete_student()
	void class_result()
	void result()
	void intro()
	void entry_menu()

2.3 File handling functions used –
fopen-  is the standard C function for opening or creating streams. It is primarily used for reading from and writing to files, though there are other uses as well
fclose-  is the standard C function for closing streams 
fputc- is the standard C function for writing character in a file 
fgetc - is the standard C function for reading character from a file.
fwrite-is the standard C function for writing number of objects to the desired file.
fseek-is the standard C function to set the file pointer to specified offset.
fflush-is the standard C function use to flush/clear the file.

2.4 Switch-case-
A switch statement tests the value of a variable and compares it with multiple cases. Once the case match is found, a block of statements associated with that particular case is executed.
                                  

2.5 Loops used-

for loop - A  for  loop  is  a  repetition  control  structure  which  allows  us  to  write a loop that is executed a specific number of times.
                                              



while loop - while statement is being used for loop operation for example printing numbers form 1 to10.
i=1;
while(i<=10)
{
printf("%d",i);
i++
}


2.6 –Flowchart -





3.SPECIFIC REQUIREMENT

3.1 Language used – C
C is a general-purpose, procedural computer programming language supporting structured programming , lexical variable scope and recursion while a static type system prevents unintended operations. 
3.2 Why I used C?
C provides efficiency, high performance, and high quality softwares, flexibility and power, many high-level and low-level operations like middle level, stability and small size code, provide functionality through rich set of function libraries.
3.3 IDE used – 
 TURBO-C++
3.4 Space Required-
The code size is 8.0KB and since some space is to be reserved for creating notes , a minimum of 2 MB space is required on hard disk for this Application to run properly.

