<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240610151132/Networks-and-Process-of-Network-Communications.webp"/>
</p>

<h1>Network Communication</h1>
This tutorial displays how two machines communicate over a shared network using wireshark.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark Software

<h2>Operating Systems Used </h2>

- Windows 11 Pro
- Ubuntu Pro

<h2>Network Observation Stages</h2>

- Capture
- Filter
- Ping
- Observation

<h2>Lifecycle Stages</h2>

<p>
<img width="1132" height="877" alt="Screenshot 2025-08-11 145258" src="https://github.com/user-attachments/assets/05a046a8-70d4-4b37-85a0-d865e077f377" />

</p>
<p>
-Launch wireshark on machine within a network.

- At the top right click the blue sharkfin icon to begin capturing.
</p>
<br />

<p>
<img width="1133" height="874" alt="Screenshot 2025-08-11 145315" src="https://github.com/user-attachments/assets/def72743-7fc1-45bc-945c-ca04f25061c1" />

</p>
<p>
You will notice a steady flow of information constantly being produced within the interface. This is ALL the communication currently going on with that particular machine.
</p>
<br />

<p>
<img width="1137" height="879" alt="Screenshot 2025-08-11 145426" src="https://github.com/user-attachments/assets/ddf2bd7d-2c55-4fde-b2a2-c1393fa7aaf3" />

</p>
<p>
within the searchbar near the top, filter the traffic for icmp(Internet Control Message Protocol) only. In doing this you will notice that there is no traffice available.
</p>
<br />

<p>
<img width="1715" height="904" alt="Screenshot 2025-08-13 150257" src="https://github.com/user-attachments/assets/9b738960-212e-4742-9fd4-6e75dd617724" />

</p>
<p>
Collect the private ip of another machine on the network and open command prompt. Within command prompt ping that private ip. 
</p>
<br />

<p>
<img width="1918" height="1000" alt="Screenshot 2025-08-11 145749" src="https://github.com/user-attachments/assets/2210a3dd-250f-4ddd-8dd1-012c13916ceb" />

</p>
<p>
After pinging the next machine, you can see within wireshark that for each packet there was communication carried out between the two machines.
</p>
<br />


