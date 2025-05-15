# pseudo-code collection
this is a collection of my pseudocode, coding and problem solving knowledge and practice.
# How to pseudo code
- it contains 5 components:
	1. variables: has a name, data type, and a value. there is a location in memory associated with each variable. it can be anything, given any name, it is good practiceto give names relevant to the task at hand.
	2. assignement: the physical act of placing a value into a variable using this format set = 5; set = num + set;.where the left side is a variable the value is being stored at, and the right side is where the variable is being accessed. when the variableis assigned a value, the old balue is written over with the new value so the old value is gone. x = 6 does not mean x is equal to five; it means set the variable x to hav the value 5.
	3. input/output: both deal with outside source (user or program) to recieve or give information.
		- output: write/display/print
		- input: Read/ get/ input
	4. selection: allows for choice between performing an action or skipping it. it is our conditional statement. written as. 
		if(conditional statement)
			statement list
		else
			statement list
	5. Repitition: allows instruction to be executed multiple of times. in a repetition preblem count is initialized, Tested, encremented. and is shown as.
		while (conditional statement)
			statement list
> i found better, I will write comment style logic statement then put code blocks under them. statement contain logic and keywords using the 5 components above, as well as stages of code, with intro giving full sequence then, code block or structure dpecific purpose. started using in example 7 and 8.
> arrange sequence of tasks and write accordingly
start with statement of main goal or aim of code
indent like code
use the programming structures as used in programming

# Examples (write a pseudocode that)
1. reads two numbers that multiplies them together and print out their product
- int x, y, r;
- get x, y;
- set r = y * x;
- print r;
2. tells a user that the number they entered is not a 5 or a 6.
- int x;
- get x;
- if x != 5 & x != 6
	print " the number you entered is not a 5 or a 6";
else if x = 5 OR x = 6
	print " the number you entered is %x";
3. ask a user a number, if it is between 0 and 10, write red, if between 10 and 20 write bleu, if between 20 and 30 write green. if any other number write it is not a color option.
- int x;
- get x;
- if x >= 0 & x <= 10
	print "Red";
else if x > 10 & x <= 20
	print "Bleu";
else if x > 20 & x <= 30
	print "Green";
else
	print "the number you entered is not a color option"
4. print all multiplies of 5 between 1 and 100 (both included).
- int x = 1;
- while x <= 100
-	if x%5 = 0
		print x;
-	x++;
// faster this way
- int x = 1;
- while x <= 20
-	x = x * 5;
- 	print "%x";
5. count even numbers up to a user defined stopping point.
- int x, c = 0;
- get x;
- while c <= x
	if c % 2 != 0
		print c;
	c++;
// faster to keep c even by adding 2 each time to even
6. a) read 5 separate numbers b) calculate the average of them c) find min and max d) write results from b and c while describing what they are.
- int A, B, C, D, E, AVG, MIN, MAX, T;
- get A, B, C, D, E;
// average is sum devided by number of vars summed
- AVG = (A + B + C + D + E)/5;
// find max then challenge it, assume min as shortcut
- IF A > B
	MAX = A;
	MIN = B;
ELSE
	MAX = B;
	MIN = A;
- IF MAX < C
	MAX = C;
- IF MAX < D
	MAX = D;
- IF MAX < E
	MAX = E;
// challenge assumed min by all but itself and max
- IF MIN > C
	MIN = C;
- IF MIN > D
	MIN = D;
- IF MIN > E
	MIN = E;
//output
- the average of the inserted numbers is %AVG, while the smallest number is %MIN, and the largest number is %MAX.

> i think i can work around the repetitive conditional structure with some repetition structure. maybe index the numbers.
7. reads 3 numbers and writes them all in sorted order.
//DECLARE AND INPUT
- int A, B, C, T1, T2, T3, t;
- GET A, B, C;
//FIND SMALLEST OF TWO
- IF A < B -	T1 = A;
-	T2 = B;
- ELSE 
-	T1 = B;
-	T2 = A;
//CHALENGE FOR SMALLEST WITH THE THIRD CONDIDATE, and allocate possible biggest
- IF C > T1 
-	T3 = C;
- ELSE
-	T1 = C;
-	T3 = A;
//CHALLENGE BIGGEST, SO THE OTHER IS MIDDLE
- IF T2 > T3
-	t = T3;
- 	T2 = T3;
-	T3 = t;
//OUTPUT
- PRINT "SORTED IN ASCENT: %T1, %T2, %T3"
// or use nested ifs, like first with 1 and 2, then nest it with 2 and 3 else if 3 and 1 else. then else of the first nested twice as first condition and almost copy earlier nestings
// or try all possibilities with if and write the correct condition only.
8. Calculate a running sum. a user will enter numbers that will be added to the sum and when a negative number is encountered, stop adding and write out the final result.

// repeatable input reading and addition, condition number not negative, F for final results, I for input
// declare, assign (get), initial value
- int F = 0;
- int I;
- GET I;
// add, get again, but repeat only if read num is not negative
- WHILE I >= 0
-	F = F + I;
-	GET I;
//output
- PRINT "Final result is %F" 

## collection

0. calculate the sum of squares of given input of numbers
//declare s array of input, n to count number inputted, and c to count sum of squares and repeat untill null input
- int s[], c = 0, n = 0;
-  get s[];
//repeat untill null input,
- while s[0] != null
-	c = c + s[n] ** 2;
-	n++;
- print "%c"


