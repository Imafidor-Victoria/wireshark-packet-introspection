# wireshark-packet-introspection
Cyber 500 packet introspection lab - wireshark analysis, GeoIP, TCP streams, FTP extraction
#Overview
This project analyzes multiple packet captures using Wireshark to identify:
Most active IPv4 and TCP flows
Directional traffic volumes (A→B vs B→A)
GeoIP location of remote hosts
Reassembled TCP streams
Hidden HTTP headers
FTP binary extraction using Follow TCP Stream
This lab demonstrates real-world packet investigation techniques used in cybersecurity operations and digital forensics.

Summary of Findings
4.1 – Packet Conversations
Most active IPv4 conversation: 24.6.173.220 ↔ 209.177.86.18
Traffic heavily asymmetric (A→B vs B→A)
4.2 – GeoIP Lookup
Remote host 24.6.181.160 located in Santa Clara, CA
682 packets, 711 KB of traffic
4.3 – TCP Reassembly
Extracted hidden header:
X-Slogan: "Sniffing the glue that holds the Internet together."
4.4 – FTP Data Extraction
File identified: pantheon.jpg
Reassembled as Raw binary from FTP data stream
🛠️ Tools Used
Wireshark
Labtainer VM
Oracle VirtualBox

Ubuntu Linux
