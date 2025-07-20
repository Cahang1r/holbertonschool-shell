# Permissions Project

This project contains a script that changes the owner and group of the symbolic link `_hello` to `vincent` and `staff`.

- `15-symbolic_link_permissions` changes the ownership of `_hello` symbolic link without affecting the target file.
# Permissions Scripts

## 14-change_owner_and_group

This script changes the owner to `vincent` and the group owner to `staff` for all files and directories in the current directory.

- The script uses the command: `chown vincent:staff *`
- Must be run with `sudo` because changing ownership requires root privileges.
- The script is exactly two lines long:
  - First line: `#!/bin/bash`
  - Second line: ownership change command

### Note:

If `vincent` user does not exist on your system, replace `vincent` with an existing user for testing.
# Permissions Scripts

## 3-new_owner

This script changes the owner of the file `hello` to the user `betty`.

- The script is named `3-new_owner`.
- It uses the `chown` command to change ownership.
- Must be run with `sudo` because changing file ownership requires root privileges.
- The script contains exactly two lines:
  - The first line specifies the script interpreter (`#!/bin/bash`).
  - The second line runs `chown betty hello`.
