## Notes
options can have different meaning to different programs
docker cp foo.txt container_id:/foo.txt
nano, vim, emacs
if you want to use ifconfig, install net-tools
## Help
1. man command
2. command --help
man 
## Search Show and install packages
1. apt search sudo
2. apt show sudo
3. apt install sudo

## get some basic info and create a user 
[Link](https://linuxize.com/post/how-to-create-users-in-linux-using-the-useradd-command/)
1. whoami = print effective userid
2. id = print real and effective user and group IDs
3. pwd = print name of current/working directory
4. printenv = prints environment variables
5. sudo useradd -m username = user gets added to home/username directory
6. sudo passwd username
7. sudo usermod -s /bin/bash username = changes terminal from sh to bash
8. sudo adduser username sudo
9. login = login as new user

try to create a new user and then try to step into his home directory. What happens?

## g

- wc -l file  => one option
- wc -l -w file => options are seperated
- wc -lw file => or with just one dash
- wc --lines file =>  commands can also be one word with two dashes

## unzip
- use the myzip file

## grep and pipes
- [grep exercise](https://ostechnix.com/the-grep-command-tutorial-with-examples-for-beginners/)
- grep ker grep.txt| sort
- combining commands = command1 && command2 && command3


## echo, write and read from and to a file
- echo my name is joerg
- echo my name is $USER and my home is $HOME
- echo this is a long sentence /
that doesn't fit on one line
- touch file.txt
- echo sometext > file.txt
- echo some more text >> file.txt
- rm file.txt
- mkdir folderName
- create a text file
- delete folder incl textfile

## copy
- cp file1 file2 // copy file
- mv file1 file2 // rename

## network
- ip


## Process
- ps
- top
- kill


## file permissions
- chmod octal file


## show off linux
 - [SDKMan](https://sdkman.io/)
 - [ZSHELL](https://linuxconfig.org/learn-the-basics-of-the-zsh-shell)

