# 🛡️ Wazuh Detection Analysis — Multi-Endpoint Evaluation

## 📌 Purpose
Evaluate Wazuh’s detection accuracy, speed, and rule diversity for simulated cyberattacks executed on Windows and Linux endpoints.

---

## 🧪 Attack Techniques (Atomic Red Team)
- T1059 — Command Execution  
- T1078 — Valid Accounts  
- T1082 — System Discovery  
- T1046 — Network Scanning  
- T1053 — Scheduled Tasks  

---

## 🏗️ Architecture
Include a diagram in `/diagrams`.

- Wazuh Manager (Ubuntu 22.04)
- Wazuh Indexer
- Wazuh Dashboard
- Windows 11 endpoint (Agent ID X)
- Linux endpoint (Agent ID Y)
- Atomic Red Team executor

---

## 📑 Research Questions
1. Does Wazuh detect attacks consistently across OS types?  
2. What is the average detection time?  
3. Are certain attack techniques harder to detect?  
4. Does Wazuh classify severity appropriately?  
5. Are rules equally effective across platforms?

---

## 📊 Metrics Used
| Metric | Description |
|--------|-------------|
| Detection Accuracy | TP / (TP+FN) |
| Detection Speed | Time delta from execution to alert |
| Rule Coverage | Number of unique rules triggered |
| Severity Distribution | High/Medium/Low |
| Cross-Platform Consistency | Windows vs Linux results |

---

## 📈 Results
Add charts & tables from your thesis or notebook.

---

## 🧠 Key Findings
Bullet list of high-level conclusions.

---

## 📁 Repo Layout
