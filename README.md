# Kondor
This Repository holds a simple task tracker that will accept tasks and let you view them.

"mv todo todo.py"

this is mistake on my part and I am currently working towards a fix.

Installation:

Create a file in your home directory ".todo_tasks.txt" This will be hidden, but makes the tasks persist when the terminal is closed/process is ended.

Git clone (this repo)

cd Todobird

ls

"README.md  todo"(SEE NOTE BELOW)

chmod +x todo.py

sudo mv todo.py /usr/local/bin/todo

Thats it! to use your tool:

$todo [command]
add
delete
view
exit

ex:
$todo add "This is a task"
$todo view 
1. This is a task
todo delete 1

NOTE:
*when you first download the repository with "git clone" the repository will be "Todobird"
when you "cd" into the repository, it will have this README.md and a file called "todo"
This file needs to be changed to a python readable format, i.e:

"mv todo todo.py"



