http://cli.learncodethehardway.org/book/ex18.html

As you'll learn in this chapter, grep allows you to search files for strings.

Alternative english ways of asking you to search files:

>Show me the lines in foo.txt that have ERROR in them.


grenadine:tmp $ grep "ERROR" foo.txt

ERROR
ERROR: You're running out of bath salts
ERROR: The store is closed tonight
ERROR: You've found Riley Jones



>Show me the lines in bar.txt that have davinci in them.

grenadine:tmp $ grep "davinci" bar.txt

I'ma gonna be a davinci coder
Coding my davinci code bro.


>Can you print all the lines in text files that 
>have your first and last name in them?

grenadine:tmp $ grep "Riley Jones" bar.txt foo.txt

bar.txt:Run away from Riley Jones, quick!
foo.txt:ERROR: You've found Riley Jones


> What does the -i do in grep -i "*" file.txt?
It has the effect that the search is not CASE sensitive. 
