<h1>Python MD5 Hash Cracker</h1>


<h2>Description</h2>
In this project, we will be creating a Python script designed to crack MD5 hashes. The focus will be on developing a script that can take an MD5 hash input and employ a list of potential plaintext passwords to uncover the original text. This practical exercise serves as an excellent introduction to the vulnerabilities of MD5 hashes and the techniques used for their decryption.<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Linux</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Elastic Cloud</b>

<h2>Takeaways</h2>

- <b>Python Script Development for MD5 Hash Cracking</b>: Successfully developed a Python script that deciphers MD5 hashes to reveal plain text passwords, emphasizing practical applications of cryptographic techniques. Demonstrated proficiency in utilizing Python's hashlib module, enhancing skills in creating security tools and understanding hash function vulnerabilities.

- <b>Testing and Verification of Script Functionality</b>: Acquired practical experience by rigorously testing the hash cracker against a custom password list, validating the script’s effectiveness in identifying the correct passwords. This process highlighted the importance of comprehensive testing in software development, ensuring the tool’s functionality and reliability in real-world scenarios.


<h2>Program walk-through:</h2>

<p align="center">
Connecting to the Elastic Beats agent in order to receive data from Kali VM: <br/>
<img src="Agent Verifed Connection.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating security events using nmap for the SIEM to pick up on:  <br/>
<img src="Generating Security Events on Kali.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log analysis: <br/>
<img src="Log Analysis.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom query for nmap:  <br/>
<img src="Custom Query.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Dashboard containing security events:  <br/>
<img src="Dashboard.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Alert to detect security events via email:  <br/>
<img src="Email Alert Setup.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
