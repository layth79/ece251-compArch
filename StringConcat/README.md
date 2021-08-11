# CompArch - Ari Ghuman, Xue Ru Zhou, Husam Almanakly, Layth Yassin

To build and run the assembly code,  use command ”make all” 
while on the micro-lab server, and it should create an executable 
named "a.out".  To execute, run ./a.out from the current directory 
and enter the prompted input.

For project #1, you will ask the user to input 2 strings and concatenate the two. Both strings will have at most 12 ASCII characters. You will ask the user to enter the first string after which they will hit enter. If the number of characters exceeds the 12-character limit, you will print an error and exit the program with a 7 return code. If the number of characters is less than or equal to 12 characters, you will ask them to enter another string. If the second string exceeds the character limit, your program should print an error message and exit with an 8 return code.

If both strings meet the requirements, you will then output the concatenated string to stdout and return an error code that consists of the total number of characters in the concatenated string.
