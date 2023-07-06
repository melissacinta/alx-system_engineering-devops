# Shell Permissions

## Task One: switch to betty

The command for this task is ```su betty ``` it tells the shell to switch the current user to betty provided we have adequate permissions.

## Task Two: Who am I

The command for this task is ```whoami ``` , it prints out the current user

## Task Three: Groups:

The command for this task is ```groups ```, this command prints out the group of the current user if no other arguement is passed, else it would print the groups for the specified user or process

## Task Four: New owner

This command ```chown betty ./hello ``` changes the owner of the file hello to the user betty.

## Task Five: Empty

This command ```touch hello ``` creates an empty file called hello

## Task Six: Execute

```chmod u+x ``` A command to add execute permission to the owner of the file hello

## Task Seven: Multiple permissions

```chmod 754 ./hello``` A command to add execute permission to the owner and the group owner, and read permission to other users, to the file hello

## Task Eight: Everybody!

```chmod ugo+x ./hello``` A command to add execute permission to the owner and the group owner, and read permission to other users, to the file hello

## Task Nine: James Bond

the command ```chmod 007 ./hello ``` sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions

## Task Ten: John Doe

the command ```chmod 753 ./hello ``` sets the mode of the file hello to this:

```-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```

## Task Eleven: Look in the Mirror

```chmod --reference=olleh hello ``` this command mirrors permisions of the reference file

## Task Twelve: Directories
 
```find . -type d -exec chmod ugo+rx {} + ``` set the execute permissions for subdirectories of current directory no files are touched


## Task Thirteen: More Directories

the command ```mkdir -m 751 my_dir ``` creates a dir called ```my_dir``` with the 751 permission set to it


## Task Fourteen:change group

the command ```chgrp school hello``` changes the group owner of the file hello to school

## Task Fifteen: change group and owner

```chown -R vincent:staff . ``` changes the group and user ownership of file and diresctories


## Task Sixteen: symbolic links

```chown -h vincent:staff _hello``` is used to change the user and  group ownership of the symbolic ```link _hello```


## Task Seventeen: If Only

```chown -h -R --from=guillaume betty ./hello ``` is used to change ownership of hello to betty if only the prev owner is guillaume


## Task Eighteen: Star Wars

```telnet towel.blinkenlights.nl ``` plays star ways on the terminal but you have to make sure you have star wars installed


