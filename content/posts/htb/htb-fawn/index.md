---
title: HTB - Fawn
description: 
slug: htb-fawn
date: 2023-01-21
image: htb-fawn.png
categories:
    - HTB
tags:
    - htb 
    - tier0-machine
---
This is my second HTB Machine. I only had to answer some questions about different tools and things that are used in linux.

1. What does the 3-letter acronym FTP stand for?
	- File Transfer Protocol

2. Which port does the FTP service listen on usually?
	- 21

3. What acronym is used for the secure version of FTP?
	- SFTP

4. What is the command we can use to send an ICMP echo request to test our connection to the target?
	- ping

5. From your scans, what version is FTP running on the target?
	- scan = nmap IP -sV | vsftpd 3.0.3

6. From your scans, what OS type is running on the target?
	- unix (scan from nmap)

7. What is the command we need to run in order to display the 'ftp' client help menu?
	- ftp -h

8. What is username that is used over FTP when you want to log in without having an account?
	- anonymous

9. What is the response code we get for the FTP message 'Login successful'?
	- 203 code

10. There are a couple of commands we can use to list the files and directories available on the FTP server. One is dir. What is the other that is a common way to list files on a Linux system.
	- ls

11. What is the command used to download the file we found on the FTP server?
	- get

How to connect to FTP Server

type first ftp:

```bash
ftp

open

[IP Address]

USERNAME
PASSWORD
```

---

Submit root flag: 035db21c881520061c53e0536e44f815