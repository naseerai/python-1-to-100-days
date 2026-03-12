12-3-2026

As per the video intro , we are discussing about the comments in the code and Escape Sequence 

Comments will help the viewer or develeoper or ourselfs to understand what was the code about and what is going on 
 and also we have learned about milti line comment 

And also escape sequence which will give you output in the new line 

they are several escape sequence are there 

Common Escape Sequences
The table below lists the most frequently used escape sequences in Python: 
Escape Sequence 	Description	Example
\'	Single Quote	'It\'s a sunny day!'
\"	Double Quote	"He said, \"Hello!\""
\\	Backslash	"This is a backslash: \\"
\n	New Line (Line Feed)	"Line 1\nLine 2"
\t	Tab (Horizontal Tab)	"First\tSecond"
\b	Backspace	"Helloo\b" outputs "Hello"
\r	Carriage Return	"Hello\rWorld" outputs "World" (overwrites "Hello")
\f	Form Feed	"Hello\fWorld"
\a	ASCII Bell (Alert)	print("\a") (makes a sound)
\xhh	Character with hex value hh	print("\x48\x65\x6c\x6c\x6f") outputs "Hello"
\ooo	Character with octal value ooo	print("\110\145\154\154\157") outputs "Hello"
\uXXXX	Unicode character with 16-bit hex value XXXX	print("\u0048") outputs "H"
\UXXXXXXXX	Unicode character with 32-bit hex value XXXXXXXX	print("\U0001F600") outputs "😀"