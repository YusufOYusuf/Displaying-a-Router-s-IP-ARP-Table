<h1>Displaying a Router's IP ARP Table</h1>



<h2>Description</h2>
In this lab, I learned to display a router's IP ARP(address Resolution Protocol) table. The IPv4 ARP table lists the IPv4 address and matches the MAC(media access control) address of hosts connected to the same subnet as the router. When forawarding a packet to a host on the same subnet, the router encapsulates the packet with destination MAC address as found in the  ARP table.
<br />



<h2>Environments Used </h2>

- <b>Ubuntu 20.04.2 LTS</b> 

<h2>Languages and Utilities</h2>

- <b>PuTTY SSH Client</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop open PuTTY SSH Client: <br/>
<img src="https://i.postimg.cc/6QXmmzbH/Screen-Shot-2022-06-23-at-2-43-35-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br>
In The PuTTY Configuration dialog box type in
<br>1. Host Name as 172.16.43.129
<br>2. Type Port as 5000
<br>3. Connection type as Telnet
<br>4. Click Open to open up terminal window
<img src="https://i.postimg.cc/VLHRt4cS/Screen-Shot-2022-06-23-at-2-49-59-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
In the R1 terminal window, type command "en" to enter into enable mode:</br>
<img src="https://i.postimg.cc/0NNKC1dP/Screen-Shot-2022-06-23-at-2-51-23-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
in the R1 terminal window type "show ip arp" then enter to to display ARP cache:  <br/>
<img src="https://i.postimg.cc/cLPGFQfC/Screen-Shot-2022-06-23-at-2-53-39-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />


<br />
Displayed ARP cache:  <br/>
<img src="https://i.postimg.cc/9f48NKcH/Screen-Shot-2022-06-23-at-2-59-15-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />




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
