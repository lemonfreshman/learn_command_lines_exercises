http://cli.learncodethehardway.org/book/ex11.html
As you'll learn in this chapter, mv (move) allows you to move 
files from one location to another.


>Alternative "english" ways of asking for your working directory:

>Can you rename foo.txt to blah.txt?

Yes. 

touch foo.txt
mv foo.txt blah.txt
ls
blah.txt

>Can you move the production.log file in the log directory to slash temp?

Yes. 

mkdir tmp
mkdir log 
cd log
echo "this is the content of production.log" > production.log
mv production.log ../tmp
cd ..
cat tmp/production.log
this is the content of production.log

