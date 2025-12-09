# Vulnerable-Machine-Assessment
This repository covers a hands-on penetration test of a vulnerable .ova VM. Using Nmap, port enumeration, web testing, and OWASP-aligned analysis, all findings, screenshots, and PoCs are in the Report/ directory, demonstrating methodical real-world security assessment skills.

# Vulnerable-Machine-Assessment

![Status](https://img.shields.io/badge/Status-Completed-success) ![Language](https://img.shields.io/badge/Language-Documentation-blue) ![License](https://img.shields.io/badge/License-Educational-lightgrey)

This repository contains a hands-on penetration testing assessment of a purposely vulnerable virtual machine (`.ova` file). The project demonstrates practical cybersecurity skills and a **methodical real-world security assessment workflow**.

---

## 🖥 Machine Setup

<details>
<summary>Click to expand</summary>

- **Platform:** Oracle VirtualBox  
- **VM Image:** Vulnerable `.ova` file  
- **Network:** Bridged Adapter  
- **Target Access:** `http://<VM_IP>:8080`  
- **Default Credentials:**  
  - Username: `Pawnward`  
  - Password: `qua121`  

</details>

---

## 🔍 Assessment Overview

<details>
<summary>Click to expand</summary>

The penetration testing assessment included:

- Host discovery & Nmap scanning  
- Port enumeration and service fingerprinting  
- Manual & automated web application testing  
- Exploit validation (LFI, sensitive file exposure, verbose errors, etc.)  
- Reviewing insecure HTTP methods  
- Identifying outdated or legacy components  
- OWASP-aligned vulnerability classification  
- Impact analysis and remediation recommendations

</details>

---

## 📂 Repository Structure

---

## 🛡 Key Highlights

- All findings, screenshots, and PoCs are included in the `Report/` directory.  
- Demonstrates methodical, real-world security assessment skills.  
- Provides actionable remediation recommendations for identified vulnerabilities.

---

## ⚠ Disclaimer

This virtual machine is **intentionally vulnerable** and intended strictly for educational purposes.  
Do **not** deploy or expose it outside a controlled testing environment.


