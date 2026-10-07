CodeAlpha — Basic Network Sniffer

Project Overview

This project was completed as Task 1 of the CodeAlpha Cybersecurity Internship. It demonstrates a basic Python-based network sniffer that captures network traffic and displays useful packet information.

The implementation focuses on observing:

Source IP address

Destination IP address

Network protocol

Packet length

Available payload information

The project was performed in a Kali Linux virtual-machine lab environment.

Objective

The objective of this task was to build a simple network packet sniffer and use it to understand how network traffic is transmitted and how packet information can be inspected.

Tools & Technologies

Kali Linux

Python 3

Scapy

Linux terminal

Browser Developer Tools for supplemental web-request observation

Evidence

1. Python Environment

Python 3 was verified in the Kali Linux terminal.



2. Ping Test

ICMP traffic was generated with a ping test. The captured output shows successful ICMP replies, although the VM also experienced packet loss during one test.



3. Captured Packets

The sniffer output shows source and destination IP addresses, protocol identification, packet length, and payload information.



4. DNS Test

nslookup example.com was used to generate DNS-related traffic and demonstrate name-resolution activity.



5. Supplemental Web Request Evidence

Browser Developer Tools were used to observe a login POST request and its request/response details. Credential values have been redacted in the published evidence image.



Key Observations

The lab captured traffic involving the Kali VM address 10.0.0.5.

TCP packets were observed between the VM and external destinations.

ICMP traffic was generated through ping.

DNS resolution for example.com was observed using nslookup.

Packet output included source IP, destination IP, protocol, packet length, and available payload data.

Security & Privacy Note

Packet captures can contain sensitive information. This project was conducted in a controlled lab environment. Credentials shown in the original browser screenshot were not reproduced in the published evidence.

Learning Outcomes

Through this project, I gained practical experience with:

Basic packet capture

Network protocols

Source and destination addressing

Packet inspection

Network traffic generation and observation

Python-based network security tooling

Conclusion

The Basic Network Sniffer project provided hands-on experience in monitoring and analyzing network traffic. It demonstrated how packet-level information can be collected and inspected to better understand communication between systems.

Internship Context

Completed as part of the CodeAlpha Cybersecurity Internship — Task 1: Basic Network Sniffer.
