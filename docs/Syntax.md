Z-Dash Lite Syntax Guide
This document provides an overview of the syntax used in Z-Dash Lite.

Variable Declarations

BIT
Declare a bit variable.
Syntax: BIT <varname> <value>

STRING
Declare a string variable.
Syntax: STRING <varname> <value>

NUM
Declare a number variable.
Syntax: NUM <varname> <value>

INUM
Declare an integer number variable.
Syntax: INUM <varname> <value>

Button Commands
BUTTON_<name>
Execute a command when the button is pressed. The <name> part is specified by the user.
Syntax: BUTTON_<name> <command>

Math Commands

ADD
Add two variables and store the result in a third variable.
Syntax: ADD <result_var> <var1> <var2>

SUB
Subtract the second variable from the first and store the result in a third variable.
Syntax: SUB <result_var> <var1> <var2>

MULT
Multiply two variables and store the result in a third variable.
Syntax: MULT <result_var> <var1> <var2>

DIV
Divide the first variable by the second and store the result in a third variable.
Syntax: DIV <result_var> <var1> <var2>

INV
Invert the value of the variable.
Syntax: INV <var>


Utility Commands

RANDOM
Generate a random number between two specified values and store the result in a variable.
Syntax: RANDOM <var> <low> <high>

BACK
Jump back to the start of the code.
Syntax: BACK

LBACK
Jump back or forward by a specified number of lines.
Syntax: LBACK <line>

SAVE
Set the variable to a specified value.
Syntax: SAVE <varname> <value>

Display Commands

DISPLAY
Set text or variable value at a specific row and column on the display.
Syntax: DISPLAY <row> <col> <message or variable>

CLRDISP
Clear the display.
Syntax: CLRDISP

Other Commands

DELAY
Delay execution for a specified amount of time in milliseconds.
Syntax: DELAY <time>

HALT
Halt the program and display an error on the screen.
Syntax: HALT

IF
Execute a command if a variable satisfies a specified condition.
Syntax: IF <var> <operator> <value> <command>

ABUT
Add a button with the specified name.
Syntax: ABUT <name>
