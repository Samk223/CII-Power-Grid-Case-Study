# PII Leak at a Fintech Startup

---

##  PII Leak at a Fintech Startup

### 1️⃣ What kind of data was compromised (identify PII)?

In this incident, highly sensitive **Personally Identifiable Information (PII)** was exposed. The compromised data includes customers’ names, phone numbers, Aadhaar numbers, and bank account details — all of which can directly identify individuals and put them at risk of identity theft and financial fraud.

---

### 2️⃣ How could this incident have been prevented?

This breach could have been prevented by implementing strong cloud security best practices. The main cause — a misconfigured AWS bucket — highlights the need for proper access controls and encryption of stored data. The company should have enforced strict permissions to ensure only authorized users could access the bucket. Encryption at rest using strong symmetric encryption would have added an extra layer of security even if access controls failed. Regular audits of cloud configurations and automated tools to detect misconfigurations could have flagged the exposure early.

---

### 3️⃣ What are the immediate and long-term measures the company must take?

Immediately, the company must secure the misconfigured bucket, notify affected users, and report the breach to regulatory authorities. They should reset any compromised credentials and monitor for misuse of leaked information. In the long term, the startup must establish strong data protection policies, enforce encryption of sensitive data, and implement strict access management. Staff should receive regular training on secure cloud practices, and continuous security monitoring and third-party audits should be routine. By applying lessons from the CipherSchools video — using robust cryptographic techniques for data storage and secure access controls — the startup can rebuild customer trust and prevent similar incidents in the future.

