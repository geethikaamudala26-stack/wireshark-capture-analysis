## Network Traffic Analysis Using Wireshark

## Objective
To capture network traffic, filter packets by protocol, identify at least three network protocols, and save the captured traffic for further analysis.

## Tools Used
- Wireshark
- Npcap (if using Windows)
- Kali Linux or Windows
- An active network connection

## Procedure
1. Installed Wireshark from the official website.
2. Selected the active network interface and started packet capture.
3. Generated network traffic by browsing a website and/or pinging a server.
4. Captured traffic for approximately one minute and stopped the capture.
5. Applied display filters such as `dns`, `tcp`, `tls`, `udp`, and `icmp`.
6. Inspected packet headers, IP addresses, protocol names, packet lengths, and information fields.
7. Saved the capture as `network_traffic_analysis.pcap`.
8. Reopened the saved file to verify the captured packets.

## Observations

| No. | Protocol | Observed packet details |
|---|---|---|
| 1 | DNS | Enter the observed DNS query or response |
| 2 | TCP | Enter the observed ports and TCP flags |
| 3 | TLS / UDP / ICMP | Enter the actual protocol and packet details |

## Results
Network traffic was captured and examined using Wireshark. Display filters were used to isolate individual protocols, and packet header information was reviewed to understand the communication between network endpoints. The capture was saved for future analysis.

## Conclusion
This practical demonstrated the use of Wireshark for basic network traffic analysis. It provided experience in packet capture, protocol filtering, inspection of packet headers, and exporting network traffic for further investigation.

## Evidence
- Screenshot 1: Active interface and running capture
- Screenshot 2: Captured packet list
- Screenshot 3: DNS or other protocol filter results
- Screenshot 4: TCP or TLS packet details
- Screenshot 5: Saved `.pcap` file
