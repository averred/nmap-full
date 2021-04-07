# nmap-full
## Introduction
`nmap-full` is a simple bash script to quickly scan all TCP ports on a host using nmap then perform a detailed slow scan on the results of the quick scan.

### Why?
When conducting the **Active Reconnaissance** or **Discovery** stage on a single host, traditional full nmap scans can take a while to come back with results. 

`nmap-full` returns the open TCP ports quickly so you can get started on investigating low hanging fruit while the full nmap scan enumerates your target further. The script was designed with CTF platforms such as HackTheBox.eu in mind, YMMV in real world use with IDS/IPS.


## Usage
    $ nmap-full <host>

## Pull requests
Pull requests welcome as long as they do not severely impact the speed of the initial scan.
