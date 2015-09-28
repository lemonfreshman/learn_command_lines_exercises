http://cli.learncodethehardway.org/book/ex15.html
As you'll learn in this chapter, pipes allow you to run the output of one command into the input of a second command. Redirection allows you to redirect the output from a command to somewhere else.


Alternative "english" ways of asking for pipes and redirection:



> Can you put "This class is fun" into bar.txt?

echo "This class is fun" > bar.txt
cat bar.txt | less




>Can you put "Oh so much fun" into foo.txt?

echo "Oh so much fun" > foo.txt


> What does | or bar do? 

There must be a command on both sides to use this. 
the output of left command is fed into the command on the right


> What does > redirect do?

There must be a command on the left side. There must be a file on the right.
The output of the command is written to the file on the right. 



> What does < redirect do?
This sends the info of the file on the right to a command on the left side.


> What does >> do?

It works the same as > except that it adds info instead 
of overwriting it like > does. 
