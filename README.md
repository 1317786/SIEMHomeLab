<h1>SIEM Tool Home Lab</h1>


<h2>Description</h2>
In this project, we will be creating a Python script designed to crack MD5 hashes. The focus will be on developing a script that can take an MD5 hash input and employ a list of potential plaintext passwords to uncover the original text. This practical exercise serves as an excellent introduction to the vulnerabilities of MD5 hashes and the techniques used for their decryption.<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Linux</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Elastic Cloud</b>

<h2>Takeaways</h2>

- <b>Elastic Stack SIEM Configuration and Management</b>: Successfully set up and configured Elastic Stack SIEM in a home lab environment. Demonstrated proficiency in deploying a Kali Linux VM, configuring Elastic agents for log collection, and forwarding data to the SIEM for effective security event monitoring.


- <b>Security Event Simulation and Analysis</b>: Acquired hands-on experience in generating and analyzing security events using Nmap on Kali Linux. Proficient in querying Elastic SIEM to identify and investigate security incidents, enhancing skills in network security monitoring and threat detection.

- <b>Visualization and Alerting in SIEM</b>: Developed a custom dashboard in Elastic SIEM to visualize security events, demonstrating skills in data interpretation and pattern recognition. Successfully created and tested alert rules for detecting specific security events, showing competency in proactive incident response and alert management.


<h2>Program walk-through:</h2>

<p align="center">
Python code to create MD5 hash cracker using nano text editor: <br/>
<img src="Agent Verifed Connection.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created .txt file containing list of possible passwords:  <br/>
<img src="Generating Security Events on Kali.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generated an MD5 hash tied to the password 'admin': <br/>
<img src="Log Analysis.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful verfication of the hash cracker detecting admin within the hash:  <br/>
<img src="Custom Query.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
