<h1>SIEM | Azure Sentinel MAP Tutorial</h1>




<h2>Description</h2>
<b>In this lab, I created an Azure Sentinel SIEM and set up a virtual machine to act as a honey pot. Using IPGeolocation, PowerShell, and Azure Sentinel we are able to view live RDP attacks from across the globe.


</b>
<br />
<br />
By utilizing the Powershell script we are able to take Windows Event Log information combined with the IPGeolocation API and make a live map in Azure Sentinel. By turning off the firewall and making the VM vulnerable, its an interesting way to see how quickly people attack vulnerable systems. 
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/bYRCGOm.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Bulk of attacks came from Pakistan; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/oXJm77l.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks within minutes of being implemented in Microsoft Azure Sentinel. (built custom logs including geodata and workbook)</h2>

<p align="center">
<img src="https://i.imgur.com/fN9Fh1E.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
