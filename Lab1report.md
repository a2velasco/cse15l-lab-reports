# CSE 15L Lab Report 1
## 1. cd with no arguments
```
[user@sahara ~]$ cd
[user@sahara ~]$ 
```
The working directory was /home when the command was run. 
There was no output because an argument was not given to change the directory, so it automatically takes you to /home.
The output was not an error.
## 2. cd with path to directory
```
[user@sahara ~]$ cd lecture1/
[user@sahara ~/lecture1]$
```
The working directory was /home when the command was run. 
There was no output but we see the prompt has changed. The output was not an error.
## 3. cd with path to file
```
[user@sahara ~]$ cd lecture1/messages/es-mx.txt 
bash: cd: lecture1/messages/es-mx.txt: Not a directory
```
The working directory was /home when the command was run. 
The reason I got this output is because I gave an invalid argument to the cd command.
The output is an error because I gave the command an invalid argument. It is an error because
the command change directory needs a directory to change to, and a file is not a directory.
## 4. ls with no arguments
```
[user@sahara ~]$ ls
lecture1
```
The working directory was /home when the command was run.
The reason I got this output is because the command ls lists files in the current directory and lecture 1 was the only file in /home.
The output is not an error and the command worked correctly.
## 5. ls with path to directory
```
[user@sahara ~]$ ls lecture1/
Hello.class  Hello.java  messages  README
```
The working directory was /home when the command was run. The reason I got this output was because I used the list files command with a directory argument whicb
will list all files and directories. The output was not an error and the command worked correctly.
## 6. ls with path to file
```
[user@sahara ~]$ ls lecture1/messages/es-mx.txt 
lecture1/messages/es-mx.txt
```
The working directory was /home when the command was run. The reason I got this output is because I used a command to list files from a directory with a file argument.
Instead it listed the path to the file I tried to use ls on. The output is not an error because it does say what the error was. 
## 7. cat with no arguments
```
[user@sahara ~]$ cat
hello
hello
what
what
```
The working directory was /home when the command was run. The reason I got this output is because cat with no argument begins to read input and print it to output.
The output is not an error and the command worked as intended with no arguments.
## 8. cat with path to directory
```
[user@sahara ~]$ cat lecture1/
cat: lecture1/: Is a directory
```
The working directory was /home when the command was run. The reason I got this output is because I gave the command cat an invalid argument.
The output is an error because it explains why the command did not work since cat needs files as arguments and does not take directories.
## 9. cat with path to file
```
[user@sahara ~]$ cat lecture1/messages/es-mx.txt 
¡Hola Mundo!
```
The working directory was /home when the command was run. The reason I got this output is because cat prints the contents of a file to the terminal.
So cat accepted the path as an argument and printed the file's contents to the terminal. The output is not an error and the command worked correctly.

