# 🐚 Holberton School - Shell

## 📋 Description

Collection of shell scripting projects and exercises focused on mastering Unix/Linux command-line operations. This repository demonstrates proficiency in Bash scripting, file manipulation, system administration, and automation tasks.

## 🎯 Learning Objectives

- Master essential Unix/Linux commands
- Understand file system navigation and permissions
- Learn I/O redirection and piping
- Work with environment variables and shell initialization
- Automate tasks using shell scripts
- Apply filters and text processing tools

## 🛠️ Technologies Used

- **Bash** - Unix shell and command language
- **Linux/Unix** - Operating system environment
- **Shell Scripts** - Automation and task scripting
- **Text Processing Tools** - grep, sed, awk, cut, tr

## 📁 Projects Structure

### 📂 `/basics`
Fundamental shell commands and navigation:
- File and directory operations (ls, cd, pwd, mkdir, rm)
- File display and manipulation (cat, head, tail, less)
- Working with paths (absolute and relative)
- Special characters and wildcards
- Basic file operations

**Key Commands:**
```bash
ls -la          # List all files with details
cd /path        # Change directory
pwd             # Print working directory
mkdir dir       # Create directory
cp src dest     # Copy files
mv src dest     # Move/rename files
```

### 📂 `/permissions`
File permissions and ownership management:
- Understanding permission system (read, write, execute)
- Changing file permissions (chmod)
- Modifying file ownership (chown, chgrp)
- Special permissions (setuid, setgid, sticky bit)
- Security best practices

**Key Commands:**
```bash
chmod 755 file      # Set permissions (rwxr-xr-x)
chmod u+x file      # Add execute for user
chown user file     # Change owner
chgrp group file    # Change group
ls -l               # View permissions
```

### 📂 `/io_redirections_and_filters`
Advanced I/O operations and text processing:
- Input/output redirection (>, <, >>)
- Pipes and command chaining (|)
- Text filters (grep, sort, uniq, wc)
- Stream editing (sed, tr, cut)
- Process substitution

**Key Commands:**
```bash
command > file          # Redirect output
command >> file         # Append output
command < file          # Input from file
command1 | command2     # Pipe output
grep pattern file       # Search text
sort file               # Sort lines
uniq file               # Remove duplicates
wc -l file              # Count lines
```

### 📂 `/init_files_variables_and_expansions`
Shell initialization and environment configuration:
- Initialization files (.bashrc, .bash_profile)
- Environment variables (PATH, HOME, USER)
- Local vs global variables
- Variable expansion and substitution
- Aliases and functions
- Arithmetic operations

**Key Commands:**
```bash
export VAR=value        # Set environment variable
echo $VAR               # Print variable
alias ll='ls -la'       # Create alias
env                     # Show all variables
printenv PATH           # Show specific variable
```

## 🚀 Usage

Each script is executable and follows Holberton School's requirements:

```bash
# Make script executable
chmod +x script.sh

# Run script
./script.sh

# Or with bash
bash script.sh
```

## 📚 Key Concepts

### File System
- Absolute vs relative paths
- Hidden files (starting with .)
- Directory hierarchy
- File types and extensions

### Permissions
- Owner, group, others
- Read (r), write (w), execute (x)
- Numeric notation (755, 644)
- Special permissions

### Redirection & Pipes
- stdin (0), stdout (1), stderr (2)
- File descriptors
- Command chaining
- Process substitution

### Variables
- Environment variables
- Shell variables
- Variable expansion
- Command substitution

## 🎓 Skills Acquired

✅ Shell scripting fundamentals  
✅ File system navigation  
✅ Permission management  
✅ I/O redirection and piping  
✅ Text processing and filtering  
✅ Environment configuration  
✅ Command-line automation  
✅ System administration basics  

## 📖 Script Standards

All scripts follow these guidelines:
- First line: `#!/bin/bash`
- Executable permissions
- Betty-compliant (when applicable)
- No syntax errors
- Proper comments and documentation

## 👨‍💻 Author

**Nicolai C.** - Holberton School Student

## 🏫 Institution

Holberton School - Full-Stack Software Engineering Program

---

*"The command line is the ultimate power tool for developers. Master it, and you master your system."*