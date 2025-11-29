---
sidebar_position: 3
---

# Alpha Chain RPC Service Privacy Policy

## 1. Introduction and Scope

This Privacy Policy describes how AlphaToken (“we,” “us,” or “our”) handles information in connection with the provision of the Remote Procedure Call (RPC) endpoint for the Alpha Chain network (the “Service”).

**Effective Date:** [November 1, 2025]
**Contact:** For questions about this policy, please contact us at dev@alphatoken.com .

## 2. Information We Collect

We are committed to collecting the minimum amount of data necessary to provide a stable, secure, and functional RPC service.

### **2.1. RPC Request Data**

When you interact with the Service, we process the following types of information:

- **IP Address:** Your IP address is processed and temporarily logged for the purpose of maintaining service security, detecting and preventing malicious activity (e.g., DDoS attacks, excessive requests), and load balancing.
  - ***Crucially, IP addresses are not stored permanently.*** Security logs containing IP addresses are retained only for a short, limited duration (e.g., 7 days) and are automatically purged/anonymized thereafter.
- **Request Metadata:** This includes the timestamp, the specific RPC method called (e.g., `eth_getBalance`, `eth_call`), request parameters (e.g., transaction hash, block number, wallet address), and the HTTP headers (e.g., user-agent).
- **Transaction Data:** If you submit a transaction, the Service necessarily processes the raw, signed or unsigned transaction data to broadcast it onto the Alpha Chain network. This data is immediately broadcast and not permanently stored by us.

### **2.2. Information We DO NOT Collect**

**We explicitly state that we do not collect or store any directly identifiable Personal Identifiable Information (PII)** such as your name, email address, physical address, or phone number.

**We do not have access to, nor do we store, your private keys or wallet seed phrases.**

## 3. How We Use the Information

The information we process is used strictly for the following operational and security purposes:

- **Service Provision:** To process your requests, fetch data from the blockchain, and broadcast transactions to the Alpha Chain network.
- **Security and Abuse Prevention:** To monitor traffic, identify and mitigate threats, excessive requests, spam, and other forms of service abuse.
- **Service Optimization:** To analyze request volumes and response times to ensure service stability, reliability, and efficient load balancing.
- **Compliance:** To comply with any applicable laws, regulations, and legal processes.

***We will not use your RPC request data or access information for commercial analysis, marketing, or any purpose beyond the operational and security needs of the Service.***

## 4. Data Storage and Retention

- **Non-Permanent Storage of IP Addresses:** As stated, security logs containing IP addresses are retained for a brief, limited period (e.g., up to 7 days) to ensure network stability and security, and are then permanently deleted or fully anonymized.
- **Data Security:** We employ standard security measures (such as TLS/SSL encryption, access control, and firewalls) to protect the data we process against unauthorized access, disclosure, alteration, or destruction. However, no internet transmission is 100% secure.

## 5. Disclosure to Third Parties

We do not sell, trade, or otherwise transfer your data to outside parties, except in the following limited circumstances:

- **Service Providers:** We may use third-party cloud service providers (e.g., AWS, Google Cloud, Cloudflare) to host and operate the RPC endpoint. These providers are bound by confidentiality obligations and are only permitted to use the data to perform services on our behalf.
- **Legal Obligation:** If required to do so by law or in response to a valid court order or subpoena.

## 6. Your Rights

Due to the limited and non-identifiable nature of the data we collect (as IP logs are temporary and deleted), your rights to access, correct, or delete data are limited to what is technically feasible and required by law.

- **Contact Us:** If you have concerns about the data we process, please contact us at dev@alphatoken.com .

## 7. Changes to this Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new policy on this page and updating the “Effective Date” above. You are advised to review this Privacy Policy periodically for any changes.
