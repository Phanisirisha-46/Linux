# Linux
## Basic commands in Linux

### Create the user
    sudo useradd username
### Add sudo privileges for user
    sudo visudo /etc/sudoers.d/username
### Login into system
    ssh username@workstation
### Create group
    sudo groupadd groupname
### Create user and add it as supplementary group
    sudo useradd -G groupname username
### Create the user and deny access to it
    sudo useradd -s /sbin/nologin username
### Create the password to users
    sudo passwd username
### Create the dicrectory
    sudo mkdir -p directoryname
### Giving the ownership to group
    sudo chown :groupname directoryname
### Giving the members of group - accessibility, read, write
    sudo chmod 770 directoryname
### copy the directories
    sudo cp directory1 directory2
### File being owned by root
    sudo chown root directoryname
### File belongs to group root
    sudo chgrp directoryname
### File being not executable by anyone
    sudo chmod o-x directoryname
    sudo chmod g-x directoryname
    sudo chmod u-x directoryname
### File having the ability to read in future
    sudo chmod o+r directoryname
### Creating tar file
    sudo tar -cjf /root/myetcbackup.tar.bzip2  /etc
### Redirect the long listing file to another file
    sudo ls -al /home/natasha > vimedit.txt
### vim commands
#### edit the vim file
    vim vimedit.txt
#### Delete the lines
    Shift + V
#### Delete the columns
    Ctrl + v
#### insert the dashed line
    echo "--------------" >> vimedit.txt
### Create hardlink 
    sudo mkdir -p ~/Documents/backups
    sudo ln vimedit.txt ~/Documents/backups/vimedit.back
    cat  ~/Documents/backups/vimedit.back
## These are some Basic commands of Linux Operating System
    

    
