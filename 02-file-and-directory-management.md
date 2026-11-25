# Linux Fundamentals Lab 02: File and Directory Management

## Objective
Learn how to create, organize, copy, move, rename and delete files and directories using Linux commands.

## Environment
- Operating System: Kali Linux
- Shell: Bash

## Commands Practiced

| Command | Purpose |
|---|---|
| `mkdir` | Creates directories |
| `touch` | Creates empty files |
| `cp` | Copies files |
| `mv` | Moves or renames files |
| `rm` | Removes files |
| `rmdir` | Removes empty directories |
| `find` | Searches for files |
| `cat` | Displays file contents |
| `file` | Identifies file types |
| `du` | Displays disk usage |

## Practical Exercises

### Creating directories
```bash
mkdir projects
```

### Creating files
```bash
touch notes.txt
```

### Copying files
```bash
cp notes.txt backup.txt
```

### Moving and renaming files
```bash
mv notes.txt projects/
mv backup.txt backup-old.txt
```

### Searching for files
```bash
find . -name "*.txt"
```

### Displaying file contents
```bash
cat backup-old.txt
```

### Removing files
```bash
rm backup-old.txt
```

## Key Lessons
- Linux organizes information using a hierarchical filesystem.
- Files can be copied, moved, renamed and deleted using terminal commands.
- The `find` command helps locate files.
- Proper file organization is important in system administration.

## Cybersecurity Relevance
File management is essential when handling security logs, scripts, configuration files, backups and digital investigation evidence.

## Status
Practical exercises and documentation to be verified.
