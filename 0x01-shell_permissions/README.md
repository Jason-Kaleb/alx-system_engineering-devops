This is a new directory for shell_permissions.
Explanation for each script down below.
0-iam_betty
-->changes the current user to someone else in this case it is betty
1-who_am_i
-->prints the username of the current user
2-groups
-->prints all the groups that the current user is in
3-new_owner
-->chnages the owner of a file to someone else in this case it is betty
4-empty
-->creates an empty file called hello
5-execute
-->adds execute permission to the owner of the file hello
6-multiple_permissions
-->adds execute permissions to the owneer and group owner and read permission to other users to the file hello
7-everybody
-->adds execution permission to everybody
8-James_Bond
--> No one has permission to do anything besides other users who can read,write and execute
9-John_Doe
--> a script where owner has permission to read,write and execute,but group owner can only read and execute but not write and other users can write and execute
10-mirror_permissions
--> this script mirrors the permissions of one file to another
11-directories_permissions
--> this script addds execute permission to all subdirectories of the current directory.
12-directory_permissions
--> creates a directory with permissions 751 in the working directory
13-change_group
--> changes the group owner for a file
100-change_owner_and_group
--> changes the owner and group of all files in the working directory
101-symbolic_link_permissions
--> changes owner and group owner of a symbolink 
