<h1>Active Directory Home Lab</h1>

<h2>Description:</h2>
In this home lab, I set up Active Directory using Oracle VirtualBox. A Windows Server VM was configured as the domain controller, and Active Directory Domain Services was installed. I created a Windows 10 client VM to join the domain, simulating real-world user management. This setup provided hands-on experience in managing a domain, including user and network management, in a virtualized environment.
<br />

<h2>My Thought Process:</h2>

<p align="center">
  <br/>
I began by setting up the server's IPV4 <br/> address & DNS server settings.
  <br/>
<img src="https://i.imgur.com/wTFpKFV.png" style="height: auto; width: 300px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
Next I used the 'Add Roles and Features Wizard' to <br/> install Active Directory Domain Services.
  <br/>
<img src="https://i.imgur.com/VQuADcS.png" style="height: auto; width: 500px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
I then created an Organizational Unit for both <br/> standard and admin users.
  <br/>
<img src="https://i.imgur.com/UXmoT7L.png" style="height: auto; width: 450px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
I added 2 users, 'Test1' and 'Josh Yerdon', simulating an actual network enviornment.
  <br/>
<img src="https://i.imgur.com/fLlr0Yj.png" style="height: auto; width: 450px;"/><img src="https://i.imgur.com/XwsJiVg.png" style="height: auto; width: 445px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
After this, I began giving 'Domain Admins' privileges to myself.
  <br/>
<img src="https://i.imgur.com/kFiJJIS.png" style="height: auto; width: 450px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
I installed the Remote Access role & configured Routing and Remote Access <br/> to use NAT, allowing internal devices to access external networks.
  <br/>
<img src="https://i.imgur.com/tYapxvM.png" style="height: auto; width: 314px;"/><img src="https://i.imgur.com/MKjcxJE.png" style="height: auto; width: 375px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
Following this, I installed the DHCP role to automatically assign IP addresses to devices in the network, <br/> set the IP address scope and assigned the router IP. 
  <br/>
<img src="https://i.imgur.com/OM1zfYD.png" style="height: auto; width: 313px;"/><img src="https://i.imgur.com/ijlPtin.png" style="height: auto; width: 278px;"/><img src="https://i.imgur.com/Q7IxND0.png" style="height: auto; width: 279px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
I then enabled Routing and Remote access so that the Windows client would have an internet connection.
  <br/>
<img src="https://i.imgur.com/8nOS6k1.png" style="height: auto; width: 600px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
On a client PC, I ran ipconfig and ping to confirm a connection. <br/> I also renamed the PC for consistency with the domain.
  <br/>
<img src="https://i.imgur.com/xogjd0D.png" style="height: auto; width: 350px;"/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
Finally, I verified in DHCP > Address Leases that devices were assigned <br/> IPs within the configured range.
  <br/>
<img src="https://i.imgur.com/xoPj4N8.png" style="height: auto; width: 700px;"/>
  
