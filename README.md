# sample_C-
C++ Project

This program is designed to display, to add new data into a table and to search the paternal tree of a specified animal in a specified group.

Before calling all the functions related to requirements, "readFromFiles()" is called to import the data from files into the program.

The function for displaying the table is named “displayTable()”and it’s called from “main()”.
The function receives the reference of animal group vectors as parameters. 
By using a for loop for each animal group I display all the data from the vectors in a table.


The function for adding new data into the table is named “addData()”and it’s called from “main()”.
The function receives the reference of animal group vectors as parameters. 
By making use of a switch statement it determines the group of the animal to be introduced and allows users to enter the data about it.
At the end, it writes the new data into the file of that animal.
Furthermore after the completion of “addData()” the vectors of animals are cleared and the new data from the files is inputted. 


The function for search the paternal three of a specified animal in a specified group is named “paternalThree()”and it’s called from “main()”. 
The function receives the reference of animal group vectors as parameters. 
The user is required to introduce the initial of the animal group in which the search will be conducted and the name of the animal.
By using a set of if statements the group of animals is determined and searched through it.
The search is done using a for loop which iterates through the vector and adding the fathers into a string which contains the results.
If the animal is not to be found anywhere in the vectors a message will be displayed accordingly. 
In the “main()” function local variables are create to store all the information from the files as vectors.
By using a do while loop a persistent state is enabled and the program will not close after just a run.
In the do while loop I have a switch case structure used to determine the user option. 
