# Get the capital letters in a string
This is an introduction to flex for compiler construction.

The file capital.l contains the flex code for checking the number of capital letters present in an input. The file is then compiled to a C file named lex.yy.c. 
The C code will compile to an executable file named a.exe

To run the file capital.l :
* open the command prompt and run ```flex capital.l```, this will create lex.yy.c
* Then run the c file using ```gcc lex.yy.c```, a.exe will be created
* Finally, run the executable file using ```./a```

When you run that, you can input any string and the program will be able to give a count of the capital letters used.
For example:

![Screenshot (98)](https://github.com/Nkatha004/CapitalLetters/assets/69391540/396a94e3-416d-48f6-b6fc-a0f50088affc)
