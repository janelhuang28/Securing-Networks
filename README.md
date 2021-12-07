# Securing-Networks
Home Networks are common DDoS tools for hackers. Such hacking abilities are also applicable to work places.

## Pentest-Tools
To do a simple scan for vulnerabilities in a home network, one can use ```pentest-tools.com```. This is an open source website that can scan for vulnerabilities within a public IP address. 
![image](https://user-images.githubusercontent.com/39514108/145118577-7d46716c-7731-4c4f-befd-6ca6e5f606a5.png).
This tool is able to find open vulnerable ports that can allow hackers to enter. For example, port 3389 is a port that should not be permanently opened as it allows for remote desktop logins.

## Nmap
Nmap can also be used to scan for vulernabilities in a system. For example, ```nmap -sT <public IP>``` can scan for open ports on a network. Custom scripts can also be used to scan for specific vulnerbilities such as XSS, etc. 
![image](https://user-images.githubusercontent.com/39514108/145119415-2d38b177-c19b-49a4-a402-c511e190f0b5.png)

## To Patch
1. Enable a firewall
2. Close Unecessary ports through port frowarding in NAT forwarding
3. Disable remote access - only allow for a temporary time and a specific user
4. Patch all software, firmware or hardware where necessary
5. Use WPA/WPA2 or better
6. Set a secure wifi password

