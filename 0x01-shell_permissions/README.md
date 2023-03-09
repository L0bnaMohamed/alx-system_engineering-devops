readme file
1)su betty > Create a script that switches the current user to the user betty.You should use exactly 8 characters for your command (+1 character for the new line)You can assume that the user betty will exist when we will run your script
2)whoami > prints the effective username of the current user.
3)groups > prints all the groups the current user is part of.
chown betty hello > changes the owner of the file hello to the user betty.
4)touch hello > creates an empty file called hello.
5)chmod u+x hello > adds execute permission to the owner of the file hello.
6)chmod u+x,g+x,o+r hello > adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.The file hello will be in the working directory
7)chmod ugo+x hello > Write a script that adds execution permission to the owner, the group owner and the other users, to the file helloThe file hello will be in the working directoryYou are not allowed to use commas for this script.
8)chmod 007 hello > Write a script that sets the permission to the file hello as follows:Owner: no permission at allGroup: no permission at allOther users: all the permissions,The file hello will be in the working directory You are not allowed to use commas for this script.
9)chmod 753 hello > sets the mode of the file hello to this:-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello,The file hello will be in the working directory,You are not allowed to use commas for this script
10)chmod --reference olleh hello > Write a script that sets the mode of the file hello the same as olleh’s mode.The file hello will be in the working directory,The file olleh will be in the working directory 
11)chmod -R ugo+x */ > adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12)mkdir -m 751 my_dir > creates a directory called my_dir with permissions 751 in the working directory.
13)chgrp school hello > hanges the group owner to school for the file hello,The file hello will be in the working directory
14)chown -hR vincent:staff . > changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15)chown -h vincent:staff _hello > Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.The file _hello is in the working directory,The file _hello is a symbolic link.
16)chown --from=guillaume betty hello > Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.The file hello will be in the working directory
17)telnet towel.blinkenlights.nl > play the StarWars IV episode in the terminal.
