# Challenge: Security Detective

## Question 1
Answer: I am maleehanadeem13. My home folder is /home/maleehanadeem13.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu-lab01. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.6 GiB of RAM and 4.6 GB of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: The users who can log in with /bin/bash are root and maleehanadeem13.
Command: grep bash /etc/passwd

## Question 5
Answer: 224 processes are running (ps aux printed 225 lines, minus 1 header line).
Command: ps aux | wc -l

## Question 6
Answer: lab5user was created at ____ and deleted at ____.
Command: sudo grep -E "new user|delete user" /var/log/auth.log
