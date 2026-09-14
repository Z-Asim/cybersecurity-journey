# Day 22 — August 10, 2026

## Learning

### Google Cybersecurity Professional Certificate
**Course 3 — Connect and Protect: Networks and Network Security**

Continued Module 3: **Secure against network intrusions**.

Worked through a cybersecurity incident report based on network traffic analysis. Analyzed DNS, UDP, and ICMP traffic using the provided tcpdump scenario.

### Incident Analysis

- Customers were unable to access `yummyrecipesforme.com`.
- The investigation involved analyzing network traffic using `tcpdump`.
- DNS requests were sent using UDP.
- DNS communication uses port 53.
- The captured traffic showed an ICMP error indicating that UDP port 53 was unreachable.
- This suggested that the DNS server was unreachable or not responding.
- Possible causes included a DNS server problem, firewall configuration blocking port 53, or a potential Denial of Service (DoS) attack.

## Key Takeaways

- DNS is responsible for resolving domain names to IP addresses.
- UDP can be used for DNS communication.
- Port 53 is associated with DNS traffic.
- ICMP can communicate network errors such as an unreachable port.
- Network traffic analysis can help identify where a connectivity problem is occurring.
- An observed symptom should be separated from a suspected root cause during incident analysis.

## Portfolio Evidence

- [Cybersecurity Incident Report — Network Traffic Analysis](../portfolio/day-22-incident-report.pdf)

## Progress

- Continued Course 3, Module 3.
- Completed the Network Traffic Analysis incident-report activity.
- Created an incident report based on the investigation scenario.

## Reflection

This activity helped me understand how cybersecurity analysts can use network traffic to investigate an incident. I also learned the importance of distinguishing confirmed findings from suspected causes.

## Next Step

Continue with **Course 3 — Module 3: Secure against network intrusions**.
