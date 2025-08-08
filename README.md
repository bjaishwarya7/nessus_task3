nessus_task3
Basic Vulnerability Scan
📌 Objective
Use free tools to identify common vulnerabilities on your PC, understand their severity, and document the findings.
🛠 Tools Used
Nessus Essentials (or OpenVAS Community Edition) – Free vulnerability scanner
Local Machine IP (scan target)

📂 Steps Followed
Install the Vulnerability Scanner
Downloaded Nessus Essentials from the official Tenable website.
Completed installation and initial setup.
Identify Scan Target
Checked local machine IP address using:
bash
Copy
Edit
ipconfig   # Windows  
ifconfig   # Linux/Mac
Used local IP (e.g., 192.168.x.x) as the scan target.
Configure the Scan
Created a New Scan in Nessus.
Selected Basic Network Scan template.
Entered local machine IP in the target field.
Run the Scan
Started the scan and waited ~30–60 mins for completion.
Review Results
Opened the generated report.
Checked each vulnerability’s Severity Level (Critical, High, Medium, Low).
Research & Document Fixes
Researched mitigation steps for the most critical vulnerabilities found.
Capture Evidence
Took screenshots of scan results and vulnerability details.

📊 Outcomes
Understood how vulnerability scanners detect weaknesses.
Learned about CVSS (Common Vulnerability Scoring System).
Identified and documented critical security risks on the PC.

📁 Repository Structure
bash
Copy
Edit

📂 Task-3-Vulnerability-Scan
 ├── README.md          # This file
 ├── screenshots/       # Scan result images
 └── report.pdf         # Nessus/OpenVAS generated report
 
💡 Key Concepts Learned
Vulnerability Scanning vs. Penetration Testing
CVSS Scoring & Risk Prioritization
Common PC Vulnerabilities & Remediation
