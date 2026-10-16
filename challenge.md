# Challenge: Security Detective

## Question 1
Answer: I am logged in as taaniszahra51. My home folder is /home/taaniszahra51.
Commands: whoami, pwd

## Question 2
Answer: The server's hostname is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.6 GiB of RAM, and 2.3 GiB of disk space is free on /.
Commands: free -h, df -h /

## Question 4
Answer: Users with /bin/bash shell are root and taaniszahra51.
Commands: grep "bash" /etc/passwd

## Question 5
Answer: There are 238 processes running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at 05:21:40 and deleted shortly after as recorded in /var/log/auth.log.
Commands: sudo grep lab5user /var/log/auth.log
