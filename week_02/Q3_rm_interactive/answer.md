The rm command is used to delete files and directories in Linux.

The -i option makes it interactive, meaning it will ask for confirmation before deleting each file.

How it works:

When you run rm -i on one or more files:

rm -i file1.txt file2.txt

Linux will prompt you for each file:

rm: remove regular file 'file1.txt'? y/n
rm: remove regular file 'file2.txt'? y/n

You must type:

y → Yes, delete the file

n → No, keep the file
