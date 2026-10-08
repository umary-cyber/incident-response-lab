# Incident Response Lab 🛡️

A hands-on Linux Incident Response Lab demonstrating the **NIST Incident Response Lifecycle** in a controlled Kali Linux environment.

## 🎯 Project Objective

The purpose of this lab is to simulate a small security incident and practice the core Incident Response phases:

**Preparation → Detection → Containment → Eradication → Recovery → Lessons Learned**

## 🧪 Lab Environment

- **OS:** Kali Linux
- **Shell:** Bash
- **Tools:** Linux process and network utilities
- **Git:** Version control
- **Environment:** Controlled local lab

## 🔍 Incident Simulation

A harmless Bash script was used to simulate a suspicious process.

The simulated incident was:

1. System baseline information was collected.
2. Running users and processes were investigated.
3. Network listening ports were reviewed.
4. A simulated suspicious process was detected.
5. The process was contained and terminated.
6. The suspicious artifact was removed.
7. System health was verified.
8. Lessons learned were documented.

## 📋 NIST Incident Response Lifecycle

| Phase | Action |
|---|---|
| Preparation | Collected system, user, process and network baseline |
| Detection | Identified the simulated suspicious process |
| Containment | Terminated the suspicious process |
| Eradication | Removed the suspicious script |
| Recovery | Verified system health and load |
| Lessons Learned | Documented the incident and response |

## 📁 Evidence

The `evidence/` directory contains investigation artifacts:

- `system-info.txt` — System information
- `users.txt` — Logged-in user information
- `processes.txt` — Process baseline
- `network.txt` — Listening network ports
- `suspicious-process.txt` — Detection evidence
- `incident-summary.txt` — Incident response summary

## 🛡️ Safety

This project uses a **harmless simulated incident** for educational purposes.

No real malware, credential theft, destructive activity, or unauthorized systems were used.

## 🚀 Skills Demonstrated

- Linux command-line investigation
- Process analysis
- Network investigation
- Incident detection
- Containment and eradication
- Evidence collection
- Incident documentation
- Git/GitHub
- NIST Incident Response methodology

## 📌 Learning Outcome

This lab provided practical experience with the Incident Response lifecycle and demonstrated how a SOC analyst can investigate, contain, eradicate, and document a simulated security incident.
