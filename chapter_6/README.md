http://cli.learncodethehardway.org/book/ex6.html
As you'll learn in this chapter, ls (list directory) shows you what files are in your current directory.
Alternative "english" ways of asking for a list of files:

>What's in the tmp directory?

ls tmp
stuff

>Can you show me what files are in that directory?

There's no files in that directory, see. 

cd tmp
ls -lR

total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 stuff

./stuff:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 things

./stuff/things:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 frank

./stuff/things/frank:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 joe

./stuff/things/frank/joe:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 alex

./stuff/things/frank/joe/alex:
total 0
drwxr-xr-x  2 davincicoder  staff  68 Sep 21 03:09 john

./stuff/things/frank/joe/alex/john:



>What files are in your home directory?

ls /users/davincicoder 

Applications Documents    Library      Music        Public       macports
Desktop      Downloads    Movies       Pictures     bash_profile workspace


>What's in slash temp?

ls /tmp 

enadine:chapter_6 davincicoder$ ls /tmp
KSOutOfProcessFetcher.505.I5ci1K_TwCwqo1sKvc0siaBbJTw=
com.apple.launchd.RYBlm4d3cb
com.apple.launchd.leKm0hxuHU

> What does ls -lR do?

It lists all the directories and subdirectories in them including the files in in them.
In other words, it provides an overview of everything that resides inside the current directory. 

>$ls -lR

total 8
-rw-r--r--  1 davincicoder  staff  1334 Oct  9 23:32 README.md
drwxr-xr-x  3 davincicoder  staff   102 Sep 21 03:09 tmp

./tmp:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 stuff

./tmp/stuff:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 things

./tmp/stuff/things:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 frank

./tmp/stuff/things/frank:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 joe

./tmp/stuff/things/frank/joe:
total 0
drwxr-xr-x  3 davincicoder  staff  102 Sep 21 03:09 alex

./tmp/stuff/things/frank/joe/alex:
total 0
drwxr-xr-x  2 davincicoder  staff  68 Sep 21 03:09 john

./tmp/stuff/things/frank/joe/alex/john:
