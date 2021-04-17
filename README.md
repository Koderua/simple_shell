
Simple Shell

**NAME**

hsh - Alx Holberton Simple Shell command interpreter (shell)


**SYNOPSIS**

**./hsh**

[command] [arguments ...]



**DESCRIPTION**

The **hsh** (Simple Shell) is an end of the trimester project for students at  Alx. The objective is to  write
a simple UNIX command interpreter that acts closely to **sh**



**Overview**

A  shell  is a command-line interpreter that provides a command line user

interface. The first argument at argument [0] is under‐stood by the shell to be a command. The shell will then run  that  com‐

mand  if  it  can be found and arguments after the first are treated as

modifiers or options.


## To Compile

    gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

## Built-ins

 1. cd - changes current directory of the process.

 Syntax : `cd [DIRECTORY]`

 2. exit - to exit from the shell you type exit and press ENTER.

 3. env - prints the environment

Users type commands which get executed within the session.

###### Example:
~~~~
$pwd - to print working directory
$cd .. - to change direcory to previous directory
$echo - to print to standard output
$cat - to read a file's content

~~~~

## Authors

Contributors to the Alx Shell project

 - [Kibirt B Chane](https://github.com/Koderua) email: kibirtbayou@yahoo.com
 - [Christian Nshimyumukiza](https://github.com/Crispy-rw) email: nshimyumukizachristian@gmail.com
