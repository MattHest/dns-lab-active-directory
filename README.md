# DNS Lab – Active Directory

Hands-on DNS lab in an Active Directory environment demonstrating A record creation, CNAME configuration, and DNS cache troubleshooting.

---

## Overview
In this lab, I configured and tested DNS functionality within an Active Directory environment using a Windows Server Domain Controller and a Windows client machine.

---

## Screenshots & Walkthrough

### Azure Virtual Machines
![Azure VMs](images/azure-vms-running.png)

Both the Domain Controller (DC-1) and Client machine (Client-1) are running in Azure, providing the environment for DNS testing.

---

### DNS Manager – Record Configuration
![DNS Manager](images/dns-manager-records.png)

Created and modified DNS records including an A record for "mainframe" and a CNAME record pointing "search" to an external domain.

---

### DNS Cache (Before Flush)
![DNS Cache Before](images/dns-cache-display-before-flush.png)

The client machine still resolves the old IP address due to cached DNS records, demonstrating how DNS caching can cause outdated results.

---

### DNS Cache (After Flush)
![DNS Cache After](images/dns-cache-after-flush.png)

After flushing the DNS cache, the client retrieves the updated DNS record, confirming successful propagation and resolution.
---

## What This Lab Demonstrates
- Creating and modifying DNS A records  
- Understanding DNS name resolution  
- Identifying DNS caching issues  
- Flushing DNS cache to resolve outdated records  
- Configuring and testing CNAME records  

---

## Key Skills Demonstrated
- DNS Troubleshooting  
- Active Directory DNS  
- Command Line Tools (ipconfig, nslookup)  

---

## Author

Matthew Hestand  
Aspiring IT Support Specialist  
CompTIA A+ (Core 1 Passed)
