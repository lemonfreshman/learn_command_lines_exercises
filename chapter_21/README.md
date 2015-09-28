http://cli.learncodethehardway.org/book/ex21.html

As you'll learn in this chapter, env (environment) shows you what environment variables you have defined.

Alternative "english" ways of asking about your environment:





>What is your shell set to?

$ env 
SHELL=/bin/bash


>What directory are you in (don't use pwd this time)?

$ env
PWD=/Users/davincicoder/workspace/davinci_coders_t3_2015/homework
/learn_command_lines_exercises/chapter_20

>What is your home directory set to?

$ env
HOME=/Users/davincicoder

Can you set your environment to have DEBUG set to true?

$ export DEBUG=true
$env
DEBUG=true


> How do you change your PATH? 

$PATH=/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin:/usr/local/mysql/bin

