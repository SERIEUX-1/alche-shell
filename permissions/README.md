# 0x01. Shell, permissions

Shell scripts covering Unix file permissions, ownership, and user/group
management: chmod, chown, chgrp, su, whoami, groups.

## Files

- 0-iam_betty: switches the current user to betty
- 1-who_am_i: prints the effective username
- 2-groups: prints all groups the current user belongs to
- 3-new_owner: changes the owner of hello to betty
- 4-empty: creates an empty file called hello
- 5-execute: adds execute permission to the owner of hello
- 6-multiple_permissions: adds owner/group execute and other read to hello
- 7-everybody: adds execute permission to owner, group, and other on hello
- 8-James_Bond: sets hello to 007 (no perms for owner/group, all for other)
- 9-John_Doe: sets hello mode to 753 (rwxr-x-wx)
- 10-mirror_permissions: copies olleh's mode onto hello
- 11-directories_permissions: adds execute to all subdirectories only
- 12-directory_permissions: creates my_dir with mode 751
- 13-change_group: changes hello's group to school
- 14-change_owner_and_group: changes owner/group of everything to vincent:staff
- 15-symbolic_link_permissions: changes owner/group of the _hello symlink itself
- 16-if_only: changes hello's owner to vincent only if currently owned by guillaume
