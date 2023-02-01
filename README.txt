SMS Application
---------------

How to run:

1. Please find DB information in the hibernate.cfg.xml, and adjust it accordingly, the name of the database will be SMSdb.

 		<!-- Information to connect to database -->
        <property name="connection.driver_class">com.mysql.cj.jdbc.Driver</property>
        <property name="connection.url">jdbc:mysql://localhost:3306/SMSdb?createDatabaseIfNotExist=true</property>
        <property name="connection.username">root</property>
        <property name="connection.password">password</property>


2. Please run the program through App.java

3. Upon running the program you will be asked if it is your first time running the application:

Welcome to the Student Management System!
Is this your first time running the application?
__________________________
1). Yes.
2). No.

Selecting yes will populate the database with the necessary information. 


4. Running the application will produce a work flow like this: 


Welcome to the Student Management System!
Is this your first time running the application?
__________________________
1). Yes.
2). No.
1
Attempting to build and populate SMS Database...
__________________________
The SMS Database has been set up for use!
__________________________
Are you a Student?
__________________________
1). Yes.
2). No.
1
__________________________
Please provide your login information! 
Enter email: 
sbowden1@yellowbook.com
Enter password: 
SJc4aWSU

Login Successful. Welcome!
MY CLASSES:
***YOU ARE NOT CURRENTLY ENROLLED IN ANY CLASSES***
__________________________
What would you like to do? Please choose a number to make a selection:
__________________________
1. Register to a Class.
2. Logout.
1
....
Course ID: 8
Course Name: Data Structures
Course Instructor: Carolan Stoller

Course ID: 9
Course Name: Politics
Course Instructor: Carmita De Maine

Course ID: 10
Course Name: Art
Course Instructor: Kingsly Doxsey

Select the ID of the Course you would like to register for:
8
MY CLASSES:
Course Name: Data Structures
Course Instructor: Carolan Stoller

__________________________
What would you like to do? Please choose a number to make a selection:
__________________________
1. Register to a Class.
2. Logout.
2
Thank you. Goodbye!
