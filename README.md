# holbertonschool-shell
## permissions

0-iam_betty: switches the current user to betty
1-who_am_i: prints the effective username of the current user
2-groups: prints all the groups the current user is part of
3-new_owner: changes the owner of the file hello to betty
4-empty: creates an empty file called hello
5-execute: adds execute permission to the owner of the file hello
6-multiple_permissions: adds execute permission to owner and group, and read permission to other, on the file hello
7-everybody: adds execute permission to owner, group, and other on the file hello
8-James_Bond: sets the file hello to no permissions for owner and group, all permissions for other
9-John_Doe: sets the file hello to mode 753
10-mirror_permissions: sets the mode of hello to match the mode of olleh
11-directories_permissions: adds execute permission to all subdirectories of the current directory, leaving regular files untouched
12-directory_permissions: creates a directory called my_dir with permissions 751
13-change_group: changes the group owner of the file hello to school
14-change_owner_and_group: changes the owner to vincent and group to staff for all files and directories in the working directory
15-symbolic_link_permissions: changes the owner and group of the symbolic link _hello itself (not its target) to vincent and staff
16-if_only: changes the owner of the file hello to vincent, only if it is currently owned by guillaume
