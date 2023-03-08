README.md file
pwd print working directory
ls list directory content
cd ~ go to the home
ls -l Display current directory contents in a long format
ls -al Display current directory contents, including hidden files (starting with .). Use the long format.
ls -al Display current directory contents.Long format,with user and group IDs displayed numerically,And hidden files (starting with .)  
mkdir /tmp/my_first_directory/ Create a script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/betty Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty Delete the file betty.The file betty is in /tmp/my_first_directory
rm -rf /tmp/my_first_directory Delete the directory my_first_directory that is in the /tmp directory."by force".
cd - or cd .. changes the working directory to the previous one.
ls -la . .. /boot lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls __ls__ Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in thecurrent working directory.
cp -u *.htm .. Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.You can consider that all HTML files have the extension .html
