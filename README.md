This is a set of scripts to display networking information. I wrote these for my Linux Administration course.

The script labeled "Ubuntu" is intended for use with an Ubuntu server.
It performs a few general tests, and prints what I believe to be relevant network information.

It starts with displaying all network interfaces via the "ip a" command. Then it runs two ping tests, one with
an IP address and one with a domain name. These tests help troubleshoot basic network connectivity issues. 
The next command prints the units routing table, also for general troubleshooting. After routing, the script
prints any active TCP ports which is useful for determining if there are any unauthorized connections. Finally,
The script outputs the DNS server information for the server. This is useful in case the server has any issues
resolving domain names, which I've run into a few times during the course of the course.

CentOS to be added.
