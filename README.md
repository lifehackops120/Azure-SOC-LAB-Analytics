# Azure-SOC-LAB-Analytics
# NIST 800-61 Incident Management Lifecycle and the Importance of Applying NIST CSF and NIST 800-53

## NIST 800-61 Incident Management Lifecycle

This document outlines the steps taken during an incident management lifecycle, demonstrating a comprehensive approach to handling security incidents using Microsoft Log Analytics, Microsoft SIEM, and other tools and frameworks.

### Preparation
- Deployed Microsoft Log Analytics and Microsoft SIEM to monitor and analyze data.
- Set up logging features and KQL queries to prepare for incident identification.

### Identification
- Detected malicious traffic using logging features and KQL queries.
- Analyzed logged events and set up a GeoIP map to observe regions where malicious traffic originated.

### Containment
- Implemented NIST 800-53 controls along with Microsoft Defender.
- Created new rules within the network security groups.
- Added network security groups to the subnets and turned on Microsoft Defender firewall within the virtual environment.

### Eradication and Recovery
- Blocked traffic originating from state actors and public networks as per business operations.
- Restored systems with hardened network and firewall settings for business continuity.

### Post-Incident Activity
- Identified performance gaps and liabilities of deploying infrastructure without a defense-in-depth security mindset.

## The Importance of Applying NIST CSF and NIST 800-53

Applying the NIST Cybersecurity Framework (CSF) and NIST 800-53 is crucial for keeping our digital world safe. NIST CSF helps us understand how to protect our computers and data from threats, while NIST 800-53 provides specific steps and rules to follow. Together, they create a strong defense against cyber threats.

### Using NIST CSF and NIST 800-53 in Our Azure Lab

In our Azure lab, we started with an environment that was not secure, making it easy for hackers to break in and cause trouble. To fix this, we used tools like Azure Log Analytics and Microsoft Sentinel.

- **Azure Log Analytics**: Acts like a detective for our computers, helping us look at logs (records of what happens on our computers) and find anything strange. We used KQL queries (a special language for searching logs) to find security issues, such as unusual login attempts or changes to important files.

- **Microsoft Sentinel**: Functions as a superhero for our security, watching over our computers all the time and alerting us if something bad happens. It helps us respond quickly to stop attacks. By using Sentinel, we set up rules to automatically catch and fix problems.

### Before and After Applying NIST CSF and NIST 800-53

Before we applied NIST CSF and NIST 800-53, our lab was like a house with open doors and windows. After applying these frameworks, we locked all the doors and windows and set up an alarm system, making it much harder for hackers to get in and keeping our data safe.

### Summary

Using NIST CSF and NIST 800-53 in Azure, along with tools like Log Analytics and Sentinel, helps protect our digital world from cyber threats. This approach ensures that our environment is secure, resilient, and ready to defend against any potential attacks.

---

This README file explains the NIST 800-61 incident management lifecycle and emphasizes the importance of applying NIST CSF and NIST 800-53 in an easily understandable way.  ) ![map-1](https://github.com/user-attachments/assets/499b3649-82f4-4bcf-a6a3-79b1bb02b4be) ![map-2](https://github.com/user-attachments/assets/ccd46ea4-e4de-4832-af1b-d6438f4508f9) ![map-3](https://github.com/user-attachments/assets/7be8ea13-c381-48f0-ae6c-d8df6a1b8b98) ![map-4](https://github.com/user-attachments/assets/c6db2bae-1779-46ab-b9d0-be3e5f9b7f19) ![results](https://github.com/user-attachments/assets/aa7b770f-de6b-4a4b-b303-382bbfc6ab78) ![queries](https://github.com/user-attachments/assets/f4c51f79-9a30-4edd-a6a6-bddd6e2aeb20)






