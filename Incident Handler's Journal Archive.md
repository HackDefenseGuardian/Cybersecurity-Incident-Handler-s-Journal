## Incident Handler's Journal Archive

### **Entry #1**
**Date:** July 09, 2024

**Description:** Reporting a cybersecurity incident

**Tool(s) used:** None

**The 5 W's:**
- **Who:** An organized group of unethical hackers
- **What:** A ransomware attack encrypts the data.
- **When:** Tuesday morning, at approximately 9:00 a.m.
- **Why:** The recent cybersecurity incident at the company was caused by unethical hackers who gained unauthorized access through a successful phishing attack. The attackers then deployed ransomware, encrypting critical files and demanding a large ransom payment in exchange for the decryption key.

**Additional notes:**
1. What steps should the healthcare company take to improve its cybersecurity defenses and prevent a similar ransomware attack in the future?
2. If the company decides not to pay the ransom, what alternative methods could they use to recover the encrypted data and restore normal operations?

---

### **Entry #2**
**Date:** July 11, 2024

**Description:** Evaluating a network capture file

**Tool(s) used:** Wireshark

**The 5 W's:** N/A

**Additional notes:**
Having never used Wireshark before, I was eager to start this task and dive into analyzing a packet capture file. Initially, the interface seemed quite daunting. However, it quickly became apparent why this tool is highly regarded for interpreting network traffic.

---

### **Entry #3**
**Date:** July 18, 2024

**Description:** Examining a suspicious file hash

**Tool(s) used:** VirusTotal

**The 5 W's:**
- **Who:** An unknown malicious actor
- **What:** An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b
- **Where:** An employee's computer at a financial services company
- **When:** At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file
- **Why:** An employee was able to download and execute a malicious file attachment via email.

**Additional notes:**
How can this incident be prevented in the future? Should we consider improving security awareness training so that employees are careful with what they click on?

---

### **Entry #4**
**Date:** July 22, 2024

**Description:** Security incident involving unauthorized access to customer personal identifiable information (PII) and financial information through a web application vulnerability.

**Tool(s):**
- Web application access logs
- Vulnerability scanning tools
- Penetration testing tools

**The 5 W's:**
- **Who:** The incident was caused by an unidentified attacker who exploited a vulnerability in the e-commerce web application.
- **What:** Unauthorized access to customer personal identifiable information (PII) and financial information of approximately 50,000 customer records. Financial impact estimated at $100,000 in direct costs and potential loss of revenue.
- **When:** Initial notification received on December 22, 2022, at 3:13 p.m., PT. Incident confirmed on December 28, 2022, at 7:20 p.m., PT. Incident investigation and resolution between December 28 and December 31, 2022.
- **Where:** The vulnerability was in the e-commerce web application, allowing unauthorized access via the purchase confirmation page URL.
- **Why:** A forced browsing attack due to a vulnerability in the web application allowed the attacker to modify the order number in the URL string, accessing customer transaction data.

**Additional notes:**
The security team responded promptly after the notification, beginning an on-site investigation. The attacker accessed and exfiltrated customer data by collecting information from the purchase confirmation pages. Remediation actions included disclosing the data breach to affected customers and offering free identity protection services. Future preventive measures involve routine vulnerability scans, penetration testing, implementing allowlisting for URL access control, and ensuring that only authenticated users have access to sensitive content.

---

### **Entry #5**
**Date:** July 25, 2024

**Description:** Conducting my first network packet capture

**Tool(s) used:** Tcpdump

**The 5 W's:** N/A

**Additional notes:**
As someone relatively new to the command-line interface, capturing and filtering network traffic was a bit daunting. I encountered several obstacles due to incorrect command usage. However, by meticulously following the instructions and redoing certain steps, I managed to complete the activity and successfully capture network traffic.

---

### **Entry #6**
**Date:** July 29, 2024

**Description:** Multiple failed SSH login attempts for the root account detected on the mail server, indicating a potential brute force attack.

**Tool(s) used:** Splunk Cloud Platform

**The 5 W's:**
- **Who:** Unauthorized external attackers from multiple IP addresses
- **What:** Multiple failed SSH login attempts for the root account on the mail server, indicating a potential brute force attack
- **When:** The incident occurred on July 6, 2024, at 01:39:51.
- **Where:** The incident happened on the mail server (mailsv1) at Buttercup Games.
- **Why:** The incident appears to be a brute force attack aimed at gaining unauthorized access to the root account on the mail server, potentially to compromise sensitive data or disrupt services.

**Additional notes:**
As a security analyst at Buttercup Games, I have identified several failed SSH login attempts targeting the root account on our mail server. These attempts occurred on July 6, 2024, at 01:39:51. The attack appears to be a brute force attempt using various IP addresses. Immediate actions will be taken to mitigate this threat, including tightening SSH access controls, implementing IP blacklisting, and monitoring for further suspicious activity. Further analysis and preventive measures will be conducted to secure our mail server and protect against future attacks.

---

### **Entry #7**
**Date:** July 30, 2024

**Description:** Investigation of Phishing Attempt Targeting Multiple Workstations

**Tool(s) used:** Chronicle

**The 5 W's:**
- **Who:** 
  - Ashton-davidson-pc
  - emil-palmer-pc
  - warren-morris-pc
- **What:** Multiple POST requests to /login.php from the domain signin.office365x24.com
- **When:** The phishing activity was observed on June 11, 2024.
- **Where:** The incident occurred within the internal network of the financial services company, affecting different workstations
- **Why:** The phishing attack was executed through deceptive emails, leading users to enter their credentials on fraudulent login pages.

**Additional notes:**
On June 11, 2024, a phishing attempt targeted multiple workstations within the financial services company, including Ashton-davidson-pc, emil-palmer-pc, and warren-morris-pc. Deceptive emails led users to fraudulent login pages on domains `signin.office365x24.com` and `signin.accounts-gooqle.com`, aiming to capture sensitive credentials. The IP address `40.100.174.34` was identified in the attack. Immediate actions included securing affected workstations, enhancing email security, and educating employees. Further investigation and proactive measures are recommended to address and prevent future phishing threats.

**Next Steps:**
- Review and secure all affected workstations to confirm no credentials were compromised and to remove any lingering threats.
- Strengthen email security measures to better detect and prevent phishing attacks.
- Provide targeted training to employees on recognizing phishing attempts and secure handling of sensitive information.
- Enhance monitoring systems to identify and respond to similar phishing threats proactively.

---

**Reflections/Notes:** This is an exercise Incident handler’s journal.

You can download the complete Incident Handler's Journal [here](https://docs.google.com/document/d/1G8Q_YjoSxgUi4Ybitgg7q1QA5B-QPnfXCkm_YqQk9FQ/edit?usp=sharing).