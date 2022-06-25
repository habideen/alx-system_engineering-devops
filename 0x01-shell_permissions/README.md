# Permissions


Change user `su USE_NAME`



Print current user username `id -un`


Print list of groups of the system `groups`

Change file owner `chown USER_NAME FILE`

Create an empty file `touch FILE_NAME`

Add execution permission to a file `chmod u+x FILE_NAME`

Add multiple permission to a file `chmod u+x,g+x,o+r FILE_NAME` or `chmod 554 FILE_NAME`. the number 554 is equivalent to r-xr-xr--. Please note that  each character represents a bit rwx=7. There are 3 parts in the permission owner;group;others. Full permission is rwxrwxrwx

Give everyone permission to execute `chmod ugo+x FILE_NAME`

Give no permission to owner and group. Give all to other `chmod 007 FILE_NAME`

Give the permission of file A to file B `chmod --reference=A B`




