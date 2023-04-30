Download Link: https://assignmentchef.com/product/solved-final-project-titanic-solved
<br>
Design a Java application that will read a file containing data related to the passengers on the Titanic. The description of the file is shown below. The application should provide statistical results on the passengers including:

Total number of passengers on the Titanic

Total number of passengers who perished on the Titanic

Total number of Passengers who survived the sinking of the Titanic

Number of passengers who survived the sinking of the Titanic as a function of the passenger class (e.g. 1,2,3)

Number of passengers who survived the sinking of the Titanic as a function of the passenger gender (e.g., male, female)

A list of the names of passengers who paid greater than $200 for their tickets

A list of the names of passengers who were less than 10 years old who survived the sinking of the Titanic

A list of the names of passengers who were less than 10 years old who perished on the Titanic

The count of the number of passengers as a function of the first letter of their last name. (e.g., A: 13, B:33)

Additional statistical results you add to enhance the functionality

The following are some design criteria and specific requirements that need to be addressed:

Use command line arguments to send in the name of the Titanic file.

Use a 2D array to store the Titanic data. (Hint: You will probably need to store the array as String values and then convert to other types as needed since some data is null)

You should create at least 2 Java classes – Titanic and TestTitanic. You are welcome to create additional classes if you want to further separate the functionality.

You should create separate methods for each of the required functionality. (e.g. getTotalPassengers() will return the total number of passengers on the Titanic).

A user-friendly and well-organized menu should be used for users to select which data to return. A sample menu is shown in run example. You are free to enhance your design and you should add additional menu items and functionality.

The menu system should be displayed at the command prompt, and continue to redisplay after results are returned or until Q is selected. If a user enters an invalid menu item, the system should redisplay the menu with a prompt asking them to enter a valid menu selection

The application should keep track of the elapsed time (in seconds) between once the application starts and when the user quits the program. After the program is exited, the 2 application should provide a prompt thanking the user for trying the Titanic program and providing the total time elapsed.

Here is sample run:java TestTitanic Titanic.txt********** Welcome to the Titanic Statistical Application **************************Enter the number of the question you want answered. Enter “Q” to quit the program :

How many passengers were on the Titanic?

What percentage of passengers perished on the Titanic?

What percentage passengers survived the sinking of the Titanic?

What percentage of passengers survived for each of the three classes?

What percentage of passengers survived as a function of gender?

What specific passengers paid more than $200 for their tickets?

What specific passengers who were less than 10 years old perished on the titanic?

What specific passengers who were less than 10 years old survived the sinking of the titanic?

For each letter in the alphabet, how many passengers last names started with that letter?

Q. Quit the program

Enter your selection: 1There were 1310 Passengers on the Titanic.Submission requirements:Your deliverables include all Java files (.java) and a single word (or PDF) document. The Java files should be named appropriately for your applications. Your word document should include screen shots showing the successful compiling and running of each application, and a detailed description of the test plan for each application. The test plan should include the input, expected output, actual output and if the test case passed or failed. Submit your files to the Final Project assignment area no later than the due date listed in the calendar.Titanic Data Description:The attached tab delimited file, named titanic.txt contains the known passengers on the Titanic. There are 5 fields included in the file in the order:Passenger class (1,2,3)Survived (1=yes, 0=no)Name (Passenger name)sex (male or female)age (some values are blank)fare (some values are blank)


