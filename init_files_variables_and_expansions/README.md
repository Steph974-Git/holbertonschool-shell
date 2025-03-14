# Shell, Init Files, Variables and Expansions

This directory contains scripts that demonstrate advanced shell concepts including initialization files, variables, expansions, and arithmetic operations as part of the Holberton School Shell project.

## Learning Objectives

After working with these scripts, you should be able to explain:

### General
- What happens when you type `$ ls -l *.txt`
- How command expansion and pattern matching work in the shell

### Shell Initialization Files
- The purpose of the `/etc/profile` file and the `/etc/profile.d` directory
- The function of the `~/.bashrc` file
- How shell startup scripts affect your environment

### Variables
- The difference between local and global variables
- What reserved variables are and their importance
- How to create, update, and delete shell variables
- The roles of important reserved variables: `HOME`, `PATH`, `PS1`
- What special parameters are
- What the special parameter `$?` represents and how to use it

### Expansions
- What expansion is and how to use different types of expansions
- The difference between single and double quotes and when to use each
- How to perform command substitution with `$()` and backticks

### Shell Arithmetic
- How to perform arithmetic operations in the shell
- Using the `expr` command and arithmetic expansion `$(( ))`

### The alias Command
- How to create custom aliases
- How to list all defined aliases
- How to temporarily disable an alias
- Best practices for using aliases

## Scripts in this Directory

Each script in this directory demonstrates one or more of the concepts above:

- Working with shell variables
- Using command substitution
- Creating and managing aliases
- Performing arithmetic operations
- Working with shell initialization files
- Understanding path and environment variables

## Usage Instructions

All scripts are executable. To run any script:

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
- Bash manual (`man bash`)
- GNU Bash documentation
- Shell initialization documentation (`man bash` section on INVOCATION)
