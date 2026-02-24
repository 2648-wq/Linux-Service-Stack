# Linux-Service-Stack
This repository documents a simulated enterprise network environment. It includes the setup and configuration of essential Linux servers: DHCP for IP allocation, DNS for domain resolution, FTP for file transfer, and HTTP for web services. Also features firewall rules and gateway configuration.

Due to the limitations of the H3C simulator's server components, all devices labeled as 'servers' (e.g., FTP, DNS) in the diagram are simulated using router devices. They are used solely for building the network topology and IP connectivity testing. All actual application services (such as vsftpd, bind9, httpd) are deployed and configured on an external Linux virtual machine.
