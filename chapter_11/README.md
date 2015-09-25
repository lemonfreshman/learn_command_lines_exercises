http://cli.learncodethehardway.org/book/ex11.html
As you'll learn in this chapter, mv (move) allows you to move 
files from one location to another.


>Alternative "english" ways of asking for your working directory:

>Can you rename foo.txt to blah.txt?

Yes. 

ls 
foo.txt
mv foo.txt blah.txt
ls
blah.txt

>Can you move the production.log file in the log directory to slash temp?

Yes. 

echo "this is the content" > production.log
mkdir temp
production.log mv temp
cd temp
ls 
production.log
cat production.log
this is the content

