 Use `su betty` to create a sript that switches the current user to the user betty

Use `whoami` to write script that prints the effective username of the current user

Use `groups` to write a script that prints all groups the current user is part of

Use `chown betty` to write a script that changes the owner of the file hello to the user betty

Use `touch hello` to write a script that creates an empty file called hello

Use `chmod u+x hello` to write a script that adds execute permission to the owner of the file hello

Use `chmod ug+x,o+r hello` to write a script that adds execute permission to the owner and the group owner and read permission to other user, to the hello

Use `chmod a+x hello` to write a script that adds execution permission to the owner, the group owner and the users, to the file hello

Use `chmod 007 hello` to write a script that sets the permission to the file hello as Owner, Group and Other user

Use `chmod 753 hello` to write a script that sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 sep 20 14:25 hello

Use `chmod --reference=olleh hello` to write a script that sets the mode of the file hello the same as olleh's mode

Use `chmod --reference=olleh hello` to write a script that sets the mode of the file hello the same as olleh's mode

Use `chmod a+X *` to create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

Use `mkdir -m 751 my_dir` to create a script that creates a directory called my_dir with permissions 751 in the working directory

Use `chgrp school hello` to write a script that changes the group owner to school for the file hello

Use `chown -R vincent:staff ./` to write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory

Use `sudo chown -h vincent:staff_hello` to write a srcipt that changes the owner and the group ownerof hello to vincent and staff respectively.

Use `chown --from=guillaume betty hello` to write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume

Use `telnet towel.blinkenlights.nl` to write a script that will play the starWars IV episode in the terminal

Use `telnet towel.blinkenlights.nl` to write a script that will play the StarWar IV episode in the terminal
