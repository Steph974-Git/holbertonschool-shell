# Shell, Permissions

This directory contains scripts demonstrating file and directory permission management in Linux/Unix systems as part of the Holberton School Shell project.

## Learning Objectives

After working with these scripts, you should be able to explain:

### Permissions Basics
- What permissions are and how they affect files and directories
- The Linux file permission model (owner, group, others)
- Understanding read, write, and execute permissions
- The meaning of octal notation for permissions (e.g., 755, 644)

### Managing Permissions
- How to represent and change permissions with symbolic notation
- How to change permissions, owner, and group of files
- Why changing permissions is important for security
- Default permissions when creating files and directories

### Special Permissions
- Understanding special permissions (setuid, setgid, sticky bit)
- When and how to use special permissions
- Security implications of special permissions

## Scripts in this Directory

The scripts in this directory demonstrate:
- Displaying file and directory permissions using `ls -l`
- Changing permissions with `chmod` using both symbolic and numeric notation
- Changing file ownership with `chown`
- Changing group ownership with `chgrp`
- Setting default permissions with `umask`
- Working with special permissions
- Managing permissions for multiple files

## Usage Instructions

All scripts in this directory are executable. To run any script:

```bash
# Make the script executable if needed
chmod +x script-name

# Run the script
./script-name
```

## Requirements

- All scripts are written for Bash
- All scripts begin with `#!/bin/bash`
- All scripts are executable
- Scripts follow shell scripting best practices

## Additional Resources

For more information on these topics, refer to:
- Manual pages for permission-related commands (`man chmod`, `man chown`)
- Linux Documentation Project guides on file permissions
- The book "Linux Command Line and Shell Scripting Bible"
- Online tutorials on Linux file permissions and security