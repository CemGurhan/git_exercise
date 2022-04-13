# **My Command CheatSheet**

## Standard commands

|Command|function|
|---|---|
|tab|1 tab autocompletes, 2 tab lists subdirectories/files, 3 tab selects|
|.|This directory|
|..|Directory above this one|
|open file|Opens file with default app for that file|
|ls|Display all files and subdirectories inside of current directory|
|ls -a|Same as ls, but displays hidden files as well (these files are denoted with a ".")|
|ls -l|List in a long format, displays file mode, owner and group name, date and time file was modified, pathname etc.|
|ls -al| List detailed directory but including hidden files|
|rm file |Remove a file|
|rm -r dir|Removes all matching directories, their subdirectories and the files they contain|
|rm -f file|Never prompt before removing file, force delete|
|rm -rf dir| Deletes a directory forcefully|
|rm -i file|Delete a file only when you give confirmation|
|cd|Change Directory|
|cd ..|Go up a directory|
|cd dir|Go down into a directory|
|cd dir x/...|Go to a specific directory|
|cd -|Takes us to our last accessed directory|
|cp file dir| copy a file to a directory (vice versa)|
|cp -r| copy entire directory|
|cp file newFile|Providing a filename in the second path creates a new name for the file as we copy it|
|cp ~/dir x  .|Copy from the directory "dir x" to here "."|
|mv file dir|Move a file to a new directory|
|mv file ..|Move file up a level|
|mv file newFile|Change the name of a file|
|mv file dir/newFile|Move file to new directory and change files name|
|touch file|Create a new file|
|mkdir dir|Create a new directory|
|code file|Opens a file in vscode|

## Git Commands

|Command|Function|
|---|---|
|git init|Create a new git repository|
|git status|Tell you what is happening right now in your repo|
|git add file|Add file to git track|
|git add .|Adds all changes made to track|
|git commit -m""|Create a new commit with a chosen description typed inbetween ""|
|git commit|Opens up vi for you to manually type in your commit message|
|git log|Tracks all git commits|





