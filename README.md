# Common-Tools
Common tools that are used in networking
#
One can use a variety of network tools to perform tasks such as obtaining information about other systems on your network, accessing other systems, and communicating directly with other users. Network information can be obtained using utilities such as ping, ipconfig, tracret, host, nslookup etc.
#
`ping`
The PING command is used to check if a remote system is running or up. In short this command is used to detect whether a system is connected to the network or not. It's used a lot in troubleshooting to check connectivity between two points

`nslookup`
The NSLOOKUP command is used to troubleshoot network connectivity issues in the system. Using the nslookup command, we can access the information related to our system’s DNS server, i.e., domain name and IP address. It's primarily used when you want to figure out what a machine's address is if you know the name, or what the name is if you know the IP address

`arp`
The ARP command is used to access the mapping structure of IP addresses to the MAC address. This provides us with a better understanding of the transmission of packets in the network channel.

`ipconfig`
The IPCONFIG network command provides a comprehensive view of information regarding the IP address configuration of the device we are currently working on.

- ipconfig (ifconfig on mac/linux) - primary function is to show the network's IP addressing and congifuration 
- ipconfig /all - shows even more adapter information (including DNS information)
- ipconfig /displaydns - shows the dns cache (list of names to IP mappings that your computer is keeping track of)
- ipconfig /renew - Used to renew the system’s IP address.
- ipconfig /release - Removes the system’s current IP address.

`netstat`
The NETSTAT command as the name suggests displays an overview of all the network connections in the device. The table shows detail about the connection protocol, address, and the current state of the network.
