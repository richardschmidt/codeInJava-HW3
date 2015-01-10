MIS4310 – Programming in Java
Homework 3

Problem 1 (30 points):

PART I:

Create a Java class named “Square” in a package named “SQUARE”. This class has only one attribute: side-length that is defined as private. Class Square declaration provides a default constructor, get-method and set-method of the attribute side-length, and the methods to calculate the perimeter and the area of the square.

PART II:

Write a Java program that can calculate and print out the perimeter and area of a square. The user enters data of the side-length and its measurement unit (“in” for inch, “ft” for feet, “cm” for centimeter, and “m” for meter) from the console. The program should check to be sure that the side-length is not negative and the measurement unit must be one among the listed-above units. 

The Java program should be another Java class named “SquareCalculator” in the same package, i.e. SQUARE. The program creates an object of class Square. After reading the input of side-length, the program sets the value of side-length of the Square object and invokes the public methods of class Square to calculate the perimeter and the area of the square.

Important Notes:
•	To submit PART I, students copy all the code of the class Square into a Notepad file named “hw3_Square” (the file should have the suffix .txt)
•	To submit PART II, students copy all the code of the program SquareCalculator into a Notepad file named “hw3_SquareCalculator” (the file should have the suffix .txt)














Problem 2 (30 points):

PART I:

Create a Java class named “Book” in a package named “BOOK”. This class has 4 attributes:
1.	ISBN number (an integer of 10 digits)
2.	Title
3.	Author (assumed that each book is authored by only one author )
4.	Edition (e.g.: 1st Edition, 2nd Edition, etc. )

 All of them should be defined as private. Class Book declaration provides a default constructor, get-methods and set-methods of the attributes, and a method to display book data in only one line.


PART II

Write a Java program that can read data of a book from the console. The program should check to be sure that the ISBN input is a positive value and input values of title, author, and edition are not empty strings. 

The Java program should be another Java class named “BookDisplayer” in the same package, i.e. BOOK. The program creates an object of class Book. After reading the inputs, the program sets the values of the attributes of the Book object and invokes the public method of class Book to display the book data.

Important Notes:
•	To submit PART I, students copy all the code of the class Book into a Notepad file named “hw3_Book” (the file should have the suffix .txt)
•	To submit PART II, students copy all the code of the program BookDisplayer into a Notepad file named “hw3_BookDisplayer” (the file should have the suffix .txt)











Problem 3 (40 points):

PART I:

Create a Java class named “Student” in a package named “STUDENT”. This class has three attributes: 
1.	Student ID (an integer of 10 digits)
2.	Full name (first last - of String type)
3.	Major (a string)

Class Student declaration provides a default constructor, get-method and set-method for each attribute, and a public method to print out all information of the student in one line.

PART II:

Write a Java program that can store data of three students in an array and display their data, each student in one line. The user enters all three student’s data from the console. It is assumed that the user does not make any mistake while entering students’ data. 

The Java program should be another Java class named “StudentDisplayer” in the same package, i.e. STUDENT. The program creates an array of three elements of class Student type. After reading every piece of data of each student from the console, the program assigns the input to the corresponding element of the array. When all the data of the three students have been entered and correctly stored into the array, the program displays their data, each in one line, by invoking a public method of class Student.


Important Notes:
•	To submit PART I, students copy all the code of the class Student into a Notepad file named “hw3_Student” (the file should have the suffix .txt)
•	To submit PART II, students copy all the code of the program StudentDisplayer into a Notepad file named “hw3_StudentDisplayer” (the file should have the suffix .txt)