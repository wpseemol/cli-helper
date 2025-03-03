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
    ln hardlink-file file/path
```

-   Soft link any folder or file.

```sh
    ln -s file/path softlink-file
```

#### 📌 The `ls -ltr` command in Linux is used to list file and directories in a detailed, time-sorted manner.

-   ls → lists file and directories.
-   -l → Long format(show permissions, ownership, size, and timestamp),
-   -t → Short file by modification time(newest first).
-   -r → Reverses the order (oldest first).

```sh
    ls -ltr
```
