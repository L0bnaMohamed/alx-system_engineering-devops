1)echo "Hello, World" >> prints “Hello, World”, followed by a new line to the standard output.
2)echo "\"(Ôo)'" >> displays a confused smiley "(Ôo)'.
3)cat /etc/passwd >> Display the content of the /etc/passwd file.
4)cat /etc/passwd /etc/hosts >> Display the content of /etc/passwd and /etc/hosts
5)tail /etc/passwd >> Display the last 10 lines of /etc/passwd
6)head /etc/passwd >> Display the first 10 lines of /etc/passwd
7)head -n 3 iacta | tail -n 1 >>  displays the third line of the file iacta
8)echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) >> creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
9)ls -la > ls_cwd_content >> writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
10)tail -1 iacta >> iacta >>  duplicates the last line of the file iacta
11)find . -type f -name "*.js" -delete >>  deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
12)find . -type d -not -name '.' | wc -l >>  counts the number of directories and sub-directories in the current directory.The current and parent directories should not be taken into account,Hidden directories should be counted.
13)ls -t1 | head -10 >> displays the 10 newest files in the current directory.Requirements:One file per line,Sorted from the newest to the oldest.
14)sort | uniq -u >> takes a list of words as input and prints only words that appear exactly once.
15)grep bin /etc/passwd | wc -l >> Display lines containing the pattern “root” from the file /etc/passwd
16)grep bin /etc/passwd | wc -l >> Display the number of lines that contain the pattern “bin” in the file /etc/passwd.
17)grep -i "root" -A 3 /etc/passwd >> Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
18)grep -i -v "bin" /etc/passwd >> Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
19)grep -i "^[a-z]" /etc/ssh/sshd_config >> Display all lines of the file /etc/ssh/sshd_config starting with a letter.
20)tr "A" "Z" | tr "c" "e" >> Replace all characters A and c from input to Z and e respectively.
21)tr -d "cC" >> Create a script that removes all letters c and C from input.
22)rev >> Write a script that reverse its input.
23)cut -d ':' -f 1,6 /etc/passwd | sort >> displays all users and their home directories, sorted by users.
