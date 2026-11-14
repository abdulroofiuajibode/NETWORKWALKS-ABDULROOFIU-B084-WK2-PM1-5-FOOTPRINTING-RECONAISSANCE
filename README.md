# NETWORKWALKS-ABDULROOFIU-B084-WK2-PM1-5-CYBERSECURITY-LAB-SETUP

# Week 2: Penetration Testing – Footprinting & Network Scanning

## Project Overview

This project documents my practical experience during Week 2 of the Cybersecurity and Ethical Hacking Internship at **Networkwalks**.

The project focuses on two important stages of penetration testing: **Footprinting & Reconnaissance** and **Network Scanning & Discovery**.

The exercises involved gathering publicly available information about the `networkwalks.com` domain using Kali Linux tools and discovering active devices on my own local network using Zenmap.

## Project Objectives

- Understand the fundamentals of footprinting and reconnaissance.
- Gather domain and website information using Kali Linux tools.
- Identify website technologies and DNS information.
- Examine HTTP response headers.
- Identify the presence of a Web Application Firewall (WAF).
- Discover active hosts on a local network.
- Identify IP and MAC addresses.
- Generate a network topology using Zenmap.
- Understand potential security risks associated with information exposure.

## Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Reconnaissance environment |
| WHOIS | Domain registration information |
| WhatWeb | Website technology fingerprinting |
| Nslookup | Domain-to-IP resolution |
| Curl | HTTP response header inspection |
| Wafw00f | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |
| GHDB | Google Hacking Database research |
| Maltego | Information gathering and relationship mapping |
| TheHarvester | OSINT information gathering |
| Zenmap | Network discovery and scanning |
| Windows CMD | Local IP and MAC address identification |

## Project Activities

### 1. Footprinting & Reconnaissance

I performed reconnaissance on the `networkwalks.com` domain using different Kali Linux tools.

Activities included:

- Retrieving domain registration information using WHOIS.
- Identifying website technologies using WhatWeb.
- Resolving the domain name to its IP address using Nslookup.
- Inspecting HTTP response headers using Curl.
- Identifying the reported WAF using Wafw00f.
- Enumerating DNS records using DNSRecon.

### 2. Network Scanning & Discovery

I used Zenmap to perform network discovery on my own local network.

Activities included:

- Identifying my local IP address and subnet using Windows CMD.
- Performing a Ping Scan with Zenmap.
- Discovering active hosts on the network.
- Identifying available IP and MAC address information.
- Generating and saving a network topology.

## Key Findings

The practical exercises produced the following observations:

| Finding | Observation |
|---|---|
| Website Technology | WordPress and WP Download Manager identified |
| Domain IP Address | 192.232.216.135 |
| HTTP Information | HTTP response headers and `/wp-json/` endpoint observed |
| WAF Detection | ModSecurity (SpiderLabs) identified |
| DNS Information | DNS, mail and service-related records identified |
| Network Discovery | Active hosts discovered on the local network |

**Note:** These findings represent reconnaissance and network discovery observations. They do not independently confirm the existence of exploitable vulnerabilities.

## Security Recommendations

Based on the observations, the following improvements were recommended:

1. Review publicly exposed website technology information.
2. Keep CMS platforms, plugins and other software updated.
3. Review HTTP response headers and publicly accessible endpoints.
4. Regularly review DNS records.
5. Maintain and monitor the Web Application Firewall.
6. Perform regular internal network discovery.
7. Investigate unexpected devices.
8. Maintain updated network documentation.
9. Conduct security testing only with proper authorization.

## Skills Gained

Through this project, I developed practical knowledge and understanding of:

- Open Source Intelligence (OSINT).
- Footprinting and reconnaissance.
- Website technology fingerprinting.
- DNS enumeration.
- HTTP header analysis.
- Web Application Firewall identification.
- Network scanning and host discovery.
- IP and MAC address identification.
- Network topology mapping.
- Technical documentation and security reporting.

## Evidence & Documentation

The project report contains screenshots and practical evidence of the activities performed, including tool outputs and network discovery results.

**Project Report:** [W2-PM-FINAL – Penetration Testing Report](./W2-PM-FINAL_Revised_Recommendations_Conclusion.docx)

## Disclaimer

All activities documented in this project were conducted for educational and research purposes on the assigned training target with written permission and on my own local network.

No exploitation or vulnerability validation was performed during these exercises.

Unauthorized access, scanning or testing of systems without appropriate permission is not encouraged.

## Acknowledgement

I appreciate **Networkwalks** for providing the opportunity to develop practical cybersecurity and ethical hacking skills through this internship program.

---

**Author:** Ajibode Abdulroofiu  
**Program:** Cybersecurity & Ethical Hacking Internship  
**Batch:** B084 – Networkwalks  
**Project:** Week 02 – Footprinting & Network Scanning
