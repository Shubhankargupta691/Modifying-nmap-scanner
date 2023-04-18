# Modifying-nmap-scanner

Nmap (Network Mapper) is a free and open-source tool used for network exploration, management, and security auditing. It is a very powerful scanner that can be used to discover hosts and services on a computer network, thus creating a "map" of the network. Nmap can be used to identify hosts and services on a network, as well as their operating systems, and detect open ports and vulnerabilities.

# REQUIREMENTS
 import nmap
 
# HOW To use:
 Enter the IP address  you want to scan.
 Enter the type of scan you want to run
     1) SYN ACK scan
     2) UDP Scan
     3) Comprehensive Scan
 
 When the scan completes it will display the collected information based on which type of scan you have selected.
 
 # SCANS Used in this project:
 
 # 1) SYN ACK scan
     A SYN ACK scan is a type of port scan that is used to determine which ports on a target system are open, closed, or filtered.
     This type of scan is also known as a TCP SYN ACK scan, or simply a SYN scan.

The SYN ACK scan works by sending a SYN (synchronize) packet to the target system on a specific port. If the port is open, the target system will respond with a SYN ACK (synchronize-acknowledge) packet. If the port is closed, the target system will respond with a RST (reset) packet. If the port is filtered, the target system will not respond at all.

By analyzing the responses from the target system, an attacker can determine which ports are open and which are closed or filtered. This information can be useful in determining the attack surface of a system, identifying potential vulnerabilities, and developing an attack plan.

It is important to note that SYN ACK scans can be detected by intrusion detection and prevention systems (IDS/IPS), firewalls, and other security measures. Additionally, using SYN ACK scans against systems that you do not have permission to scan is illegal and can lead to severe consequences.

# 2) UDP Scan
    A UDP (User Datagram Protocol) scan is a type of network scan used to identify open UDP ports on a target system.
    UDP is a connectionless protocol, and unlike TCP, there is no handshake process to establish a connection. 
    This makes UDP scans more difficult than TCP scans, as there is no confirmation that the packet has reached its destination.

    UDP scans work by sending a UDP packet to a specific port on the target system. If the port is open, the target system will respond with a UDP packet. If the port is       closed, the target system will respond with an ICMP (Internet Control Message Protocol) packet indicating that the port is unreachable. If the port is filtered, the         target system will not respond at all.

    UDP scans can be used to identify potential vulnerabilities in services that use the UDP protocol, such as DNS (Domain Name System), DHCP (Dynamic Host Configuration       Protocol), and SNMP (Simple Network Management Protocol). However, UDP scans are often less reliable than TCP scans, as they can be affected by network congestion,         packet loss, and other factors.

# 3) Comprehensive Scan
    
    A comprehensive scan is a type of network scanning technique that involves scanning an entire network for vulnerabilities, open ports, and other security issues. It is     a thorough and exhaustive process that aims to identify all potential weaknesses in a network and its devices.

    Here are some important points about a comprehensive scan:

    A comprehensive scan involves scanning all devices on a network, including servers, workstations, routers, switches, and other network devices.

    It can be time-consuming and resource-intensive, as it requires scanning all devices and ports on a network.

    A comprehensive scan can be performed using various tools and techniques, including vulnerability scanners, port scanners, and network mapping tools.

    The main advantage of a comprehensive scan is that it can help organizations identify all potential security vulnerabilities in their network, including misconfigured       devices, outdated software, and other weaknesses.

    A comprehensive scan can also help organizations meet regulatory compliance requirements, such as those related to the Payment Card Industry Data Security Standard (PCI     DSS).

    It is important to note that a comprehensive scan should only be performed with the permission of the network owner, as it can be disruptive and potentially harmful if     not performed correctly.
