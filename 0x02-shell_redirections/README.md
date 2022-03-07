
echo Hello, World - prints “Hello, World”, followed by a new line to the standard output
echo "\"(Ôo)'" - displays a confused smiley "(Ôo)'
cat /etc/passwd - Display the content of the /etc/passwd file
cat /etc/passwd /etc/hosts - Display the content of /etc/passwd and /etc/hosts
tail /etc/passwd - Display the last 10 lines of /etc/passwd
head /etc/passwd - Display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1 -  displays the third line of the file iacta
ls -la > ls_cwd_content - writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
tail -n 1 iacta >> iacta - duplicates the last line of the file iacta
find . -type f -name "*.js" -delete - deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
find ./* -type d | wc -l - counts the number of directories and sub-directories in the current directory
ls -t -1 | head - displays the 10 newest files in the current directory.
