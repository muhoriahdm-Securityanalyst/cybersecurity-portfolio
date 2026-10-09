Derrick Mutie Muhoria | Junior SOC Analyst & Security Automation Practitioner

Welcome to my cybersecurity portfolio. Here, I showcase practical defensive security operations, Linux administration, log analysis, cryptographic workflows, and AI-driven automation skills developed through the Google Cybersecurity Certificate and hands-on lab environments.

🛠️ **Core Technical Skills**

1. **Security Operations & Analysis**: Incident Investigation, Threat Hunting, Log Parsing, IOC Verification.

2. **Database & Querying**: MariaDB / SQL (Advanced filtering, Wildcards, Boolean logic operators).  

3. **Systems & Scripting**: Linux Command Line, Bash, File Permissions, Cryptographic Hashing.

4. **Cryptography & Tools:** OpenSSL (aes-256-cbc), Caesar Cipher Cryptanalysis (tr), SHA-256 Integrity Verification. 

5. **Gen AI & Tooling**: AI-assisted workflow automation, rapid prototyping, and web interface generation.   

**📁 Featured Projects**

**Project 1: SOC Log Investigation & Threat Hunting via Advanced SQL Queries**

Objective: Investigate potential security incidents, track unauthorized access attempts, and isolate vulnerable employee machines across departmental networks using SQL.

**Actions Performed:**
Wrote MariaDB queries to filter after-hours failed login attempts (login_time > '18:00' AND success = FALSE) to identify suspicious post-business-hour activity. 

Tracked multi-day security events using date-range filtering and logical operators (OR). 
Handled geographic anomalies by filtering out authorized regions using pattern matching (NOT country LIKE 'MEX%').  

Targeted specific enterprise assets for security patches by querying organizational databases by department and office locations (e.g., Marketing in the East building, or excluding IT staff).

**Key Skills Demonstrated:** 

SQL data extraction, incident log triage, indicator filtering.Project 2: File Integrity Monitoring & Cryptographic Hashing

Objective: Implement cryptographic hashing controls to protect organizational systems against file tampering and malicious alterations. 

**Actions Performed**:
Generated unique SHA-256 cryptographic digests (sha256sum) for system binaries and text assets.  

Maintained baseline secure hashes by outputting digests to verification files (>> file1hash).  

Performed manual integrity checks and binary file comparisons (cmp) to detect unauthorized modifications or spoofed application files.

Key Skills Demonstrated: **File integrity monitoring (FIM)**, **command-line forensics**, **asset verification**.

**Project 3: Incident Cryptanalysis & Data Recovery Operations**

**Objective:** Respond to a simulated ransomware/encryption incident by breaking classical ciphers and decrypting locked enterprise files.

**Actions Performed**:

Navigated compromised directory structures via the Linux command line to locate hidden recovery notes (README.txt). 

Solved shifted Caesar ciphers using command-line text translation utilities (tr 'd-za-c-D-ZA-C' 'a-z-A-Z') to uncover decryption instructions.

Executed OpenSSL decryption pipelines (openssl aes-256-cbc -pbkdf2 -d) using recovered keys and passphrases to successfully restore encrypted data files (Q1.encrypted to Q1.recovered).

**Key Skills Demonstrated:** Incident response workflows, Linux CLI forensics, OpenSSL cryptography.

**Project 4: AI-Driven Workflow & Compliance Automation Tool**
**Objective:** Leverage generative AI leadership principles to design and deploy an automated compliance tool for tracking project documentation and operational registers.

**Actions Performed:**

Designed and built a dynamic web application (Fiscal Attendance Register Generator) using AI-assisted programming to streamline administrative tracking for urban infrastructure projects.  

Configured automated document styling, customized font rendering rules (html2canvas + jsPDF), and bulk PDF generation packages. 

Integrated multi-template configuration settings to match strict organizational and regulatory formatting standards. 

**Key Skills Demonstrated:** Gen AI integration, rapid web prototyping, operational efficiency automation.

**📜 Certifications & Credentials**

Google Cybersecurity Professional Certificate (Google Skills) 
Gen AI Leader (Google)
