# terminal-exercises

//Answers are written in parentheses ()

**Part I**
1. make a directory called ***first***  (mkdir first)
2. change directory to the ***first*** folder (cd first) 
3. create a file called ***person.txt*** (touch person.txt)
4. change the name of ***person.txt*** to *another.txt* (mv person.txt another.txt)
5. make a copy of the ***another.txt*** file and call it ***copy.txt*** (cp another.txt copy.txt)
6. remove the ***copy.txt*** file (rm copy.txt)
7. make a copy of the ***first*** folder and call it *second* (cp -r first second)
8. delete the ***second*** folder (rm -rf second) //had to use flag because of file inside//

**Part II**
1. What does the ***man*** command do? Type in ***man rm***. How do you scroll and get out?  (man brings up the manual and "q" quits out of it)
2. Look at the ***man*** page for ***ls***. What does the ***-l*** flag do? What does the ***-a*** flag do? (-l uses a long listing format, -a brings up "all" files including hidden ones)
3. How do you jump between words in the terminal?   (alt + left/right)
4. How do you get to the end of a line in terminal?  (ctrl + e)
5. How do you move your cursor to the beginning in terminal?  (ctrl + a)
6. How do you delete a word (without pressing backspace multiple times) in terminal?      (ctrl + w)
7. What is the difference between a terminal and shell?           (terminal is the window you type in commands, the shell is the program itself that processes the commands)
8. What is an absolute path?                   ( it starts with a forward slash / and shows the full path to a file starting from the root directory)
9. What is an relative path?                   (this does not start with a forward slash/ and starts from the current directory and not from the root)
10. What is a flag? Give three examples of flags you have used.                     ( a flag is an added option to a command that changes the commands behavior. 3 examples are -a used with ls to show hidden files, -l used with ls for long format, and another example is -f that list all the entries in directory order)
11. What do the ***r*** and ***f*** flags do with the *rm* command?  (-rf deletes folders that have existing files within them) 
