<h1>Azure Sentinel Map with Live Cyber Attacks</h1>

 ###

<h2>Description</h2>
SIEM systems have become an essential component of modern cybersecurity strategies, as they help organizations to comply with regulatory requirements, enhance their risk management capabilities, and protect their valuable assets. With the increasing sophistication of cyber threats and the growing complexity of IT infrastructures, SIEM solutions have become more important than ever.
<br />

<h2>Languages and Tools</h2>

- <b>Sentinel (SIEM)</b> 
- <b>Azure Virtual Machine</b>
- <b>Log Analytics Workspace</b>
- <b>PowerShell</b>

###

<h2>Environments Used </h2>

- <b>Windows 10</b>

###
<h2>Project walk-through:</h2>

<p align="center">
<br/>
Log in Azure <br/>
<img src="https://imgur.com/HIZ6AVy.gif"height="80%" width="80%" alt="Azure" />
<br />
<br />
Set up Virtual Machine, Log Analytics and Microsoft Sentinel  <br />
<img src="https://imgur.com/GcECczO.gif" height="65%" width="80%" alt="Virtual Machine"/>
<br />
<img src="https://imgur.com/gYccEqW.gif" height="65%" width="80%" alt="Log Analytics"/>
<br />
<img src="https://imgur.com/wy5eamr.gif" height="65%" width="80%" alt="Microsoft Sentinel"/> <br />
<br />
<br />
Go to Microsoft Defender for Cloud and set as follow <br/>
<img src="https://imgur.com/E75oyMK.gif" height="65%" width="80%" alt="Microsoft Defender for Cloud"/>
<img src="https://imgur.com/8yof7PF.gif" height="65%" width="80%" alt="Microsoft Defender for Cloud"/>
<br />
<br />
Connect Virtual Machine By IP Address:  <br/>
<img src="https://imgur.com/mCD5TXg.gif" height="65%" width="80%" alt="Connect Virtual Machine"/>
<br />
<br />
Go to Remote Desktop Connection on Window and put in the IP address provided <br />
<img src="https://imgur.com/3XuOYic.gif" height="65%" width="80%" alt="Remote Desktop Connection"/>
<br />
<br />
Go into Microsoft Firewall and set everything to off (expose to everyone)  <br/>
<img src="https://imgur.com/hVMWjAH.gif" height="65%" width="80%" alt="Microsoft Firewall"/>
<br />
<br />
Go to Powershell ISE and run the script (NOTE: use your API Key)  <br/>
<img src="https://imgur.com/cRWUfk6.gif" height="65%" width="80%" alt="Disk Powershell"/>
<br />
<br />
Go to Log Analytics to create custom log <br />
<image src="https://imgur.com/afcWMxa.gif" height="65%" width="80%" alt="Custom Log"/>
<br />
<br />
Go to Log in Log Analytic and run query <br />
<image src="https://imgur.com/w4aXEKX.gif" height="70%" width="80%" alt="Query"/>
<br />
<br />
Extract fields for better analysis <br />
<img src="https://imgur.com/p2PX7tJ.gif" height="65%" width="80%" alt="Extract Fields"/>
<br />
<br />
Go to Azure Sentinel and run the query to get data for analysis <br />
<img src="https://imgur.com/KRd77OU.gif" height="65%" width="80%" alt="Sentinel" />
<br />
<br />
Continue setting your views <br />
<img src="https://imgur.com/Gd81fSa.gif" height="65%" width="80%" alt="Sentinel" />
<br />
<br />
Enjoy your live cyber attacks from around the world:  <br/>
<img src="https://imgur.com/XLOnfQP.gif" height="65%" width="80%" alt="Cyber Attack"/>
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
