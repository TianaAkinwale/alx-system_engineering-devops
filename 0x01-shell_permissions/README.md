A project that includes scripts that contains various shell permissions
Task 0- 'su betty'- A script that switches the current user to the user betty.
Task 1- 'whoami'- A script that prints the effective username of the current user.
Task 2- 'groups'- A script that prints all the groups the current user is part of
Task 3- 'Chown betty hello'- A script that changes the owner of the file hello to the user betty.
Task 4- touch hello'- a script that creates an empty file called hello.
Task 5- chmod u+x hello-  a script that adds execute permission to the owner of the file hello.
Task 6- chmod ug+x,o+r hello- a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
Task 7- chmod a+x hello-a script that adds execution permission to the owner, the group owner and the other users, to the file hello
Task 8-chmod 007 hello-a script that sets the permission to the file hello as follows:, Owner: no permission at all, Group: no permission at all, Other users: all the permissions
Task 9-chmod 753 hello- a script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
Task 10-chmod--reference=olleh hello-a script that sets the mode of the file hello the same as olleh’s mode.
Task 11-chmod a+X-a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Task 12- mkdir -m 751 my_dir-Create a script that creates a directory called my_dir with permissions 751 in the working directory.
Task 13-chgrp school hello- a script that changes the group owner to school for the file hello
Task 14-chown vincent:staff *-a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directoryTask 15-chown -h vincent:staff _hello-a script that changes the owner and the group owner of _hello to vincent and staff respectively.
Task 16-chown --from=guillaume betty hello-Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
Task 17-telnet towel.blinkenlights.nl-a script that will play the StarWars IV episode in the terminal.
