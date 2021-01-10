# Fix Bugs of the Application.
Fix the bugs in the application using the appropriate algorithmic techniques.
## Steps to run:
* git clone https://github.com/AlhiloMustafa/FixBugs.git
* Open it in IntelliJ/Eclips and run the file Main.java
* Follow the instructions that will appear in the IDE's terminal.


##### The bugs have been fixed by the following steps:

* First step, I moved the given “ arrlist “ and “ expenses “ contractors to the class level scope and made them static, to prevent creating new list each iteration.

* Add the missing source code to the application based on searching technique.
    - Steps :
        - Get the expenditure from the user to search for it, by using scanner class . 
        - Set a flag value to false. 
        - Iterate through the expenditures array list.
        - Compare each item in the expenditures list with entered expenditure by the user. If the value exists in the list, the program will set the flag value to true and prints the expenditure.
        - When the program exits the loop, it checks the flag value if it is still false. If yes, then it prints “ value not found”. 

* Write source code for sorting the predefined array and ensure the functionality of the application.
    - Steps :  
        - Inside sortExprenses method Collections class. 
        - Use sort method in the collections class
        - Pass the array list (expenditures) to the sort method to get them sorted .

