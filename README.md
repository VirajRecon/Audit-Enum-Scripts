# 🛡️ Win10 & 7 Audit & Enumeration Script

A powerful PowerShell-based enumeration script designed for auditing and assessing Windows 10 system security settings, user access, services, and more. Ideal for red teaming, blue teaming, and Windows hardening reviews.

---
## 🔍 Features
- 📄 Audits system info, OS version, and installed products
- 🔐 Checks:
  - Windows Firewall, UAC, PowerShell version
  - Local security products: antivirus, antispyware, firewall
  - Password and lockout policy
  - Patches
- 🗂️ Enumerates:
  - Shares with “Everyone” access
  - Domain/local group memberships
  - Writable/configurable/unquoted path services
  - DLL hijackability & autoruns
  - Scheduled tasks and unattended install files
  

many more.
---

## 🚀 Usage

> ⚠️ Run as Administrator for full audit output

```powershell
# From an elevated PowerShell window
powershell -ExecutionPolicy Bypass -File .\winaudit_10.ps1
```

---

## 📁 Output

The script outputs results to:
- `report-[COMPUTERNAME].txt` — Primary system report
- `exceptions-[COMPUTERNAME].txt` — Any errors or exceptions

---

## 📌 Requirements

- Windows 10
- PowerShell 2.0 or above
- Administrator privileges recommended

---

## 📝 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

## 👤 Author

Created by **Viraj K Mota**  
GitHub: [VirajRecon](https://github.com/VirajRecon)  
LinkedIn: [linkedin.com/in/virajmota](https://www.linkedin.com/in/viraj-mota/)

---

> “Audit fast. Report smarter.”
