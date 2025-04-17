# Linux Commands Cheat Sheet

## 1. Basic Navigation and Directory Commands

| Command               | Description                                           | Example                            |
|-----------------------|-------------------------------------------------------|------------------------------------|
| `ls`                  | List files and directories                            | `ls -l` (long listing)             |
| `pwd`                 | Print working directory                              |                                    |
| `mkdir`               | Create a directory                                    | `mkdir folder`                     |
| `mkdir aa bb cc dd`   | Create multiple directories                          |                                    |
| `cd`                  | Change directory                                      | `cd folder`                        |
| `cd ..`               | Go up one level to parent directory                   |                                    |
| `cd -`                | Go to the previous directory (back button)            |                                    |
| `clear`               | Clear terminal screen                                 |                                    |

---

## 2. File Operations

| Command                | Description                                           | Example                            |
|------------------------|-------------------------------------------------------|------------------------------------|
| `touch filename`       | Create an empty file                                  |                                    |
| `cat`                  | View or create file content                           | `cat file.txt`                     |
| `nano filename`        | Edit file using Nano editor                           |                                    |
| `vi filename`          | Edit file using Vi editor                             | `i` (insert mode), `:wq` (save & quit) |
| `cp source destination`| Copy file or directory                                | `cp file1.txt file2.txt`           |
| `mv source destination`| Move or rename file or directory                      | `mv file1.txt folder/`             |
| `rm filename`          | Remove a file                                         |                                    |
| `rm -r foldername`     | Remove directory and its contents                     |                                    |

---

## 3. System Information and Networking

| Command                | Description                                           | Example                            |
|------------------------|-------------------------------------------------------|------------------------------------|
| `uname`                | Print system information                              | `uname -a` (full info)             |
| `df -h`                | Display disk space usage                              |                                    |
| `free -m`              | Show RAM usage                                        |                                    |
| `ping IP/domain`       | Check server connectivity                             | `ping 8.8.8.8`                     |
| `scp`                  | Secure copy files between local and remote machines   | `scp file.txt user@host:/path`     |

---

## 4. Permissions and Ownership

| Command                | Description                                           | Example                            |
|------------------------|-------------------------------------------------------|------------------------------------|
| `chmod`                | Change file permissions                               | `chmod 754 file.txt`               |
| `chown`                | Change file owner and group                           | `chown user:group file.txt`        |
| `chgrp`                | Change group ownership                                | `chgrp group file.txt`             |

---

## 5. Service Management

| Command                      | Description                                           | Example                            |
|------------------------------|-------------------------------------------------------|------------------------------------|
| `sudo service apache2 start`  | Start Apache service                                  |                                    |
| `sudo systemctl enable apache2`| Enable Apache to start on boot                        |                                    |
| `sudo service nginx restart`  | Restart Nginx service                                 |                                    |
| `sudo systemctl status httpd` | Check Apache service status                           |                                    |

---

## Additional Commands

### 6. File Viewing and Editing

| Command                     | Description                                             | Example                             |
|-----------------------------|---------------------------------------------------------|-------------------------------------|
| `head file.txt`             | View the first 10 lines of a file                       |                                     |
| `tail file.txt`             | View the last 10 lines of a file                        |                                     |
| `head -n 20 file.txt`       | View the first 20 lines of a file                       |                                     |
| `tail -n 20 file.txt`       | View the last 20 lines of a file                        |                                     |

---

### 7. Other Useful Commands

| Command                     | Description                                             | Example                             |
|-----------------------------|---------------------------------------------------------|-------------------------------------|
| `history`                   | View the command history                                |                                     |
| `whoami`                    | Display the current logged in user                       |                                     |
| `man`                       | Get the manual for any command                          | `man ls`                            |
| `ls -a`                     | List all files, including hidden files                  |                                     |
| `ls -al`                    | List all files with long details                        |                                     |

---

## 8. Software and Package Management

| Command                           | Description                                             | Example                             |
|-----------------------------------|---------------------------------------------------------|-------------------------------------|
| `yum install software_name`       | Install a package using yum (Amazon Linux)              | `sudo yum install httpd -y`        |
| `apt-get install software_name`   | Install a package using apt (Ubuntu/Debian)             | `sudo apt-get install apache2`      |
| `yum remove software_name`        | Remove a package using yum                              | `sudo yum remove httpd -y`         |
| `systemctl restart service_name`  | Restart a service                                       | `sudo systemctl restart nginx`      |
| `sudo systemctl enable service_name` | Enable service to start at boot                         |                                     |
