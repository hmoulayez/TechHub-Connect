# TechHub-Connect
Welcome to the TechHub Connect Network Simulation project! This project aims to simulate a small to medium-sized enterprise network, incorporating essential network services and remote management capabilities for the machine room
Overview
TechHub Connect is a fictional company that requires a robust and secure enterprise network infrastructure. The network consists of multiple locations, including the Office and the Factory. The Office encompasses the IT VLAN and the production VLAN, while the Factory houses the server room with production machines. The Office is connected to a Cisco 1700 series router. Both the Office and the Factory are connected to the Edge Router, a Cisco 2600 series router as well. The Edge Router further connects to the ISP Router, a Cisco 2800 series router, which serves as the gateway to the internet.

## Network Services
The TechHub Connect network includes the following essential services:

Telephony Service: Cisco 7912 IP phones are deployed at both the Office and the Factory, providing internal communication capabilities.
Mail Service: An internal mail server is set up to facilitate email communication within the organization.
Web Server: A dedicated web server is hosted within the network, allowing the company to have an online presence.
Internal DNS Server: The network includes an internal DNS server to resolve domain names for internal resources.
Remote Management and Monitoring
The project also focuses on remote management and monitoring of the server room at the Factory. The server room is equipped with cameras for surveillance, temperature control systems, and light intensity monitoring. This allows remote monitoring and control of the server room environment, ensuring optimal conditions for the production machines.

## Configuration and Usage
To access the network equipment and services, SSH or Telnet protocols can be used. However, access to the equipment is limited to the IT VLAN for security reasons. Follow the steps below to access the devices:

* Connect to the network using a device connected to the IT VLAN.
* Open an SSH or Telnet client.
* Enter the IP address of the target device (router or switch) to establish a connection.
* Provide the appropriate login credentials (username and password) for authentication.
* Once authenticated, you will have access to the command-line interface (CLI) of the device.
Note: It is recommended to use SSH for secure remote access. Telnet should only be used if necessary and in a controlled environment.

Make sure to adhere to the network security guidelines and protect the access credentials to prevent unauthorized access to the network equipment.

## Contribution


## License
