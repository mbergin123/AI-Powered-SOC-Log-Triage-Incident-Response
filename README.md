# 🔐 AI-Powered SOC Log Triage & Incident Response (Ubuntu + Python)

## 📌 Overview

This project demonstrates the development of an AI-assisted Security Operations Center (SOC) triage tool built on Ubuntu. The system analyzes Linux authentication logs to detect suspicious activity such as brute-force login attempts, extracts indicators of compromise (IOCs), classifies incident severity, and generates structured incident reports.

---

## 🎯 Objectives

* Analyze Linux authentication logs (`auth.log`)
* Detect brute-force login attempts
* Extract indicators of compromise (IP addresses, user activity)
* Classify incident severity
* Generate automated reports
* Enhance analysis using AI

---

## 🛠️ Technologies Used

* Ubuntu 24.04 (VMware)
* Python 3
* OpenAI API
* python-dotenv
* Regex
* Linux CLI

---

## 🧱 Project Structure

**Screenshot: `tree.png`**

```markdown
![Project Structure](tree.png)
```

```text
ai-soc-triage-assistant/
├── logs/
├── reports/
├── soc_triage.py
├── soc_triage_ai.py
├── .env
└── venv/
```

---

## ⚙️ Environment Setup

### 🖥️ Virtual Machine Setup

**Screenshot: `vm.png`**

```markdown
![VM Setup](vm.png)
```

* Configured Ubuntu in VMware
* Fixed NAT/network connectivity issue
* Verified internet access

---

### 📦 Dependency Installation

**Screenshot: `pythonpackage.png`**

```markdown
![Python Packages Installed](pythonpackage.png)
```

Installed:

* Python3
* pip
* virtual environment
* OpenAI SDK
* python-dotenv

---

## 📄 Log Data Preparation

**Screenshot: `samplelog.png`**

```markdown
![Sample Log File](samplelog.png)
```

Created simulated authentication logs containing:

* Failed SSH login attempts
* Successful login
* Privileged command (sudo)

---

## 🧠 Rule-Based Detection Script

**Screenshot: `correctscript.png`**

```markdown
![Core Script](correctscript.png)
```

This script:

* Parses authentication logs
* Counts failed/successful logins
* Extracts IP addresses
* Detects suspicious patterns
* Classifies severity

---

## ▶️ Script Execution (Rule-Based)

**Screenshot: `scriptran.png`**

```markdown
![Script Execution](scriptran.png)
```

Output:

* Detected brute-force behavior
* Classified severity as **High**
* Generated structured report

---

## 🤖 AI Integration Setup

**Screenshot: `aipython.png`**

```markdown
![AI Dependencies Installed](aipython.png)
```

* Stored API key securely in `.env`
* Installed `openai` and `python-dotenv`
* Prepared environment for AI analysis

---

## 🚀 AI-Enhanced Execution

**Screenshot: `airun.png`**

```markdown
![AI Script Run](airun.png)
```

AI script:

* Processes extracted indicators
* Sends structured prompt to OpenAI
* Receives contextual analysis

---

## 📊 Final AI-Generated Report

**Screenshot: `aireport.png`**

```markdown
![AI Report Output](aireport.png)
```

Report includes:

* Severity classification
* Indicators of compromise (IPs)
* Attack explanation
* Recommended response actions

---

## 🧠 Key Takeaways

* Built a SOC-style triage workflow from scratch
* Combined rule-based detection with AI analysis
* Simulated real-world incident investigation
* Strengthened Linux + Python + cybersecurity skills

---

## 💼 Why This Project Matters

This project reflects real SOC responsibilities:

* Log analysis
* Threat detection
* Incident classification
* Response recommendations

---

## 🚀 Future Improvements

* Real-time log monitoring
* Automated IP blocking
* SIEM integration
* Alert notifications
* Web dashboard

---

## 👩‍💻 Author

Marilyn Bergin
🔗 GitHub: https://github.com/mbergin123
🔗 LinkedIn: https://www.linkedin.com/in/marilyn-bergin/
