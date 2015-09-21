http://cli.learncodethehardway.org/book/ex7.html
As you'll learn in this chapter, rmdir (remove directory) removes directories.
Alternative "english" ways of asking you to delete a directory:


Can you remove the tmp directory?

rmdir tmp
rmdir: tmp: Directory not empty

Let's remove the tmp directory.


cd tmp
ls 
stuff 

rmdir stuff 
rmdir: stuff: Directory not empty
cd stuff
ls
things

rmdir things
rmdir: things: Directory not empty 
cd things
ls
frank

rmdir frank
cd ..
rmdir things
cd ..
rmdir stuff
cd ..
rmdir tmp

1. Make 20 more directories and remove them all.
mkdir Berlin
rmdir Berlin

mkdir Africa
rmdir Africa 

mkdir A B C D E F G H I J K 
rmdir A B C D E F G H I J K 

mkdir russia
mkdir china
mkdir russia/doll

ls russia 
doll
rmdir russia/doll
rmdir russia

mkdir china/plate 
rmdir china/plate
rmdir china

mkdir 1 2 3 4 5 
rmdir 1 2 3 4 5 



2. 
Make a single path of directories that is 10 deep and remove them one at a 
time just like I did above.

mkdir 1
mkdir 1/2
mkdir 1/2/3
....
mkdir 1/2/3/4/5/6/7/8/9/10

cd 1/2/3/4/5/6/7/8/9
rmdir 1/2/3/4/5/6/7/8/9/10
cd ..
rmdir 1/2/3/4/5/6/7/8/9
cd ..
rmdir 1/2/3/4/5/6/7/8
........

If you try to remove a directory with 
contents you will get an error. I'll show you how to remove these in later exercises.
