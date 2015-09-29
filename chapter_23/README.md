http://cli.learncodethehardway.org/book/ex23.html
As you'll learn in this chapter, exit will exit your terminal.
Alternative "english" ways of asking for your working directory:




Let's close this terminal and open a new one.

exit 

Can you reload your terminal?
Can you logout?




>What does xargs do?
 
xargs stands for "execute arguments" is applied after a pipe preceding a command
it breaks up the the list of arguments into sublists small enough to be acceptable. 


>What does sudo?

it means super user do 

when it precedes a command so that you can override any 
permissions when you execute the command

intitally it requires a password but after you enter it once you don't need to
enter it again since it remembers your credential at least 5 minutes or so in the
terminal 



> What does chmod do?

This is an abbreviation of change mode. 
With this command you can change the permissions of different files, 
meaning that you can make the read-only, write-only, or execute or
some combinaiton of that for different user groups


>What does chown do ?

This is an abbreviation of change ownership.
 
We can change the owner of strace.log to 'rob' and the group
identifier to 'developers'.
 $ chown rob:developers strace.log

