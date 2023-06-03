---
title: HTB - Dancing
description:
slug: htb-dancing
date: 2023-01-21
image: htb-dancing.png
categories:
    - HTB
tags:
    - htb 
    - tier0-machine
---
This is my third HTB Machine. I only had to answer some questions about different tools and things that are used in linux.

1. What does the 3-letter acronym SMB stand for?
	- Server Message Block

2. What port does SMB use to operate at?
	- 445

3. What is the service name for port 445 that came up in our Nmap scan?
	- microsoft-ds

4. What is the 'flag' or 'switch' we can use with the SMB tool to 'list' the contents of the share?
	- -L

5. How many shares are there on Dancing?
	- 4

6. What is the name of the share we are able to access in the end with a blank password?
	- WorkShares

7. What is the command we can use within the SMB shell to download the files we find?
	- get


How to connect to SMB Server

type first ftp:

```bash
ftp

open

[IP Address]

USERNAME
PASSWORD
```

---

Submit root flag: 5f61c10dffbc77a704d76016a22f1664