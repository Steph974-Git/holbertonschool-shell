# Shell, I/O Redirections and Filters

This directory contains scripts demonstrating shell I/O redirection techniques and text processing filters as part of the Holberton School Shell project.

## Learning Objectives

After working with these scripts, you should be able to explain:

### Shell, I/O Redirection
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections

### Command Line Tools
- What these commands do and how to use them:
  - `head`: Display the beginning of a file
  - `tail`: Display the end of a file
  - `find`: Search for files in a directory hierarchy
  - `wc`: Print newline, word, and byte counts for files
  - `sort`: Sort lines of text files
  - `uniq`: Report or omit repeated lines
  - `grep`: Print lines matching a pattern
  - `tr`: Translate or delete characters

### Special Characters
- What special characters are and when to quote them
- Understanding how the shell interprets these characters

## Scripts in this Directory

The scripts in this directory demonstrate:
- Redirecting standard output to files using `>` and `>>`
- Taking input from files using `<`
- Piping output between commands using `|`
- Combining multiple redirections
- Processing text with utilities like `sort`, `uniq`, `grep`, and `tr`
- Handling special characters in text processing
- Advanced searching with `find`

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
- The manual pages for each command (e.g., `man head`, `man grep`)
- GNU Core Utilities documentation
- Bash manual (`man bash`) sections on REDIRECTION
- Advanced Bash-Scripting Guide online