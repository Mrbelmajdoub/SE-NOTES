# Map your mind
explain to anyone, without the help of Google:

General:
What is a Pseudocode?
why is Pseudocoding important in programming?
How do you write Pseudocodes?

## concepts
###white boarding
understanding the laguage and frameworks are just tools, they won't teach you problem solving, you devlop it when you practice a lot of coding questions.
new devlopers don't know how to turn their thoughts into code even while understanding the syntax or logic. here are steps of how programmers effectively approach a coding problem.
- step 1: understand and analyze the problem
complelety read the question to small details, write input and output, then while working on the problem ask, is problem fully understood? are you able to explain it to someone else? what and how many inputs are required? what output must came out of them? do you need to separate out some modules or parts of the problem? do you have enough info to solve the question?
- step 2: Go through the sample data and examples throughly
take some sample input and analyze output. can help to determine the output range and cases that can be handled by the code. try complex and bigger output, then edge cases. consider output if there is no input or invalid input. instead of fearing the problem, break it down into smaller chunks and try to solve each. bellow are some steps for complex coding questions
> make a flow chart for the problem at hand: devide int osubproblems and chunks, solve subs by independent functionsm connect solutions of subs by calling them in the required order, or as necessary. whenever possible use classes and objects while handling questions
- step 4: write pseudocode, make a flowchart
defines structure and logic of code. write every line and step
- step 5: replace pseudocode with real code in the language you are working on. 
keep in mind the point where you started, where you are right now, what is you destination (end result)
- step 6: simplify and optimize you code;
find better or alternate solutions. after optimizing ask these questions . Does this code run for every possible input including the edge cases.
Is there an alternate solution for the same problem?
Is the code efficient? Can it be more efficient or can the performance be improved?
How else can you make the code more readable?
Are there any more extra steps or functions you can take out?
Is there any repetition in your code? Take it out.
###flowcharts
diagram to visually represent a workflow or process using a set of symbols or icons to denote different actions/decisions/steps within the process wiht arrows showing the direction of the flow. it provides another approach and understanding to a workflow
- flowchart symbols: ISO 5807 symbol set
flowline: shows the order, comes from a symbol to another
terminal:  shows where a process starts or ends text is usually 'start', 'begin', or 'end'.
process:  process, action, step, or operation, text is usually a verb
data: Inputs to (entering data) and Outputs from (displaying results) a process
decision / conditional: Used to ask a question whose answer determines the route taken from the question. Arrow from bottom is Yes / True, Arrow from side(s) is No / False, (Always label the arrows to make it clear)
documents: Represents a document or report
subroutine: A process that can be used in the current process but defined elsewhere (should have a separate flowchart for it)
annotation: Additional info about a step; the line connecting to the step can be solid or dashed
on-page connector: Replaces long or confusing lines, use a letter to reference
off-page connector: To connect this process to the next step, which is on another page; use page number for reference
database:Data represented by a cylinder (originally representative of disk drive)


- your function is not working, create a flowchart of how it currently is. then walk through it with example input.
- a helpful tool is draw.io.
## resources
### how to think like a programmer
communicate with your machine, conveying your idea and solution. break down the problem.
build it by talking to the problem out loud. collaborate. one step at a time, think from a high level, break it down then use your foundation to crack it. if stuck, imagine a simpler problem you can solve then proceed from there.
documentation is recipes, debugging helps, don't blame the computer.
### what is pseudocode
syntactic code, use your english to write the logic. helps focus on logic instead of syntax.
easier to capitalize commands, write one statement per line, use identations, be specific, keep it simple.
write pseudo as comments then fill under each line translating into code.
### what is an algorithm
set of instruction on how to solve problems
### how to write pseudocode
arrange sequence of tasks and write accordingly
start with statement of main goal or aim of code
indent like code
use the programming structures as used in programming
### examples
Pseudo code 
Pseudo code can be broken down into five components.  
• Variables: 
• Assignment: 
• Input/output: 
• Selection: 
• Repetition: 
A variable has a name, a data type, and a value. There is a location in memory associated with each variable. A variable 
can be called anything or be given any name. It is considered good practice to use variable names that are relevant to 
the task at hand. 
Assignment is the physical act of placing a value into a variable. Assignment can be shown using 
set = 5; 
set = num + set; 
The left side is the variable a value is being stored in and the right side is where the variable is being accessed. When a 
variable is assigned a value, the old value is written over with the new value so the old value is gone. x = 5 does not 
mean that x is equal to 5; it means set the variable x to have the value 5. Give x the value 5, make x equal to 5. 
Input / Output both deal with an outside source (can be  a user or another program) receiving or giving information. An 
example would be assuming a fast food restaurant is a program. A driver (user) would submit their order for a burger 
and fries (input), they would then drive to the side window and pick up their ordered meal (output.) 
• Output – Write / display / print 
• Input – Read / get / input 
Selection construct allows for a choice between performing an action and skipping it. It is our conditional statements. 
Selection statements are written as such: 
if ( conditional statement) 
statement list 
else 
statement list 
Repetition is a construct that allows instructions to be executed multiple times (IE repeated). 
In a repetition problem – Count is initialized – Tested – incremented 
Repetition problems are shown as: 
while ( condition statement) 
statement list 


## TASKS

0.calculate the sum of squares of given input of numbers
//declare s array of input, n to count number inputted, and c to count sum of squares and repeat untill null input
- int s[], c = 0, n = 0;
-  get s[];
//repeat untill null input,
- while s[0] != null
-	c = c + s[n] ** 2;
-	n++;
- print "%c"

1. reads in three numbers and writes them all in sorted order
- Done in collection

2. Calculate a running sum
- done in collection

