Nmap (Network Mapper) is an open-source tool for network discovery, security auditing and port scanning. It identifies live hosts, open ports, service versions and operating systems by analysing packet responses.

Default usage: nmap <ip>

Flags:
	-sS: TCP SYN scan
	-sT: TCP Connect() scan
	-sA: TCP ACK scan
	-sW: TCP Window scan
	-sM: TCP Maimon scan

	-p <port ranges>: Only scans specified ports
	-F: Fast mode - scan fewer ports than default 
	-sV: probe open ports to determine service/version info
	-O: enable OS detection
	-T <0-5>: Set timing template (higher is faster)

	-6: Enable IPv6 scanning
	-A: Enable OS detection, version detection, script scanning and traceroute
	-V: Print version number