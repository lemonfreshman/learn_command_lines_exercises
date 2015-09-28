http://cli.learncodethehardway.org/book/ex17.html

As you'll learn in this chapter, find allows you to find a file by searching for it by name.

Alternative english ways of asking for your working directory:

>Can you show me all the files in slash temp slash foo?

find /tmp/foo -name "*" -print 

tmp/bar.txt
tmp/foo.txt
tmp/hello.txt

>What log files are in your log directory?
find log -name ".log" -print 


log/asdkfsdkj5.log
log/nonsense.log
log/sdfjsdjh.log
log/sdjfhsdj45.log
log/sense.log
