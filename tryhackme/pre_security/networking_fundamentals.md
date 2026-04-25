# Networking Fundamentals – TryHackMe

## Overview

This room introduced essential networking concepts that form the foundation of cybersecurity and penetration testing. The focus was on understanding how devices communicate, how data travels across networks, and how protocols operate in real-world environments.

A solid grasp of networking is critical in offensive security, as it directly supports reconnaissance, enumeration, traffic analysis, and vulnerability identification.

---

## Key Concepts Learned

### IP Addressing and Subnetting

IP addresses uniquely identify devices within a network. Understanding subnetting is essential for dividing networks efficiently and identifying address ranges during reconnaissance.

In practice, subnet knowledge helps determine the number of hosts available, locate potential targets, and understand network segmentation.

---

### TCP vs UDP

**TCP (Transmission Control Protocol)** is connection-oriented and ensures reliable delivery of packets through sequencing and acknowledgments.

**UDP (User Datagram Protocol)** is connectionless and prioritizes speed over reliability.

#### Practical Security Relevance

* TCP is commonly observed in services such as HTTP, HTTPS, SSH, and FTP.
* UDP is frequently used in DNS, VoIP, and streaming services.
* Understanding both protocols helps interpret scan results and packet captures.

---

### OSI Model

The OSI model organizes network communication into layers, making troubleshooting and analysis more structured.

#### Security Perspective

Each layer can present different attack surfaces:

* **Application Layer:** web vulnerabilities, authentication flaws
* **Transport Layer:** port scanning, session hijacking
* **Network Layer:** routing attacks, IP spoofing
* **Data Link Layer:** MAC spoofing, ARP poisoning

Understanding these layers improves incident analysis and penetration testing methodology.

---

## Tools Used

### Wireshark

Wireshark was used for basic packet analysis and traffic inspection.

#### Observations

* Captured TCP handshakes in client-server communication
* Identified DNS queries and server responses
* Compared structural differences between TCP and UDP packets

This practical analysis reinforced theoretical concepts by visualizing real network traffic.

---

## Practical Application in Pentesting

Networking knowledge is essential in offensive security tasks such as:

* Host discovery
* Port enumeration
* Service identification
* Traffic analysis
* Attack surface mapping

Without understanding how systems communicate, it becomes difficult to assess risks effectively.

---

## Key Takeaways

This room strengthened my understanding of network communication and protocol behavior.

The most important lesson was that networking is not just theoretical knowledge — it is a core skill for cybersecurity professionals, especially in penetration testing and threat analysis.

---

## Personal Reflection

Studying networking fundamentals provided a stronger technical base for future learning in web exploitation, privilege escalation, and advanced offensive security practices.

This knowledge will continue to support practical lab work and real-world security assessments.

