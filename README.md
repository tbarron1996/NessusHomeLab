<h1>Nessus - Vulnerability Management</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This Project constists of creating a lab environment where I run vulnerability scans on a VM that has deprecated software on it and using Nessus Essentials to rememdy whatever vulnerabilities are detected.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Nessus Essiantials</b> 
- <b>VMWare</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
After installing all the necessary software open and create a VM with the appropriate settings: <br/>
<img src="https://imgur.com/NSgGYPV.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Launch the VM:  <br/>
<img src="https://imgur.com/7kkyg3S.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Install Windows: <br/>
<img src="https://imgur.com/C3Jcn8v.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Ping VM on main computer(right) to ensure it has connection:  <br/>
<img src="https://imgur.com/nEzt0BN.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Download Nessus from the browser (may take some time):  <br/>
<img src="https://imgur.com/oUU5Pc0.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Using Nessus, run a scan(with no credentials) on the VM using the IP address:  <br/>
<img src="https://imgur.com/n0Co73k.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
After scan this is the screen you will get, showing any vulnerabilities on the VM. Since this is a fresh VM there are only a few:  <br/>
<img src="https://imgur.com/FtxnveW.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Allow the VM to run a scan with credentials: <br/>
<img src="https://imgur.com/aRxImxL.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
With a credential scan there are a lot more vulnerablility problems as with have allowed the computer to scan more of the VM: <br/>
<img src="https://imgur.com/G1jG9rO.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Download an old version of FireFox onto VM to test for new vulnerbilities: <br/>
<img src="https://imgur.com/eV8TA9c.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
After running scan again with old software there are a lot more vulnerabilities that Nessus shows us: <br/>
<img src="https://imgur.com/X5WRQ9Q.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
Uninstalled FireFox and updated Windows: <br/>
<img src="https://imgur.com/6i58es6.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
<br />
<br />
AFter uninstalling the old software and updating Windows there are fewer vulnerabilities on the computer: <br/>
<img src="https://imgur.com/5GA3Pwn.png" height="80%" width="80%" alt="Nessus Vulnerability Steps"/>
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
