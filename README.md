
<h1>Private-Secure-VPN</h1>



<h2>Description</h2>
In this Project, I will show how I set up my own self-hosted WireGuard Virtual Private Network (VPN) server with a website based User Interface (UI) sign in page to manage VPN clients as an admin.  WireGuard VPN will be installed using WireGuard Easy (wg-easy) GitHub repository using an Ubuntu Linux based cloud server also known as a Virtual Private Server (VPS). I will also use Docker and Bcrypt's password hasher to run wg-easy and hash your web UI sign in password for enhancing password security. WireGuard is a cross-platform opensource VPN that utilises cryptography in its protocol. DigitalOcean will be the VPS host provider used in this demonstration. It offers cloud servers through a service called Droplets.I will also be using a domian that points to the vps for the wg-easy Ui landing page.
<br />


<h2>Whats Needed</h2>

- <b>WireGuard</b> 
- <b>Server host</b>
- <b>Domain</b>
- <b>PuTTY</b>



<h2> The Steps:</h2>

<p align="center">
Purchacing Virtual private server : <br/>
<img src="https://i.imgur.com/Mo5nLOR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 <b>To start I used a vps provider (Oceandrop) to purchace some cloud computing. I chose a basic plan with regular ssd and 1gb memory priced at 6$ a month. I set the server location to New York city. I selected the latests version of ubuntu for the vps. And chose password as Authentication method and set the password for the vps

</b>
 
 <br />
 
<br />
Select the disk:  <br/>
<img src="(https://imgur.com/a/TGNILkw)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
