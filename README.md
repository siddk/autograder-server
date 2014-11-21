#Autograder-Server#

A NodeJS Snap! Autograder to interface with the BJCx edX course. Meant for use in the grading of labs, projects, and homeworks.

###Structure of the Repository###

+ snap-interpreter - A command line interpreter for Snap! built in NodeJS, forked from (https://github.com/bromagosa/snap-interpreter). Feed it an XML Snap! project file, and it runs it.


###Autograder Logic###

Using the interpreter, create an automation script that loads student project/lab/homework files and runs them, then compare output to expected solution output. From there, create a method of reporting back any errors in an efficient and cohesive fashion.

In other words:

Load Snap! File --> Run through Interpreter --> Check solutions --> Report errors