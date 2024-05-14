<h1>Failed RDP to IP Geolocation Information</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=RoZeVbbZ0o0)

<h2>Description</h2>
The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
<br />
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell ISE:</b> Extract RDP failed logon logs from Windows Event Viewer 
- <b>Remote Desktop Protocol</b>
- <b>Windows Event Viewer</b>
- <b>Log Analytics Workspace</b>
- <b>Sentinel Workbook</b>
- <b>Azure</b>
- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)


<h2>Program walk-through:</h2>

- <b>TESTING</b>
- <b>Test another</b>

<h2>Attacks from China coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/LhDCRz4.jpeg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/krRFrK5.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
