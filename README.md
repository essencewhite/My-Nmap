<p align="center">
    <img src="https://user-images.githubusercontent.com/88567404/217352522-035374b7-e3c0-4fdf-b222-d099c2d77d69.png"/>
    </p>

Nmap is a network scanning tool used to discover hosts and services on a computer. It scans the network a computer is connected to and creates a lists of ports, devices names, operating systems, running services, etc. Network data packets are sent to devices and services on the network and Nmap analyzes the responses. 

# Typical Uses of Nmap
* Examine the security of a device or firewall by identifying the network connections which can be made to, or through it
* Identifying open ports on a target device
* Network mapping and network inventory
* Examine the security of a network by identifying new servers
* Generating traffic to hosts on a network, response analysis and response time measurement
* Finding and exploiting vulnerabilities in a network

# WARNING
**NMAP is to be used at your own risk. Always get permission before doing a port scan. We do not encourage, endorse, nor condone the stealing of data, intrusion of networks, and other malicious behavior**

Reduce your risk by reading this [Nmap Legal Guide](https://nmap.org/book/legal-issues.html) before using Nmap.

# Installation
Nmap can be used with Linux, Mac OS, Windows, and many UNIX platforms (Solaris, Free/Net/OpenBSD, etc.)

Download [Nmap](https://nmap.org/download.html)

[Nmap Installation Guide](https://nmap.org/book/install.html)

Nmap already comes installed on most Linux distributions. To check if Nmap is installed use:

```
nmap --version
```

## Uninstall Nmap
For any reason you wish to uninstall Nmap, you can follow this [Removing Nmap Guide](https://nmap.org/book/inst-removing-nmap.html)

# Documentation
The primary documentation for using Nmap is the [Nmap Reference Guide](https://nmap.org/docs.html). It is regularly updated for each release and is meant to serve as a quick-reference to virtually all Nmap command-line arguments, but you can learn even more about Nmap by reading it straight through.

# Nmap Scripting Engine (NSE)
One of Nmap's most exciting new features is the [Nmap Scripting Engine](https://nmap.org/book/nse.html), which extends Nmap's functionality using the simple and efficient Lua programming language. Nmap includes about 50 valuable scripts for network discovery and vulnerability detection, and you can also write your own. We describe the system in depth (from simple usage instructions to writing your own scripts) in our NSE guide. 

We also have an [NSE Documentation Portal](https://nmap.org/nsedoc/) which includes detailed documentation for every NSE script and library.

# Help
Like its author, Nmap isn't perfect. But you can help make it better by sending bug reports or even writing patches. If Nmap doesn't behave the way you expect, first upgrade to the latest version available from https://nmap.org. 

If the problem persists, do some research to determine whether it has already been discovered and addressed. Try searching for the problem or error message on Google since that aggregates so many forums. If nothing comes of this, create an Issue on our tracker (http://issues.nmap.org) and/or mail a bug report to <dev@nmap.org>. 

If you subscribe to the nmap-dev list before posting, your message will bypass moderation and get through more quickly. Subscribe at https://nmap.org/mailman/listinfo/dev. Please include everything you have learned about the problem, as well as what version of Nmap you are using and what operating system version it is running on. Other suggestions for improving Nmap may be sent to the Nmap dev mailing list as well.

If you are able to write a patch improving Nmap or fixing a bug, that is even better! Instructions for submitting patches or git pull requests are available from https://github.com/nmap/nmap/blob/master/CONTRIBUTING.md

Particularly sensitive issues such as a security reports may be sent directly to Nmap's author Fyodor directly at <fyodor@nmap.org>. All other reports and comments should use the dev list or issue tracker instead because more people read, follow, and respond to those.

# Contributing
Information about filing bug reports and contributing to the Nmap project can
be found in the [HACKING](HACKING) and [CONTRIBUTING.md](CONTRIBUTING.md)
files.

# Licensing
Nmap is released under a custom license, which is based on (but not compatible
with) GPLv2. The Nmap license allows free usage by end users, and we also offer
a commercial license for companies that wish to redistribute Nmap technology
with their products. See [Nmap Copyright and Licensing](https://nmap.org/book/man-legal.html)
for full details.

The latest version of this software as well as binary installers for Windows,
macOS, and Linux (RPM) are available from
[Nmap.org](https://nmap.org/download.html)

Full documentation is also available
[on the Nmap.org website](https://nmap.org/docs.html).

Questions and suggestions may be sent to
[the Nmap-dev mailing list](https://nmap.org/mailman/listinfo/dev).
