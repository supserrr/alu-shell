# ALU Shell Project

This repository contains various shell scripts focusing on file and directory permissions, ownership, and symbolic links. Below is a description of each script and its functionality.

## Scripts Overview

### 0. My name is Betty
- **File**: `0-my_name_is_betty`
- **Description**: Switches the current user to the user `betty`. Assumes the user `betty` exists.

### 1. Who am I
- **File**: `1-who_am_i`
- **Description**: Prints the effective username of the current user.

### 2. Groups
- **File**: `2-groups`
- **Description**: Prints all the groups the current user is part of.

### 3. New owner
- **File**: `3-new_owner`
- **Description**: Changes the owner of the file `hello` to the user `betty`.

### 4. Empty!
- **File**: `4-empty`
- **Description**: Creates an empty file called `hello`.

### 5. Execute
- **File**: `5-execute`
- **Description**: Adds execute permission to the owner of the file `hello`.

### 6. Multiple permissions
- **File**: `6-multiple_permissions`
- **Description**: Adds execute permission to the owner and the group owner, and read permission to other users for the file `hello`.

### 7. Everybody!
- **File**: `7-everybody`
- **Description**: Adds execution permission to the owner, group owner, and other users for the file `hello`.

### 8. James Bond
- **File**: `8-james_bond`
- **Description**: Sets the permission for the file `hello` such that the owner and group have no permissions, while others have all permissions.

### 9. John Doe
- **File**: `9-john_doe`
- **Description**: Sets the mode of the file `hello` to `-rwxr-x-wx`.

### 10. Look in the mirror
- **File**: `10-mirror_permissions`
- **Description**: Sets the mode of the file `hello` to match the mode of the file `olleh`.

### 11. Directories
- **File**: `11-directories_permissions`
- **Description**: Adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users.

### 12. More directories
- **File**: `12-directory_permissions`
- **Description**: Creates a directory called `my_dir` with permissions `751`.

### 13. Change group
- **File**: `13-change_group`
- **Description**: Changes the group owner of the file `hello` to `school`.

### 14. Owner and group
- **File**: `14-change_owner_and_group`
- **Description**: Changes the owner to `vincent` and the group owner to `staff` for all files and directories in the working directory.

### 15. Symbolic links
- **File**: `15-symbolic_link_permissions`
- **Description**: Changes the owner and group owner of the symbolic link `_hello` to `vincent` and `staff`, respectively.

### 16. If only
- **File**: `16-if_only`
- **Description**: Changes the owner of the file `hello` to `vincent` only if it is currently owned by the user `guillaume`.
