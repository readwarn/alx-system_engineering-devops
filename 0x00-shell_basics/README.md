
pwd - prints the absolute path name of the current working directory

ls - display the contents list of your current directory

cd - go to home directory

ls -l - display current directory contents in a long format

ls -la - list all files (and hidden files) in the current directory in a long format

ls -n -a - display current directory contents (and hidden files) in a long format, with user and group IDs listed numerically

mkdir /tmp/my_first_directory - command to create my_first_directory directory in tmp directory

mv /tmp/betty /tmp/my_first_directory - move file betty from tmp directory to my_firsy_directory

rm /tmp/my_first_directory/betty - delete betty from my_first_directory folder

rm -r /tmp/my_first_directory - delete folder my_first_directory from tmp

cd - - go back to previous directory

ls -l -a . .. /boot - list all files (and hidden) in current directory, parent of current directory and the boot directory

file /tmp/iamafile - prints the type of a file

ln -s /bin/ls ./__ls__ - Create a symbolic link

cp -u ./*.html ../ - copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

mv [[:upper:]]* /tmp/u - moves all files beginning with an uppercase letter to the directory /tmp/u

rm ./*~ - deletes all files in the current working directory that end with the character ~

mkdir -p welcome/to/school - creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory

ls -pma -  lists all the files and directories of the current directory, separated by commas (,).

school.mgc - used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

