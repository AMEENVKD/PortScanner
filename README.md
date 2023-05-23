# PortScanner

A port scanner is a software tool used to identify open ports on a target device or network. Ports are communication endpoints that allow computers and devices to send and receive data over a network. A port scanner sends requests to specific ports on a target system to determine if they are open or closed.

Port scanning is often performed for security assessments and network troubleshooting purposes. It helps identify potential vulnerabilities or misconfigurations that could be exploited by attackers. By scanning a target system, administrators can assess its security posture and take appropriate measures to mitigate risks.

Port scanners can employ different scanning techniques, including:

TCP Connect Scan: This method establishes a full TCP connection with the target port. If the connection is successful, the port is considered open; otherwise, it is closed or filtered.

SYN/Stealth Scan: This technique sends SYN packets to the target ports without completing the TCP handshake. It analyzes the response received to determine if the port is open or closed.

UDP Scan: UDP ports are often used by certain services, and a UDP scan helps identify open UDP ports by sending UDP packets and analyzing the responses.

XMAS Scan: In an XMAS scan, specific flags (FIN, URG, and PSH) are set in the TCP packet sent to the target ports. The response received helps determine if the port is open, closed, or filtered.

Port scanners provide valuable information about a target system's network security posture. However, it's essential to use port scanning tools responsibly and with proper authorization, as unauthorized port scanning can be considered intrusive and potentially illegal.




