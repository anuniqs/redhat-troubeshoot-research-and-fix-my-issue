### 1. Command not found —

## Command not found —

Usually, all user commands are in /bin and /usr/bin or /usr/local/bin directories. All your programs are installed in these directories.

#### Find it - 

[root@localhost ~]# echo "$PATH"

[root@localhost ~]# printf "%s\n" "$PATH"

#### Fix it -

[root@localhost ~]# ls

[root@localhost ~]# export PATH=$PATH:/bin:/usr/local/bin

[root@localhost ~]# ls

####  Test it -

[root@localhost ~]# which ls

[root@localhost ~]# which gcc

[root@localhost ~]# which date

[root@localhost ~]# which cal


