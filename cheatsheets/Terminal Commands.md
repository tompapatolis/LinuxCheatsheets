# Basic Terminal Commands in Linux

## Command Reference Table

| Command   | Description                                   |
|-----------|-----------------------------------------------|
| `pwd`     | Prints the current working directory.         |
| `ls`      | Lists the contents of a directory.            |
| `cd`      | Changes the current directory.                |
| `mkdir`   | Creates a new directory.                      |
| `rmdir`   | Removes an empty directory.                   |
| `touch`   | Creates an empty file.                        |
| `cp`      | Copies files or directories.                  |
| `mv`      | Moves or renames files or directories.        |
| `rm`      | Deletes files or directories.                 |
| `cat`     | Displays the contents of a file.              |
| `nano`    | Opens a file for editing in the Nano editor.  |
| `man`     | Shows the manual page for a command.          |
| `chmod`   | Changes file or directory permissions.        |
| `chown`   | Changes file or directory ownership.          |
| `find`    | Searches for files in a directory hierarchy.  |
| `grep`    | Searches for patterns in text files.          |
| `sudo`    | Executes a command with superuser privileges. |
| `apt`     | Manages packages on Debian-based systems.     |
| `ps`      | Displays currently running processes.         |
| `kill`    | Terminates a running process.                 |
| `df`      | Shows disk space usage of file systems.       |
| `free`    | Displays memory usage.                        |
| `clear`   | Clears the terminal screen.                   |
| `exit`    | Exits the terminal session.                   |

---

## Command Explanations

### `pwd` - Print Working Directory
The `pwd` command outputs the full path of the directory you are currently in. It helps you understand your location in the filesystem.

**Usage:**
```bash
pwd
```

---

### `ls` - List Directory Contents
The `ls` command lists the files and directories in the current location. Add options like `-l` for detailed information or `-a` to include hidden files.

**Usage:**
```bash
ls
ls -l
ls -a
```

---

### `cd` - Change Directory
The `cd` command changes your current directory. Use `..` to go up one level or a specific path to navigate directly.

**Usage:**
```bash
cd /path/to/directory
cd ..
```

---

### `mkdir` - Make Directory
The `mkdir` command creates a new directory. Use the `-p` option to create parent directories if they don’t exist.

**Usage:**
```bash
mkdir new_folder
mkdir -p /path/to/new_folder
```

---

### `rmdir` - Remove Directory
The `rmdir` command deletes an empty directory. It won’t work on directories with content.

**Usage:**
```bash
rmdir empty_folder
```

---

### `touch` - Create a File
The `touch` command creates an empty file or updates the timestamp of an existing file.

**Usage:**
```bash
touch new_file.txt
```

---

### `cp` - Copy Files and Directories
The `cp` command copies files or directories. Use the `-r` option to copy directories recursively.

**Usage:**
```bash
cp file.txt /destination
cp -r folder /destination
```

---

### `mv` - Move or Rename
The `mv` command moves files or directories and can also be used to rename them.

**Usage:**
```bash
mv file.txt /new_location
mv old_name.txt new_name.txt
```

---

### `rm` - Remove Files and Directories
The `rm` command deletes files and directories. Use the `-r` option to remove directories and their contents.

**Usage:**
```bash
rm file.txt
rm -r folder/
```

---

### `cat` - Display File Contents
The `cat` command outputs the content of a file. Combine it with other commands like `| more` to paginate output.

**Usage:**
```bash
cat file.txt
```

---

### `nano` - Edit Files
The `nano` command opens a text editor in the terminal, allowing you to create or edit files.

**Usage:**
```bash
nano file.txt
```

---

### `man` - Manual Pages
The `man` command displays the manual page for a given command. Use it to understand a command’s options.

**Usage:**
```bash
man ls
```

---

### `chmod` - Change Permissions
The `chmod` command modifies file permissions. Use symbolic or numeric modes to set permissions.

**Usage:**
```bash
chmod 755 file.txt
chmod +x script.sh
```

---

### `chown` - Change Ownership
The `chown` command changes the owner and group of a file or directory.

**Usage:**
```bash
chown user:group file.txt
```

---

### `find` - Search for Files
The `find` command searches for files in a directory hierarchy based on criteria like name, size, or date.

**Usage:**
```bash
find /path -name "*.txt"
```

---

### `grep` - Search Patterns
The `grep` command searches for patterns in text files. Combine it with other commands to filter output.

**Usage:**
```bash
grep "search_term" file.txt
```

---

### `sudo` - Superuser Privileges
The `sudo` command runs commands with administrative privileges. Use it cautiously.

**Usage:**
```bash
sudo apt update
```

---

### `apt` - Package Management
The `apt` command manages packages on Debian-based systems. Use `install`, `update`, and `upgrade` for various tasks.

**Usage:**
```bash
sudo apt update
sudo apt install package_name
```

---

### `ps` - Process Status
The `ps` command lists currently running processes. Add `aux` for a detailed view.

**Usage:**
```bash
ps aux
```

---

### `kill` - Terminate Processes
The `kill` command stops a process by its ID. Use `kill -9` for forceful termination.

**Usage:**
```bash
kill 12345
```

---

### `df` - Disk Space Usage
The `df` command shows disk usage for file systems. Use `-h` for human-readable formats.

**Usage:**
```bash
df -h
```

---

### `free` - Memory Usage
The `free` command displays memory usage, including free and used memory.

**Usage:**
```bash
free -h
```

---

### `clear` - Clear Screen
The `clear` command cleans the terminal screen, giving you a fresh workspace.

**Usage:**
```bash
clear
```

---

### `exit` - Exit Terminal
The `exit` command closes the terminal session.

**Usage:**
```bash
exit
```

---

## Conclusion
This guide covers the foundational Linux commands that every beginner should know. Practice these commands to build confidence in navigating and managing a Linux system. For more details, consult the `man` pages for any command.
