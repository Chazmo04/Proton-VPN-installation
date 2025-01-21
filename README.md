<p align="center">
<img src="https://play-lh.googleusercontent.com/hferjPeJ9_aWi_r5t8L0qOAwU4ZWAyduYmRkYodJOylRKwOxPI_117GzVSkAnhaNOw=w240-h480-rw" alt="Proton VPN logo"/>
</p>

<h1> Proton VPN Instalation In Azure VM/Home PC </h1>
This tutorial describes the prerequisites needed for installing protonvpn on your Azure Virtual Machine or Home PC.<br />

<h2>Environments and Websites Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Whatismyipaddress.com
- protonvpn.com

<h2>Operating Systems Used </h2>

- Windows 10 Pro version </b> (22H2) -x64 Gen2

<h2>Steps</h2>




<p>
<img src="https://i.imgur.com/2F3s9Ws.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If your looking to provide a VPN for your Virtual Machine create your VM first
</p>
<br />

<p>
<img src="https://i.imgur.com/7gbkdeV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make any specifications to your Resource Group, Virtual Name, Region, Image, and Size to your desire 
</p>
<br />

<p>
<img src="https://i.imgur.com/hfluWhS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create your username and password and check the box under licensing or the VM won't launch
</p>
<br />

<p>
<img src="https://i.imgur.com/qiXePaV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Along with your Network Interface if any other specifications need to be made for your VM do so before creating
</p>
<br />

<p>
<img src="https://i.imgur.com/0DKvr1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create your VM
</p>
<br />

<p>
<img src="https://i.imgur.com/GwmsRqp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/3YopXkL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before we Log into your VM we need the Public IP Address. Highlight and copy the IP Address
</p>
<br />

<p>
<img src="https://i.imgur.com/c1JHVSo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into your VM with the public IP address we copied and insert into Remote Desktop Protocol (RDP)
</p>
<br />

<p>
<img src="https://i.imgur.com/HGuqjbe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use the password that you made when you created your VM</p>
<br />

<p>
<img src="https://i.imgur.com/1dUAShv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Yes and log in
</p>
<br />

<p>
<img src="https://i.imgur.com/ApVrIrW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As you can see we are in our VM as displayed from CMD prompt</p>
<br />

<p>
<img src="https://i.imgur.com/CEvFaed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before we install ProtonVPN view the website whatismyipaddress.com to see you IP Address. As we can see our IP Address is the same one that was created in Azure with the region selected</p>
<br />

<p>
<img src="https://i.imgur.com/aIR83kO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now let's go to Protonvpn.com and install</p>
<br />

<p>
<img src="https://i.imgur.com/OPzGGDQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Protonvpn offers different tiered subscriptions for there services but for this tutorial were going to select the free version</p>
<br />

<p>
<img src="https://i.imgur.com/3QOs4Wn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create an Account</p>
<br />

<p>
<img src="https://i.imgur.com/chRBa7n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Downloading to the operatring system of your choosing</p>
<br />

<p>
<img src="https://i.imgur.com/YAefknu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>

<img src="https://i.imgur.com/dmfoQh9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the download is complete click "open file" or click on the file folder</p>
<br />

<p>
<img src="https://i.imgur.com/GTnzqa6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go through the installation steps</p>
<br />

<p>
<img src="https://i.imgur.com/wTU60NN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/kr64yhI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/AH8Hckj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once installation is complete login to your account</p>
<br />

<p>
<img src="https://i.imgur.com/qyR12UD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/yxRZUOL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that were logged into our account connect to a VPN server</p>
<br />

<p>
  <img src="https://i.imgur.com/M6awjWb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we connect to a server when we check whatismyipaddress.com again we can see that out ip address has changed indicating that the vpn is working properly </p>
<br />
