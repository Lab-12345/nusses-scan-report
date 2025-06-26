# 🔍 Vulnerability Scan Report - Nessus Essentials

## 🛠 Tool Used
- **Nessus Essentials**  
  A free vulnerability scanner by Tenable used for basic vulnerability assessments.

## 🗓 Scan Date
- **June 26, 2025**

## 🎯 Target
- Localhost: **192.168.230.128**

## ⚠️ Summary of Vulnerabilities
| Severity   | Count |
|------------|-------|
| Critical   | 11    |
| High       | 7     |
| Medium     | 27    |
| Low        | 9     |
| Info       | 134   |

## 🚨 Critical Vulnerabilities Identified
1. **UnrealIRCd Backdoor Detection**
   - CVSS: 10.0
   - 🛠 Fix: Remove vulnerable backdoor services.

2. **Canonical Ubuntu Linux SElinux (0.8.4x)**
   - CVSS: 10.0
   - 🛠 Fix: Update to a secure version.

3. **VNC Server 'password' Password**
   - CVSS: 10.0
   - 🛠 Fix: Change the default password.

4. **SSL Version 2 and 3 Protocol Detection**
   - CVSS: 9.8
   - 🛠 Fix: Disable SSL 2.0 and SSL 3.0; use TLS 1.2 or higher.

5. **Bind Shell Backdoor Detection**
   - CVSS: 9.8
   - 🛠 Fix: Investigate for compromise and block access.

## ✅ Recommendations
- Patch outdated or vulnerable software.
- Disable unused network services and ports.
- Enforce strong password policies.
- Migrate from deprecated encryption protocols.
- Monitor for backdoors and unusual activity.

## 📸 Screenshots
Screenshots from the Nessus Essentials dashboard showing:
![Uploading Screenshot 2025-06-26 121844.png…]()
![Uploading Screenshot 2025-06-26 121844.png…]()
![Uploading Screenshot 2025-06-26 121844.png…]()
![Uploading Screenshot 2025-06-26 121844.png…]()

- Vulnerability breakdown
- Specific critical issues
- CVSS scores and remediation tips

## 📎 Report
Download the full PDF scan report here:
[📄 Vulnerability_Scan_Report_Nessus.pdf](./docs/vulnerability_scan_report.pdf)

---

## 💡 Notes
- This scan was performed on a local machine for educational purposes only.
- Vulnerabilities should be remediated immediately in a production environment.

