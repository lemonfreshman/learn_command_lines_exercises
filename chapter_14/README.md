http://cli.learncodethehardway.org/book/ex14.html
As you'll learn in this chapter, rm (remove) simply removes a file.
Alternative english ways of asking for your working directory:



>Can you remove blah.txt?

touch blah.txt
blah.txt
rm blah.txt
ls 
foo development.log


>Let's get rid of our development log file.

touch development.log 
development.log
rm development.log
ls 
foo

>Can you remove everything in the slash temp slash foo directory?

Yes, but you have to run 

rm -rf /tmp/foo

Which we don't want to do generally because you run the risk 
of deleting things you didn't mean to delete.

For example like accidentally running sudo rm -rf / which would remove pretty much everything and mess up our computer. 

