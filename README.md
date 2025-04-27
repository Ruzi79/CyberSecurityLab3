Task 1:
![image](https://github.com/user-attachments/assets/8f2af06c-7f8e-4937-9b18-9b28ef876317)

Hostname - IP Address:
(No hostname)	192.168.56.1,
(No hostname)	192.168.56.100,
metasploitable.localdomain	192.168.56.102

Note:
192.168.56.101 is my own Kali Linux machine

Task 2:
![image](https://github.com/user-attachments/assets/fcf19b02-4712-4030-a256-053a99e7fe4f)

Using SYN scan (nmap -sS), the top 5 open ports discovered on 192.168.56.102 are:
Port - Service:
21/tcp	FTP,

22/tcp	SSH,
23/tcp	Telnet,
25/tcp	SMTP,
80/tcp	HTTP

Task 3:
![image](https://github.com/user-attachments/assets/2384e23e-95ce-4930-8b61-d3d369fa1b10)

Using version detection (nmap -sV), the following service versions were found:
Service	- Version:
SSH	OpenSSH 4.7p1 Debian 8ubuntu1 (protocol 2.0),
HTTP (port 80)	Apache httpd 2.2.8 ((Ubuntu) DAV/2)

Task 4:
![image](https://github.com/user-attachments/assets/8576937f-7a52-47a2-9054-158b7658c4a1)

Operating System Detected: Linux 2.6.x,
OS Details: Linux kernel version between 2.6.9 and 2.6.33

Task 5:
![image](https://github.com/user-attachments/assets/fe9a0de9-b70d-4d07-84d0-84677cdb7dd3)

HTTP Service (Port 80):
Server: Apache/2.2.8 (Ubuntu) DAV/2

SSH Service (Port 22):
Server: OpenSSH_4.7p1 Debian-8ubuntu1
