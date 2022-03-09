Use `alias ls="rm *"` to create a script that creates an alias.

Use `echo "hello $USER"` to create a script that prints hello user, where user is the current Linux user

Use `export PATH=$PATH:/action` to Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program

Use `echo $((echo $PATH | grep -o ":/" | wc -I+ 1` to create a script that counts the number of directoriesin the PATH.

Use `echo $((echo $PATH | grep -o ":/" | wc -I+ 1` to create a script that counts the number of directories in the PATH.
