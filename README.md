<h1>Group Policy Management Home Lab: Creating and Setting up GPO </h1>



<h2>Description</h2>
In this lab, we will then delve into Group Policy Management to master the fundamental differences between computer and user configurations, as well as the nuances between rigid policies and flexible preferences. To apply this knowledge, we will architect and implement five specific Group Policy Objects designed to secure and automate the network. This includes enforcing strong security via a Password Policy, automating resource access with a Drive Mapping Preference, and standardizing the user experience through a Desktop Wallpaper Policy. Finally, we will harden the infrastructure by restricting access to the Control Panel and disabling USB storage devices to prevent unauthorized system changes and data exfiltration.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Virtualization: Proxmox VE </b> 
- <b>Operating System: Windows Server 2025</b>
- <b>Identity Management: Active Directory Domain Services (AD DS)</b>
- <b>Drivers: VirtIO Guest Tools for optimized VM performance</b>
   

<h2>Environments Used </h2>

- <b>Windows 11 Enterprise (21H2): Client workstation for domain joining and GPO testing </b> (21H2)
- <b>Windows Server 2025: Primary Domain Controller (DC) </b>

<h2>Program walk-through:</h2>

<p align="center">
Setting up a GPO called Password Policy and and setting the password policies for it.    <br/>
<img src="https://i.imgur.com/9dKbLeZ.png" height="80%" width="80%" alt="installing OS"/>
  <br />
<img src="https://i.imgur.com/lSHjyRQ.png" height="80%" width="80%" alt="installing OS"/>


<br />
<br />
Setting up a GPO called Drive Mapping and to create a shared drive that is assigned as an letter that users can connet to  :  <br/>
<img src="https://i.imgur.com/MvNzeqC.png" height="80%" width="80%" alt="installing OS"/>
<img src="https://i.imgur.com/NbSBlF2.png" height="80%" width="80%" alt="installing OS"/>
<img src="https://i.imgur.com/xNRNyvn.png" height="80%" width="80%" alt="installing OS"/>
<br />
<br />
Setting up a GPO called Desktop Wallpapers which will be set to stop users from changing the wallpapers: <br/>
<img src="https://i.imgur.com/S4jM6wx.png" height="80%" width="80%" alt="instaling AD"/>
<img src="https://i.imgur.com/G7gisgv.png" height="80%" width="80%" alt="instaling AD"/>
<br />
<br />
Setting up a GPO called Restrict  Control panel which will restrict users other then admin from gaining access:  <br/>
<img src="https://i.imgur.com/uJZ1dqW.png" height="80%" width="80%" alt="DC creation"/>
<img src="https://i.imgur.com/dwC0OgF.png" height="80%" width="80%" alt="DC creation "/>
<img src="https://i.imgur.com/FkYdu6t.png" height="80%" width="80%" alt="DC creation "/>
<br />
<br />
  Setting up a GPO called Restrict  Control panel which will restrict users other then admin from gaining access:  <br/>

 <b> In progress 2/25/26 </b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
