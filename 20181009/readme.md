```

nmap -O 172.20.155.28

Staring Nmap 7.40 ( https://nmap.org ) at 2.018 -10-09 02: 26 EDT
Nmap scan report for 172.20.155.28
Host is up (0.0010s latency) .
Not shown: 997 closed ports
PORT     STATE SERVICE
135/tcp open msrpc
139/tcp open netbios-ssn
445/tcp open microsoft-ds
MAC Address: 08:00:27:2B:E4:43 (Oracle VirtualBox virtual NIC)
Device type: general purpose
Running: Microsoft Windows XP|2003
OS CPE: cpe: /o:microsoft:windows_xp cpe:/o:microsoft:windows_server_2003
OS details : Microsoft Windows Xp SP2 pr SP3, or Windows Server 2003
Network Distance: 1 hop

OS detection performed. Please report any incorrect results at https://nmap.org/submit/ .
IP address (1 host up) sceanned in 2.59 second
```


```
nmap -p 0-65535 172.20.155.28
Staring Nmap 7.40(https//nmap.org ) at 2018-10-09 02:41 EDT
Nmap scan report for 172.20.155.28
Host is up (0.00088s latency).
Not shown: 65533 closed prots
PORT    STATE SERVICE
135/tcp open msrpc
139/tcp open netbios-ssn
445/tcp open microsoft-ds
MAC Address: 08:00:27:2B:E4:43 (Oracle VirtualBox virtual NIC)
Nmap done: 1 IP address (1 host up) scanned in 20.14 seconds
```
