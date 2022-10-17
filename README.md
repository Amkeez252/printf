# printf
Printf projects for two collaborators


# printf ()
The printf project is a collaboration project by Auwal Abdulmalik, students of the ALX Software Engineering Programme by Holberton School, in which a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

_printf() is a function that performs formatted output conversion and prints data. Its prototype is the following:

int _printf(const char *format, ...)

Where format contains the string that is printed. As _printf() is variadic function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:

%[flags][length]specifier

