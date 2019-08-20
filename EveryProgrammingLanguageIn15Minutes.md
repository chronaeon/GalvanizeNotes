# Every programming language in 15 minutes

### All programming languages have some things in common
	- Input (most programs) e.g..
		- write data to a file
		- send data over a network
		- send data to a screen for display
		- send data to an audio device for playback
	- Output (all programs) e.g..
		- read data from a file
		- receive data over a network
		- receive data from a hardware device (mouse, keyboard, et al.)
### Data comes as one of four:
	1. Numbers (integers, real numbers, et al.)
	2. Strings (sequences of text characters)
	3. Booleans (T/F)
	4. Collections (Values made up of multiple other values)
### Every programming language has:
	- bult-in operations
	- variables
	- branching (if statements)
	- Looping (while/for statements)
	- Functions (programmer-defined operations)
### Operations
	- arithmetic (~4)
	- logic operations
	- String joins
	- String splits
	- take input values (usually two) and return an output value
	- operations tend to generate new values rather than mutating existing values
	- Returned values materialize as one of the four types of data mentioned above
### Variables
	- a named location in memory which stores a value
	- an assignment that overwrites the value already stored in the variable with a new value
	- you can mix and match variable values with each other
	- these differ from variables in Math (storage locations in memory, store a single value, but the value can change)
### Branching
	- if statements
		- if condition x is true, then execute body y
		- (implicit: if condition x is not true, then skip over body y)
### Looping 
	- while statements
		- executes the body if the condition is true
		- the condition is automatically evaluated each time the body is executed
		- only when the execution tests false does it skip
		- infinite loops are possible if the condition never becomes false
		- loops and ifs can be nested to arbitrarily deep levels
### Functions
	- has a name and a body of statements
	- called by the name
	- may return an output value, or may not
	- may accept arguments (inputs) known as parameter variables
	- functions allow you to make your own operations, extending any operations
	- a program is a set of functions
	- functions enclose/isolate variables from other functions
	- functions take execution precedence
### System Calls
	- Capabilities exposed by the operating system for program management and input/output
	- Invoked by special hardware mechanism (particular CPU instructions)
		- can invoke system calls to do some input/output on behalf of the program
		- e.g. to read/write a file, needs to call the operating system to write the file on its behalf
	- invoked with most languages via specially-implemented functions

