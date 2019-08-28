Command Line App - To Do List App

User: General Public // Devs


Acceptance criteria

In Repl

STEP 1
INPUT: running/starting the repl "ruby todo.rb"  
OUTPUT : The user sees:
list of the ToDos, ordered by date and time, id to access them, text(string)ToDo

Below a prompt "What would you like to do? add / done"


STEP 2
INPUT: command add

add string --> adds to the list

OUTPUT: User sees the list of the ToDos once again

User see the prompt again: "What would you like to do? add / done"

id and date are added from the system, not by the user

STEP 3
either repeat STEP 2

INPUT: command DONE
OUTPUT: done id of the ToDo --> removes the ToDo

Edge cases //

if other than command add or command done --> prompt loops no error thrown

INPUT exit - OUTPUT: stops the program

TECH: Ruby; TDD: Rspec
Git and GitHub
