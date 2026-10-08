# 🛡️ Incident Response Lab

> A hands-on cybersecurity lab demonstrating the **NIST Incident Response Lifecycle** through a controlled Linux security incident simulation.

---

## 🎯 Project Overview

This project simulates a security incident in a controlled **Kali Linux** environment and demonstrates how a SOC analyst can identify, investigate, contain, eradicate, and document suspicious activity.

### Incident Response Lifecycle

```text
Preparation → Detection → Containment → Eradication → Recovery → Lessons Learned
🧪 Lab Environment
Component	Details
💻 Operating System	Kali Linux
🐚 Shell	Bash
🔎 Investigation	Linux CLI Utilities
📊 Evidence	Investigation Artifacts
🔧 Version Control	Git / GitHub
🛡️ Incident Type	Simulated Suspicious Process
🚨 Incident Scenario

A harmless Bash script was intentionally created to simulate a suspicious running process.

The objective was to practice the complete Incident Response workflow without using real malware or performing destructive actions.

🔍 Investigation & Response
1️⃣ Preparation
Collected system information
Identified logged-in users
Recorded running processes
Reviewed listening network ports
2️⃣ Detection
Investigated running processes
Identified the simulated suspicious process
Preserved detection evidence
3️⃣ Containment
Identified the suspicious process PID
Terminated the suspicious process
4️⃣ Eradication
Removed the suspicious script
Verified that the artifact no longer existed
5️⃣ Recovery
Checked system health
Reviewed system load after remediation
6️⃣ Lessons Learned
Documented the incident
Preserved investigation evidence
Reviewed the importance of process monitoring and evidence collection
📁 Project Structure
incident-response-lab/
│
├── evidence/
│   ├── system-info.txt
│   ├── users.txt
│   ├── processes.txt
│   ├── network.txt
│   ├── suspicious-process.txt
│   └── incident-summary.txt
│
└── README.md
📊 Evidence Collected
Evidence	Purpose
system-info.txt	System baseline information
users.txt	Logged-in user investigation
processes.txt	Running process baseline
network.txt	Listening network ports
suspicious-process.txt	Suspicious process detection evidence
incident-summary.txt	Incident response summary
🛠️ Skills Demonstrated
🔎 Linux Process Investigation
🌐 Network Investigation
🚨 Incident Detection
🛑 Threat Containment
🧹 Threat Eradication
🔄 System Recovery
📂 Evidence Collection
📝 Incident Documentation
🐧 Linux Command Line
🔧 Git & GitHub
🛡️ NIST Incident Response Methodology
🔐 Safety

This project was performed in a controlled local lab environment.

The simulated incident used a harmless Bash script.

No real malware, credential theft, destructive commands, or unauthorized systems were involved.

📚 Key Learning Outcome

This lab provided practical experience with the Incident Response lifecycle and demonstrated how a security analyst can move from initial detection to containment, eradication, recovery, and post-incident documentation.

Detect → Investigate → Contain → Eradicate → Recover → Learn

👨‍💻 Author

Muhammad Umar

Cybersecurity Student | SOC & Blue Team Enthusiast
