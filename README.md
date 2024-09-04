
# OSPF Palo Alto

<h2>Description</h2>
In this hands-on lab, we will configure OSPF routing to allow devices from the inside to communicate, I have also configured loopback addresses which will be set to passive mode on the palo alto firewall. The objectives of this task is to enable OSPF, so that the neighbouring routes and the Palo Alto device can communciate. Before enabling OSPF on Palo Alto, I will first ensure to configure the routers to allow both routers to exchange routes respectively. Its important to make sure that all interfaces including the loopback addresses are assigned to the same zone. Similiarly, the router id and area number for the Palo alto will also be required to be configured to understand its neighbouring routes. 

<br />

<h2>Languages and Utilities Used</h2>

- <b> Eve ng </b> 
- <b>VM Workstation </b>
- <b> Palo Alto Firewall </b>

<h2>Environments Used </h2>

- <b> Vm Workstation Pro </b> 

<h2>Program walk-through:</h2>

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/TEqiUgg.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/xXxOfBP.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/kAeO2kz.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/oIiyJhs.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/0GAI0y1.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src= https://i.imgur.com/j94wt1p.png height="80%" width="80%" alt="Palo Alto OSPF"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
