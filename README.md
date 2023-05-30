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
### Scan a Specific Port
By default, Nmap scans the most common 1,000 ports. If you want to scan a specific port or a range of ports, you can use the -p option. For example:
```
nmap -p 80 192.168.1.1
```
This command will scan only port 80 on the target host.
#
### Perform a Comprehensive Scan
To perform a comprehensive scan that includes more information about the target system, you can use the -A option. For example:
```
nmap -A 192.168.1.1
```
This command will enable OS detection, version detection, script scanning, and traceroute for the target host.
#
### Save Scan Results
If you want to save the scan results to a file, you can use the -oN option followed by the output file path. For example:
```
nmap -oN scan_results.txt 192.168.1.1
```
This command will save the scan results to a file named "scan_results.txt" in the current directory.
#
### Learn More about Nmap
Nmap offers numerous options and advanced features for network scanning. You can explore these features by referring to the Nmap documentation, available at https://nmap.org/book/man.html. The documentation provides in-depth explanations of Nmap commands, scan techniques, and scripting capabilities.
 
 Remember to use Nmap responsibly and ensure that you have proper authorization before scanning any network or system.
  
  I hope this tutorial helps you get started with Nmap! If you have any further questions, feel free to ask.
