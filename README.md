

<h1>Slow PC and Infection</h1>

 ### 

<h2>Description</h2>
The computer was experiencing very slow boot times and showed signs of potential malware infection.
<br />


<h2>Utilities Used</h2>

- <b>Command Prompt</b> 
- <b>Malwarebytes</b>
- <b>Superantispyware</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Steps Taken to Diagnose and Fix the Issue:</h2>

1.Initial System Check

- <b>Observed the system taking unusually long to start up and respond after login.</b> 

- <b>Suspected possible malware infection in addition to system performance issues.</b> 

2.Malware Scan and Removal

- <b>Ran Malwarebytes: Detected and quarantined a suspicious process named AnonymizerLauncher.exe, identified as malware.</b> 
<p align="center">
Key Logger: <br/>
<img src="https://i.imgur.com/D0vguu9.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


- <b>Ran SUPERAntiSpyware: Performed a full system scan to check for additional threats; removed tracking cookies and minor threats.</b> 

<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/zdGb0tn.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


- <b>Restarted the system after malware removal to ensure the malicious process did not reload.</b> 

3.Drive Optimization and Maintenance

- <b>Opened Windows “Optimize Drives” tool and ran a defragmentation and optimization on the system drive to improve access speed.</b> 

- <b>Opened Command Prompt as Administrator and ran:</b> 

Command Prompt:
 Chkdsk C: /f /r
<p align="center">
 C: Fix Drive Errors : <br/>
<img src="https://i.imgur.com/Vuky30C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

- <b>Scheduled the scan on reboot to check for bad sectors and file system issues.</b> 

- <b>After reboot, the scan completed and confirmed minor repairs made to the disk.</b> 

4.Final Testing

- <b>Rebooted the system multiple times to test boot speed and system responsiveness.</b> 

- <b>Confirmed that the boot time had significantly improved and the malware AnonymizerLauncher.exe was no longer present.</b> 

<h2>Conclusion</h2>

The root cause of the slow booting was a combination of disk fragmentation, file system errors, and a malware infection (AnonymizerLauncher.exe).

By using Malwarebytes, SUPERAntiSpyware, Windows Optimize Drives, and chkdsk, the malware was successfully removed and the slow booting issue was resolved.


.
.
.
.
.








