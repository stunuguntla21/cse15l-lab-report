# Lab #1 Remote Access and FileSystem
## Sujit Tunuguntla

**1) cd command**

*Example of using the cd command with no arguments:*
![Image](cse15l8.png)
When the cd command is run with no arguments there is no output since the command is used to change directory to the argument.

*Example of using the cd command with a path to a directory as an argument:*
![Image](cse15l5.png)
When the cd command is run with a path to a directory, /home/lecture1, the directory is changed to the path given in the argument, lecture1.

*Example of using the cd command with a path to a file as an argument:*
![Image](cse15l10.png)
When the cd command is run on a path to a file, /home/lecture1/Hello.java, it throws an error that the argument is not a directory as the command is unable to change the directory since the path given was to a file.


**2) ls command**

*Example of using the cd command with no arguments:*
![Image](cse15l11.png)
When the ls command is run with no arguments it produced an output of lecture1 which is the workspace it is in as the command is used to list the files and folders in a given path

*Example of using the cd command with a path to a directory as an argument:*
![Image](cse15l13.png)
When the ls command is run with path directory as the argument it produces and output of the list of the files and folder within, and for the given argument path it prints out a files/folder list: Hello.class  Hello.java  messages  README.
*Example of using the cd command with a path to a file as an argument:*
![Image](cse15l12.png)
When the ls command is used on a path to a file it does not produce a detailed error, as it only outputs the path given as the argument therfore indicating to verify the path to directory is correct. 

**3) cat command**.
*Example of using the cd command with no arguments:*
![Image](cse15l4.png)
When cat command is run with no arguments, there is no output produced since the command functions to print the contents of one or more files whose path is to be given as the argument.

*Example of using the cd command with a path to a directory as an argument:*
![Image](cse15l3.png)
When cat command is used on a path to a directory an error is thrown as the output stating that the given path is to a directory, since the intended argument path is for files.

*Example of using the cd command with a path to a file as an argument:*
![Image](cse15l2.png)
When the cat command is used on a path to a file it prints out the contents within the file and in the case of the text file used in the example, the contents printed out are ¡Hola Mundo!.
