Arithmetic DSL
=========

Compiling/Running
------
In order to compile and run the code, you need to install 'sbt'.

You can run the main file using the following command:

`sbt run`

Step 1
------
At this step, we implement the AST and parser for a simple arithmetic DSL with the following constructs:
1) addition, 2) substraction, and 3) a constant value.

Step 2
------
At this step, we define an interpreter for the DSL we have defined in the previous step.

Step 3
------
At this step, we extend the DSL with the following constructs:
4) multiplication, and 5) division.

Note how the AST, the parser, and the interpreter are modified to reflect the changes to the DSL. 