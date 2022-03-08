Use `Hello, World` to write a script that prints "Hello, World", followed by a new line to the standard output.

Use `cat /etc/passwd` to display the content of the /etc/passwd file

Use `cat /etc/passwd /etc/hosts` display content of /etc/passwd and /etc/hosts

Use `tail /etc/passwd` to display the last 10 lines of /etc/passwd

Use `head /etc/passwd` to display the first 10 lines of /etc/passwd

Use `head -3 iacta | tail -1` to write a script that displays the third line of the file iacta

Use `"Best School"` > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'` to write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)

Use `ls -la > ls_cwd_content` to write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Use `tail -1 iacta >> iacta` to write a script that duplicates the last line of the file iacta

Use `find . -name '*.js' -type f -delete

Use `find . -tpye d -not -name '.' | wc -1` to write a script that counts the number of directories and sub-directories in the current directory

Use `ls -t | head` to create a script that displays the 10 newest files in the curent directory

Use `sort | uniq -u` to create a script that takes a list of words as input and prints only words that appear exactly once

Use `grep "root" /etc/passwd` to display lines containing the pattern "root" from the file /etc/passwd

Use `grep bin /etc/passwd | wc -l` to display the number of lines that contains the pattern bin the/etc/passwd

Use `grep -A 3 root /etc/passwd` to display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd

Use `grep -v bin /etc/passwd` to display all the lines in the file /etc/passwd that do not contain the pattern bin

Use `grep -i ^[a-z] /etc/ssh/sshd_config` to display all lines of the file /etc/ssh/sshd_config starting with a letter

Use `tr "AC" "Ze" to replace all characters A and c from input to Z and e respectively.

Use `tr -d [cC] to create a script that removes all letters c and C from input

Use `rev` to write a script that reverse its iput.

Use `cut -d":" -f 1,6 /etc/passwd | sort` to write a script that displays all users and their home directories, sorted by users

Use `find . -emptyu -printf "%f\n"` to write a command that finds all empty files and directories in the current directory and all sub-directories

Use `find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL= sort -f` to write a script that lists all the files with a .gif extention in the current directory and all its sub-directories

Use `cut -c 1 | paste -s -d ''` to create a script that decodes the acrostics that use the first letter of each line 
