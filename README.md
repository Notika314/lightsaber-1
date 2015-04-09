     UNIX COMMANDS
     
  1.PRINTENV
  
The printenv command lists a number of environment variables .

 If you type printenv "env-variable-name" , the path for that variable will be printed out, like: 
 
 printenv HOME  - display the location of the current user's home directory
 
 2. EXPORT :
 
 You can add a new environment variable with export command: 
 
 $ export MYAPP=1
 
 Then you can check if the var was set properly with "$ echo $MYAPP "
 
 Also it's possible to append value to existent variable, like :
 
 $ export PATH=$PATH:/home/himanshu/practice/
 
    3. ARGV are command-line arguments . The are passed to program by the shell.
