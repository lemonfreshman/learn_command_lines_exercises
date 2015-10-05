http://cli.learncodethehardway.org/book/ex9.html
As you'll learn in this chapter, touch (touch/create empty file) will 
create a new empty file. Windows power shell does not have this command so the New-Item command is used.
Alternative "english" ways of asking you to create a file:



>Can you touch blah.txt?

Yes. 

touch blah.txt
ls 
blah.txt



>Let's create foo.txt.

touch foo.txt
ls 
foo.txt


>Unix: Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

mkdir newdirectory
cd newdirectory
touch newfile.file
cd ..
rmdir newdirectory/
rmdir: newdirectory/: Directory not empty

The directory isn't empty. This is a safeguard against
deleting directories with files in them, potentially
losing a lot of data accidentally. 
