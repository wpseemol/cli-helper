# 👩‍💻Important Commands

#### 📌 check disk space.

```sh
    df -h
```

#### 📌Check free memory.

```sh
    free -h
```

#### 📌Check mount file system.

```sh
    mount
```

#### 📌List disk partitions.

```sh
    lsblk
```

or

```sh
    fdisk -l
```

#### 📌Create new file system.

```sh
    mkfs.ext4 /dev/sdx
```

#### 📌Show list of file and folder on linux.

```sh
    ls
```

#### 📌Create folder on Linux use.

```sh
    mkdir
```

#### 📌About folder on linux.

```sh
    ls -l
```

#### 📌Present Working Directory

```sh
    pwd
```

#### 📌Create new file use commend.

```sh
    touch new_file_name.txt
```

#### 📌Clear terminal use commend.

```sh
    clear
```

#### 📌Change directory.

```sh
    cd
```

#### 📌Remove any file use commend.

```sh
    rm file_name.txt
```

#### 📌Remove folder directly

```sh
    rmdir folder_name/
```

#### 📌Remove folder recursive short `-r` commend

```sh
    rm -r folder_name/
```

#### 📌cat commend open file and display file content.

```sh
    cat file_name.txt
```

#### 📌Write some text on file use command line.

-   `>` Redirects and output file.
-   if file name is not exist the command create file.

```sh
    echo "some text" > file_name.txt
```

#### 📌Word Count on linux.

```sh
    wc file_name.tsx
```

#### 📌Link file and folder.

-   heard link

```sh
    ln file/path hard_link_file_name
```

-   Soft link any folder or file.

```sh
    ln -s file/path soft_link_file_name
```

#### 📌 The `ls -ltr` command in Linux is used to list file and directories in a detailed, time-sorted manner.

-   ls → lists file and directories.
-   -l → Long format(show permissions, ownership, size, and timestamp),
-   -t → Short file by modification time(newest first).
-   -r → Reverses the order (oldest first).

```sh
    ls -ltr
```

#### 📌 The`uname` command is used to display information such as the kernel name, version, and architecture.

```sh
    uname
```

#### 📌 Linux system was been running since the last reboot.

```sh
    uptime
```

#### 📌 `who` and `whoami` commands in linux.

-   The `who` command show information about users currently logged int the systems.

```sh
    who
```

-   the `whoami` command prints current user executing command.

```sh
    whoami
```

#### 📌`which` command is used to locate the executable path of a command or program in the system.

```sh
    which command_name
```

#### 📌 The `id` command is used to display user and group information for the current user or specified user.

```sh
    id
```

-   `uid=100(user1)` → user id and username.
-   `gid=1000(user1)` → group id and primary group name.
-   `groups=1000(user1),27(sudo)` → Lists all groups the user belongs to including `sudo` (if applicable)

#### The `useradd` command in linux is used to create a new user account.It modifies files, such as `/etc/passwd`, `/etc/shadow`, and `/etc/group`, to add the new user.

```sh
    sudo useradd -m user_name
```

-   Set a password for the user(after creation)

```sh
    sudo passwd user_name
```
