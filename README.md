Network Mapping & Ping Test
Student Information

Name: sthokozile londiwe nxele
Course: bits and bytes
Date: 23 February 2026
Operating System: Microsoft Windows 10 (Version 10.0.19045.6456)
Connection Type: Wi-Fi

Introduction

This practical task focuses on mapping my home network and testing connectivity using basic networking tools. Computer networks operate using the TCP/IP model, which consists of four layers: Application, Transport, Internet, and Network Access. The Internet Protocol (IP) assigns unique IP addresses to devices so they can communicate within a network. DNS (Domain Name System) translates domain names such as google.com into IP addresses, making it easier to access websites. Routing allows data packets to move between different networks through a router, also known as the default gateway. The ping command is used to test communication between devices, measure response time (latency), and check for packet loss. In this task, I used the ipconfig command to collect my network configuration details and the ping command to verify connectivity between my device, the router, and external internet servers.

Network Information (ipconfig Results)

Command used:

ipconfig
<img width="1600" height="900" alt="ipconfig" src="https://github.com/user-attachments/assets/a759a937-efe3-4e8f-83b4-25180260bc5b" />



Active Adapter: Wi-Fi

IPv4 Address: 172.20.7.88

Subnet Mask: 255.255.254.0

Default Gateway: 172.20.6.1

Explanation

The IPv4 address 172.20.7.88 identifies my laptop within the local network.
The subnet mask 255.255.254.0 defines the network range and determines which devices are in the same network.
The default gateway 172.20.6.1 is the router that connects my local network to the internet.

Network Diagram
                     
![Uploading BCO.8b172a72-da00-497b-9231-a607a54992cd.png…]()

Ping Test Results
1. Ping to 8.8.8.8

Command used:

ping 8.8.8.8
<img width="1600" height="900" alt="ping" src="https://github.com/user-attachments/assets/6a7ce420-56d3-4655-a3fe-6600ed1ba235" />



Results:

Packets Sent: 4

Packets Received: 4

Packet Loss: 0%

Minimum Time: 2ms

Maximum Time: 4ms

Average Time: 2ms

2. Ping to google.com

Command used:

ping google.com
<img width="1600" height="900" alt="google  com" src="https://github.com/user-attachments/assets/6f34baf1-b98b-463d-8683-75cf89f4b8aa" />



Resolved IP Address: 142.251.47.14

Results:

Packets Sent: 4

Packets Received: 4

Packet Loss: 0%

Minimum Time: 2ms

Maximum Time: 3ms

Average Time: 2ms

Analysis

The ping results show 0% packet loss, indicating a stable and reliable network connection. The low latency (average of 2ms) suggests that the internet connection is fast and responsive. The successful ping to 8.8.8.8 confirms that my device can reach external internet servers. The ping to google.com resolved the domain name to the IP address 142.251.47.14, demonstrating that DNS is functioning correctly. Routing works as expected because data travels from my laptop to the default gateway (172.20.6.1) and then through the ISP to reach external servers.

Conclusion

This practical task confirmed that my home network is properly configured and functioning correctly. My device has a valid IP address, subnet mask, and default gateway. Internet connectivity is successful with no packet loss and very low latency. DNS resolution and routing are working effectively. Overall, this demonstrates how IP addressing, DNS, routing, and the TCP/IP model operate together to enable communication across networks.
