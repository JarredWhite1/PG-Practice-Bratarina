# PG-Practice-Zino

<h1>Zino Machine Writeup</h1>


<h2>Description</h2>
Project consists of performing penetration test on a Linux machine called "Zino".
<br />


<h2>Languages and Utilities Used</h2>

- <b>Nmap</b> 
- <b>Searchsploit</b>
- <b>Smbclient</b>
- <b>Smbmap</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>

<h2>Program walk-through:</h2>

<p align="center">
Running Inital Nmap Fast Scan against target: <br/>
<img src="https://github.com/JarredWhite1/PG-Practice-Zino/blob/main/nmapinital.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nmap Inital-Finding Open Ports:  <br/>
<img src="https://github.com/JarredWhite1/PG-Practice-Zino/blob/main/nmap2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nmap Advanced Service and OS Scan with Default Scripts: <br/>
<img src="https://github.com/JarredWhite1/PG-Practice-Zino/blob/main/nmapAdv1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nmap Advanced Scan Open Ports and Services:  <br/>
<img src="https://github.com/JarredWhite1/PG-Practice-Zino/blob/main/nmapAdv2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nm:  <br/>
<img src="https://github.com/JarredWhite1/LLMNR-Poisioning/blob/main/responder5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cracking the hashes with hashcat on our Kali machine:  <br/>
<img src="https://github.com/JarredWhite1/LLMNR-Poisioning/blob/main/responder6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cracked the password on Kali!  <br/>
<img src="https://github.com/JarredWhite1/LLMNR-Poisioning/blob/main/responder7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 LLMNR Poisoning Defense  <br/>
<img src="https://github.com/JarredWhite1/LLMNR-Poisioning/blob/main/responder10.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>


