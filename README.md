# Ubuntu-20.04-Documentation
This document is intended as an instructional document for configuring Ubuntu Server 20.04. I will be configuring 2 virtual network adapters, one internal, and one external. I will be configuring the following services.

• DNS: I will be using BIND9 for address resolution for my internal network	
•	UFW: This is Ubuntu's built in firewall, IP Masquerading will be configured to allow clients on my internal network to communicate with the internet.
•	DHCP: I will be configuring Dynamic Host Configuration Protocol to dish out IP addresses for clients.
•	Squid: Squid is a transparent proxy server, that we will use to block traffic on the internal network.
