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

```chmod 751 ./hello``` A command to add execute permission to the owner and the group owner, and read permission to other users, to the file hello


