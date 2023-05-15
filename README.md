
<h1>AZURE-SIEM setup</h1>
<p align="center">
<b> ###🔷 Practice for Blue Team 🔷##</b>
 </p>
<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We observed live attacks (RDP Brute Force) from all around the world. We will use a custom PowerShell script to look up the attackers Geolocation information pulling the information from https://ipgeolocation.io/(with a dedicated key) and plot it on the Azure Sentinel Map!

<h2>Layout Example</h2>
<p align="center">
 <br/>
<img src="https://github.com/AnnaleaLayton/PICTURES-PRIVATE/blob/b850ef0a9220c52cedda9ed4a6faf9c0f6fc7716/Screenshot%20-%20layout.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Microsoft Sentinel</b>
- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Mac OS & Windows 11</b>
- <b>Windows 10 Azure VM</b> (21H2)

<h2>Walk-Through:</h2>

<p align="center">
Set up Virtual machines - Windows 10 PRO Azure <br/>
<img src="https://github.com/AnnaleaLayton/PICTURES-PRIVATE/blob/b850ef0a9220c52cedda9ed4a6faf9c0f6fc7716/Screenshot%20-%20VM%20creation.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h1></h1>
  
<p align="center">
Log to Pull users from Vm <br/>
<img src="https://github.com/AnnaleaLayton/PICTURES-PRIVATE/blob/b850ef0a9220c52cedda9ed4a6faf9c0f6fc7716/Screenshot%20-%20LOG%20created%20for%20VM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h1></h1>
  
<p align="center">
RDP World Map - Login Failurs <br/>
<img src="https://github.com/AnnaleaLayton/PICTURES-PRIVATE/blob/b850ef0a9220c52cedda9ed4a6faf9c0f6fc7716/Screenshot%20-%20Map%20of%20all%20failed%20RDP%20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
