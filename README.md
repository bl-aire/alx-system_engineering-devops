## alx-system_engineering-devops
This is an introductory course to Shell basics.

### Shell_basics
The list below shows what each script does:

0. Current_working_directory: Prints the current directory a user is on.
1. Listit: Lists the files in the current working directory.
2. Bring_me_home: Changes the working directory to the user’s home directory.
3. Listfiles: Displays current directory contents in a long format.
4. Listmorefiles: Displays current directory contents, including hidden files (starting with .)
5. Listfilesdigitonly: lists the content of the current directory (including hidden files) numerically.
6. Firstdirectory: Creates a new directory in /tmp/.
7. Movethatfile: Moves the file betty from /tmp/ to /tmp/my_first_directory.
8. Firstdelete: Deletes the file betty
9. Firstdirdelete: Deletes the directory my_first_directory that is in the /tmp directory.
10. Back: changes the working directory to the previous one.
11. Lists: Lists files in current directory, parent directory and /boot
12. File_type: Prints the type of the file.
13. Symbolic_link: creates a symbolic link to bin/ls.
14. Copy_html: Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
15. Lets_move: Moves all files beginning with an uppercase letter to the directory /tmp/u.
16. Clean Emacs: Deletes all files in the current working directory that end with the character ~.
17. Tree: Creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
 18. Commas: Lists all the files and directories of the current directory, separated by commas (,).
19. School.mgc: Contains a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.


### Shell Permissions


The list below shows what each script does:

0-iam_betty: Switches the current user to the user betty.

1-who_am_i:  Prints the effective username of the current user.

2-groups: Prints all the groups the current user is part of.

3-new_owner: Changes the owner of the file hello to the user betty.

4-empty: Creates an empty file called hello.

5-execute: Adds execute permission to the owner of the file hello.

6-multiple_permissions: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7-everybody: Adds execution permission to the owner, the group owner and the other users, to the file hello.

8-James_Bond: Sets the permission to the file hello as follows:

-Owner: no permission at all
-Group: no permission at all
-Other users: all the permissions

9-John_Doe:  sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.

10-mirror_permissions: Sets the mode of the file hello the same as olleh’s mode.

11-directories_permissions:  Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

12-directory_permissions:  Creates a directory called my_dir with permissions 751 in the working directory.

13-change_group: Changes the group owner to school for the file hello.

100-change_owner_and_group:  Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

101-symbolic_link_permissions:  Changes the owner and the group owner of _hello to vincent and staff respectively.

102-if_only: Changes the owner of the file hello to betty only if it is owned by the user guillaume.

103-Star_Wars: Plays the StarWars IV episode in the terminal.
