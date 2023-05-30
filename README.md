# Nmap Tutorial
Nmap (Network Mapper) is a powerful open-source network scanning tool used for network exploration and security auditing. It allows you to discover hosts, services, and vulnerabilities within a network.
#
*Here's a basic tutorial to help you get started with Nmap:*
#
### Install Nmap
Nmap is available for various operating systems such as Windows, macOS, and Linux. You can download it from the official Nmap website (https://nmap.org/download.html) or install it through package managers like apt, yum, or brew, depending on your operating system.
#
### Scan a Single Host
To scan a single host, open a terminal or command prompt and use the following command:
```
nmap <target>
```
Replace < target > with the IP address or hostname of the host you want to scan. For example:
```
nmap 192.168.1.1
```
This command will perform a default set of scans on the target host.
#
### Scan a Range of Hosts
If you want to scan a range of hosts, you can specify an IP address range. For example:
```
nmap 192.168.1.1-10
```
This command will scan all hosts in the range from 192.168.1.1 to 192.168.1.10.
# Scan a Specific Port
By default, Nmap scans the most common 1,000 ports. If you want to scan a specific port or a range of ports, you can use the -p option. For example:
```
nmap -p 80 192.168.1.1
```
This command will scan only port 80 on the target host.
#
