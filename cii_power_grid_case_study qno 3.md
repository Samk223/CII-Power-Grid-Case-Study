# Ransomware Attack on a Hospital

---

## 1️⃣ What are the cybersecurity principles violated here (CIA Triad)?

In this scenario, all three core cybersecurity principles of the **CIA Triad** — Confidentiality, Integrity, and Availability — are violated. Confidentiality is compromised because sensitive patient records may be accessed by attackers. Integrity is threatened as patient data could be tampered with while systems are under attacker control. Availability is severely impacted because critical medical systems and patient files are locked by ransomware, preventing surgeries and disrupting patient care.

---

## 2️⃣ How could PII and CII be involved in this situation?

Hospitals store large amounts of **Personally Identifiable Information (PII)** such as names, medical histories, test results, and insurance details. A ransomware attack can expose this data to theft or misuse if attackers leak it. Additionally, hospitals are increasingly part of a country’s **Critical Information Infrastructure (CII)**, as healthcare disruption can impact public health and safety. Compromised hospital systems can therefore pose a direct threat to life-critical services. As explained in the CipherSchools video, strong cryptographic techniques — symmetric encryption for storing patient records and asymmetric encryption for secure communication and authentication — are necessary to protect both PII and CII.

---

## 3️⃣ Propose a cybersecurity framework the hospital should adopt going forward.

The hospital should adopt a robust cybersecurity framework combining technical, human, and policy measures. Technically, patient records must be encrypted using strong symmetric encryption algorithms like AES to protect data at rest, while asymmetric encryption should be used for secure data sharing and access control. Regular backups must be maintained offline to restore systems quickly without paying ransom. Access to sensitive systems should require multi-factor authentication and strict privilege management. On the human side, staff must be trained to recognize phishing emails, which are common ransomware delivery methods. Regular security audits, vulnerability assessments, and incident response drills must be conducted. From a policy perspective, the hospital should align with standards like ISO/IEC 27001 or NIST Cybersecurity Framework and collaborate with CERT-In for threat intelligence and reporting. By integrating modern cryptographic practices, vigilant staff training, and robust governance, the hospital can greatly reduce its vulnerability to ransomware attacks in the future.

