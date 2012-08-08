AnimationVisitor
	- Interprets the brainfuck code.
	- Displays the contents of each cell of the 30000 byte array as they change.
	- Highlights cells as they are selected.

CSharpVisitor
	- Creates C# programs of the brainfuck code in the base directory.

InterpreterVisitor
	- Interprets the brainfuck code.
	
JavaVisitor
	- Creates java programs of the brainfuck code in the base directory.
	
OptimizationVisitor
	- Optimizes repeated actions in brainfuck code into repetitions.
	- i.e.: ---- becomes 4-
	
PrintVisitor
	- Creates a .bf file out of the hardcoded brainfuck code.