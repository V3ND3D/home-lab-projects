# Windows 11 Pro Hardening Project

## 📌 Summary
Hardened a personal Windows 11 Pro environment for cybersecurity and productivity purposes, applying defense-in-depth principles across system settings, encryption, network configurations, and telemetry management.

## 🎯 Goals & Purpose
- Create a secure, privacy-respecting Windows environment
- Eliminate unnecessary bloat, background telemetry, and default attack surfaces
- Ensure full control and observability over the OS and installed software
- Maintain system stability and usability for school, gaming, and lab operations

## 🧰 Tools & Stack
- Windows 11 Pro
- BitLocker (full disk encryption)
- PowerShell
- Group Policy Editor (`gpedit.msc`)
- Microsoft Defender Antivirus
- Custom DNS (router-level + OS-level)
- MAS Activation Toolkit
- GitHub hardening/debloat scripts (community vetted)

## 🔧 Features & Hardening Steps
- ✅ BitLocker enabled with TPM and PIN on system drive
- ✅ Defender Antivirus reconfigured (PUP detection on, cloud protection off)
- ✅ Windows Firewall fully enabled on all profiles (Domain, Private, Public)
- ✅ Controlled folder access & ransomware protection enabled
- ✅ App & browser control hardened (SmartScreen, exploit protection)
- ✅ Core Isolation + Memory Integrity enabled
- ✅ Disabled remote access features (RDP, Remote Assistance, Quick Assist)
- ✅ Disabled Cortana, OneDrive autostart, and Xbox background services
- ✅ Applied GitHub debloat scripts + manual service pruning
- ✅ Disabled telemetry, data collection, and feedback frequency via Group Policy
- ✅ Full dark mode & power plan set to "Ultimate Performance"
- ✅ Custom DNS applied via router and fallback in adapter settings

## 🔐 Security Considerations
- Local-first data model (no cloud dependency outside Proton Drive backup)
- PowerShell execution policy restricted (`AllSigned`)
- Defender exclusions reviewed to prevent abuse
- No third-party AV or optimization tools installed to minimize attack surface
- Updates reviewed and manually triggered (not automatic)
- *Windows Hello and Dynamic Lock intentionally not enabled to reduce Bluetooth and cloud dependency*

## 🚧 Planned Improvements
- Custom firewall rulesets and port restrictions (planned)
- Sysinternals integration (Process Explorer, Autoruns, TCPView)
- Scheduled PowerShell health checks and vulnerability scans
- Secure audit logging via Event Viewer baselines
