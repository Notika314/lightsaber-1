# UNIX COMMANDS
     
## PRINTENV
  
The printenv command lists a number of environment variables .

 If you type printenv "env-variable-name" , the path for that variable will be printed out, like: 
 
 printenv HOME  - display the location of the current user's home directory
 
## EXPORT :
 
 You can add a new environment variable with export command: 
 
<addr>$ export MYAPP=1
 
 Then you can check if the var was set properly with "$ echo $MYAPP "
 
 Also it's possible to append value to existent variable, like :
 
##### $ export PATH=$PATH:/home/himanshu/practice/
 
##ARGV

are command-line arguments . The are passed to program by the shell. 
 
## ENVIRONMENT VARIABLES. 

All the variables that we see entering printenv. Some of them are : SHELL, PATH, USER.
