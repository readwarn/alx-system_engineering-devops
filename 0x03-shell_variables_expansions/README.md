
alias ls='rm *' - creates an alias
echo hello $USER - prints hello user, where user is the current Linux user
export PATH=$PATH:/action - Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
echo $PATH | tr : "\n" | wc -l - counts the number of directories in the PATH.
printenv | less - lists environment variables.
set | less -  lists all local variables and environment variables, and functions.
export BEST=School - creates a new local variable.
export BEST=School - creates a new global variable.
echo $((128+$TRUEKNOWLEDGE)) - prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER/$DIVIDE)) - prints the result of POWER divided by DIVIDE, followed by a new line
echo $(($BREATH**$LOVE)) - displays the result of BREATH to the power LOVE
echo $((2#$BINARY)) - converts a number from base 2 to base 10.
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" - prints all possible combinations of two letters, except oo.
printf "0.00\n" $NUM - prints a number with two decimal places, followed by a new line.
