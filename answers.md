# Lab 02 - Scope Exercise
## Wyatt Pefley
## Questions:
### Question 1: 
When this code is run in Node, e.g. node index.js, what are the two stages of execution for this file called, and which order do they happen in?
  - Answer: The two stages of execution for this file would be hoisting and interpretation or execution. in that order.
### Question 2:
- Write an explanation, using as much space as you need, relating to how the first stage of execution for this file operates.

  - For example, identify the high level steps in a line by line overview and then define what each of those steps are accomplishing.
- Answer: During compilation  the code will be run through and keeps track of what functions and variables are declared and "hoists" them to the top to be used later.
### Question 3:
Write an explanation, using as much space as you need, relating to how the second stage of execution for this file operates.

For example, identify the high level steps in a line by line overview and then define what each of those steps are accomplishing.
- Answer: During execution, the code is executed and assigns values to the variables that were found during the previous stage, functions that were hoisted are also invoked during this stage as well.
### Question 4:
During the second stage of execution how many scopes have been registered by the engine?

Which segments of the code do they belong to?
Please identify any variables/refs and which scope each belongs to?
- Answer: In this code, there are three scopes. The first being the global scope, the second being baz(), and the third being bar().
- var foo = 'bar' (global)
- 
### Question 5:
When line 13 invokes the baz function, which foo will be assigned a value of bam? More specifically, bam will be assigned to the foo in ??? scope. Give a brief description in your own words to support your conclusion.

### Question 6:
Which scope, if any, will the variable bam on line 11 be registered to when the first stage of execution occurs on this file? Provide a brief description in your own words to support your conclusion.

### Question 7:
For each line, 16 through 19, what is the return value for each?