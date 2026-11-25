# Linux Fundamentals Lab 04: Users and Permissions

## Objective
Understand Linux user accounts, groups, ownership and file permissions.

## Environment
- Operating System: Kali Linux
- Shell: Bash

## Commands Practiced

| Command | Description |
|---|---|
| `whoami` | Displays the current username |
| `id` | Displays user and group identification |
| `groups` | Displays groups a user belongs to |
| `sudo` | Executes commands with elevated privileges |
| `useradd` | Creates a new user account |
| `passwd` | Changes a user's password |
| `usermod` | Modifies user account settings |
| `chmod` | Changes file permissions |
| `chown` | Changes file ownership |
| `ls -l` | Displays file permissions and ownership |

## Understanding Linux Permissions

Linux uses three main permission types:

- r = Read (4)
- w = Write (2)
- x = Execute (1)

Permissions apply to three categories:

- User (owner)
- Group
- Others

Example:

```bash
-rwxr-xr--
```

This represents:
- Owner: Read, write and execute
- Group: Read and execute
- Others: Read only

## Practical Exercises

### 1. Identify the current user
```bash
whoami
```

### 2. Display user and group information
```bash
id
```

### 3. Display group membership
```bash
groups
```

### 4. Create a test file
```bash
touch security.txt
```

### 5. View file permissions
```bash
ls -l security.txt
```

### 6. Change file permissions
```bash
chmod 644 security.txt
```

### 7. Make a file executable
```bash
chmod 755 security.txt
```

### 8. Change file ownership
```bash
sudo chown username:username security.txt
```

Replace username with an existing Linux account.

### 9. View permissions again
```bash
ls -l security.txt
```

## Key Lessons
- Linux uses user and group-based access control.
- File permissions determine who can read, write or execute files.
- `chmod` modifies permissions.
- `chown` changes ownership.
- `sudo` provides controlled administrative privileges.

## Cybersecurity Relevance
Linux permissions help protect sensitive files, restrict unauthorized access, secure system resources and prevent privilege misuse.

## Status
Documentation created. Practical exercises pending verification.
