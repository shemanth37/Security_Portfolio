# Security_Portfolio
Welcome to my central repository! I am a Master's Student in Cybersecurity at **Sapienza University of Rome**. My work bridges the gap between hands-on offensive security, emerging Artificial Intelligence vulnerabilities, and reverse engineering.

This repository serves as a living portfolio of my academic research, penetration testing lab reports, and ongoing security studies.

## 👨‍💻 About Me
* **Focus Areas:** Penetration Testing, AI/LLM Privacy Security, and System Exploitation.
* **Currently Learning:** Deep-diving into **Malware Analysis** and reverse engineering methodologies.
* **Goal:** To secure modern infrastructure and address the unique privacy risks introduced by machine learning models.

---

## 📂 Featured Projects

### 1. [Ethical Hacking & Penetration Testing](./Ethical-Hacking)
This section contains comprehensive, sanitized penetration testing reports detailing initial footholds, lateral movement, privilege escalation, and remediation strategies across various Linux environments. 

* **Target VM 1 (Web Exploitation & Credential Harvesting):** Exploited a custom web application via SQL Injection to bypass authentication. Leveraged an unrestricted file upload vulnerability to gain an initial reverse shell. Achieved root access by hunting down hardcoded PostgreSQL credentials in application source files and cracking unsalted MD5 hashes offline.
* **Target VM 2 (Advanced System Exploitation & Container Breakout):** Conducted a multi-stage attack sequence initiating with SSH brute-forcing (Hydra). Abused a misconfigured Redis server to inject SSH keys for lateral movement. Successfully executed Path Hijacking and exploited a heavily misconfigured, privileged Docker container (`--privileged`) to escape the container environment and compromise the underlying host. Finally, exploited a custom SUID-root binary to achieve total system takeover.

### 2. [AI & LLM Security Research](./AI-Security-Research)
Academic research exploring the privacy flaws and data leakage risks inherent in modern Large Language Models.

* **Paper:** *Property Inference Attacks on LLM with Black-Box Testing on Limited User Samples*
* **Overview:** This study demonstrates how attackers can indirectly extract sensitive group-level attributes from fine-tuned LLMs relying solely on black-box API access. 
* **Key Findings:** Successfully proved that high-confidence data extraction is possible using as few as 2 to 3 carefully crafted query samples per user. The research evaluates the viability and scaling of these attacks across various model sizes (small to large) and tests both text-based and multimodal (image-text) models like LLaVA and DeepSeek Vision.

### 3. [Malware Analysis (WIP) ](./Malware-Analysis)
*(Currently building this section)* Documenting my learning journey into malware analysis. This folder will soon contain documented breakdowns of malicious software, including static and dynamic analysis, behavior mapping, and Indicators of Compromise (IOC) extraction.

---

## 🛠️ Skills & Tools
* **Offensive Security:** Nmap, Hydra, Dirb, SQLMap, Netcat, John the Ripper
* **Exploitation Tactics:** Privilege Escalation (SUID, Path Hijacking), Docker Escapes, Database Exploitation, Insecure File Permissions
* **AI/Research:** Prompt Engineering, Black-Box Testing, Statistical Data Analysis
* **Languages & Environments:** Linux/Ubuntu, Bash, Python, PostgreSQL, C


## 📫 Let's Connect!
* **LinkedIn:** https://www.linkedin.com/in/sai-hemanth-898a41161/
* **Email:** shemanth3720@gmail.com
