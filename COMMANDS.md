# Commands

|Sl No| Command | Description|
|-----|---------|------------|
|1|`$ echo Hello`||
|2|`$ echo "hello world"`||
|3|`$ uptime`||
||`$ echo -n "hello"`||
||`$ type <command-name>`||
||`$ pwd`||
||`$ ls`||
||`$ mkdir <dir-name>`||
||`$ mkdir a b c`||
||`$ cd <dir-path>`||
||`$ mkdir a/b`||
||`$ mkdir -p a/b`||
||`$ cd`||
||`$ cd ..`||
||`$ pushd <dir-path>`||
||`$ popd`||
||`$ cp <src> <dst>`||
||`$ mv <src> <dst>`||
||`$ rm <file-path>`||
||`$ rm -r <dir-path>`||
||`$ cat <file-path>`||
||`$ cat > <file path>`||
||`$ cat >> <file path>`||
||`$ touch <file-path>`||
||`$ more <file-path>`||
||`$ less <file-path>`||
||`$ ls -l`|long list|
||`$ ls -a`|shows hidden file|
||`$ ls -t`|show newest first|
||`$ ls -rt`|show oldest first|
||`$ whatis <command-name>`||
||`$ man <command-name>`||
||`$ <command> --help`||
||`$ apropos <keyword>`|shows command with keyword provided|
||`$ cd $HOME`||
||`$ echo $SHELL`||
||`$ chsh`||
||`$ alias cls=clear`||
||`$ history`||
||`$ env`||
||`$ export NAME=nilanjan`| |
||`$ echo $NAME`||
||`$ OFFICE=London`|~/.profile or ~/.pam_environment|
||`$ which python3`||
||`$ export PATH=$PATH:/opt/obs/bin`||
||`$ echo $PS1`||
||`$ echo 'PS1="[\d]\u@\h:\w$"' >> ~/.profile`||
||`$ uname`|get linux kernel name|
||`$ uname -r`|get linux kernel version  |
||`$ dmesg`|shows hardware and system logs|
||`$ udevadm info --query=path --name=/dev/sda5`|The udevadm info command is used to display information about devices on a Linux system. When you run the command udevadm info --query=path --name=/dev/sda5, it will display the path of the device node for the device with the name /dev/sda5.|
||`$ udevadm monitor`|listen kernel events|
||`$ lspci`|display all pci, PCI => peripheral components interconnect|
||`$ lsblk`|display block devices|
||`$ lscpu`|display cpu architecture|
||`$ lsmem --summary`||
||`$ sudo systemctl get-default`||
||`$ sudo systemctl set-default multi-user.target`||
||`$ free`||
||`$ free -m`||
||`$ lshw`|detailed hardware info|
||`$ file <file/dir name>`||
||`$ sudo ls -l /sbin/init`||
||`$ yum repolist`||
||`$ yum proves <command-name>`||
||`$ du -sk <file-name>`||
||`$ du -sh <file-name>`||
||`$ ls -lh <file-name>`||
||`$ tar -cf <archive-name.tar> <file1> <file2> <file3>`||
||`$ tar -tf <archive-name.tar>`||
||`$ tar -xf <archive-name.tar>`||
||`$ tar -zcf <archive-name.tar> file1 file2 file3`||
||`$ bzip2 && bunzip2`||
||`$ gzip a$$ gunzip2`||
||`$ xz && unxz`||
||`$ locate <file-name>`||
||`$ updatedb`||
||`$ find <dir-path> -name <file-name>`||
||`$ grep <pattern> <file-name>`||
||`$ grep -i <pattern> <file-name>`||
||`$ grep -r "<pattern>" <dir-path>`||
||`$ grep -v "<pattern> <filename>"`||
||`$ grep -w  <file-name>`||
||`$ grep -vw <file-name>`||
||`$ grep -A1 <pattern> <file-name>`||
||`$ grep -B1 <pattern> <file-name>`||
||`$ grep -A1 -B1 <pattern> <file-name>`||
||`$ echo $SHELL > shell.txt`||
||`$ echo $SHELL >> shell.txt`||
||`$ cat invaliv_file.txt 2> error.txt `||
||`$ cat invaliv_file.txt 2>> error.txt`||
||`$ cat invaliv_file.txt 2> /dev/null`||
||`$ grep <pattern> <file-name> | less`||
||`$ echo "hello world" | tee hello.txt`||
||`$ echo "hello world" | tee -a hello.txt`||
||`$ zcat /usr/share/man/man1/tail.1.gz >> /home/bob/pipes`||
||`$ locate`||
||`$ find`||
||`$ ping <some-ip>`||
||`$ cat >> /etc/host`||
||`$ cat /etc/resolv.config`||
||`$ cat /etc/nsswitch.conf`||
||`$ nslookup`||
||`$ dig`||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
||`$ `||
