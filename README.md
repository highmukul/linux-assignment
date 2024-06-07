# linux-assignment
This is the assignment 1 of week 1 during my internship in Celebal Technologies, Jaipur in the DevOps domain.
# Linux Assignment

## File Permissions and Commands

1. Create a file and assign permissions:
    touch mukul.txt
    chmod 754 mukul.txt
    ls -l mukul.txt

2. Basic Linux commands:
    ls
    cd /home/kali/
    mkdir mukul
    rm mukul.txt
    touch mukul.txt

3. Navigating directories and moving files:
    cd ..
    ls -l
    mv /home/kali/mukul.txt /home/kali/desktop

4. User and group management:
    sudo useradd kalihaxor
    sudo passwd kalihaxor
    sudo groupadd newgroup
    sudo usermod -aG newgroup kalihaxor
    sudo chown :newgroup mukul.txt
    sudo userdel kalihaxor
    sudo groupdel newgroup
