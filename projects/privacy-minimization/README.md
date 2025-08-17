# Privacy Minimization & Cloud Independence Project

## 📌 Summary
This project documents my personal OPSEC and privacy journey — an intentional move toward minimizing my digital footprint, reducing cloud dependency, and maintaining local control over my identity, data, and devices.

---

## 🧠 Personal Privacy Philosophy

I’m not trying to disappear or live off-grid. I still use an iPhone, play games on PC and console, and enjoy the same tools everyone else does. But I apply discipline, limits, and context-aware decisions to how I use them.

I believe you can strike a balance between convenience and security. You don’t have to sacrifice all comfort to take back control — you just need to understand where your data goes, and who it serves.

---

## 🎯 My Goals
- Minimize exposure to centralized cloud ecosystems
- Retain full control over my devices, identity, and data
- Reduce attack surface while maintaining usability
- Build habits and workflows that prioritize privacy by default
- Stay adaptable without compromising discipline

---

## 🔐 Key Things I’ve Done
- Created my Apple ID using a ProtonMail burner address
- Disabled iCloud, Find My, iMessage, FaceTime, and Siri
- Avoid Google services entirely (except passive YouTube viewing)
- Use location services only for navigation, and only with Waze (no account, no background tracking)
- Run Proton Mail, VPN, and Pass as my core privacy tools — no Drive, Calendar, etc.
- Refuse Microsoft/Google account sign-in on any OS
- Store all documents locally or encrypted — no cloud dependency outside of Proton Drive for my resume

---

## 📱 Mobile Hardening (iPhone 14 Pro)

- Lockdown Mode is enabled 24/7
- No iCloud, AirDrop, Siri, or Apple Intelligence
- iMessage is tied only to my phone number — not my Apple ID
- Location Services are disabled system-wide, except during live navigation with Waze
- App permissions are manually reviewed; I deny access to camera, mic, Bluetooth, and contacts unless strictly needed
- ProtonVPN (Secure Core) is always on while in Puerto Rico, routing through Iceland/Switzerland
- App Tracking Transparency is set to block all tracking
- Push notifications are off for anything non-essential
- No cloud backups — all data is stored locally

---

## 🌐 Browser & Search

- I use Brave as my default browser with Shields maxed out (fingerprinting, HTTPS upgrade, cookie blocking)
- DuckDuckGo is my default search engine
- I don’t sign into browsers or sync to cloud accounts
- I **do** enable Brave Sync for bookmarks/settings across devices — it’s a usability tradeoff I’m okay with

---

## 🧱 Desktop Hardening

- Windows 11 Pro and macOS are both hardened — no telemetry, no Cortana, no bloat
- I use Group Policy and registry tweaks to control privacy settings and block background data collection
- Remote access tools like RDP, Quick Assist, and Remote Assistance are disabled
- I’ve enabled BitLocker and FileVault on all drives
- UAC is maxed out
- I regularly monitor startup items and running processes
- I’ve installed Kali VMs for future testing, but I’m holding off on sandboxing and advanced tools until I’m more confident — I won’t risk misconfigurations that could expose me

---

## 📎 Metadata Hygiene (In Progress)

- I only upload one file to the internet — my resume
- I haven’t started stripping metadata from images or PDFs yet, but I plan to implement tools like `ExifTool` or `PDF Redact Tools` going forward
- I don’t use cloud office suites or online resume builders

---

## 📧 Email Strategy

- I use ProtonMail exclusively
- I create aliases for one-time sites and apps — and delete them when no longer needed
- All aliases forward to my main inbox so I don’t miss anything
- I haven’t had to create multiple inboxes — Proton and good hygiene prevent spam
- I regularly audit my accounts and delete services I no longer recognize
- My Proton addresses have not appeared in any data leaks

---

## 🔐 App-Level OPSEC

- I deny camera, mic, Bluetooth, and contact access by default across all apps
- Every app on my devices serves a specific purpose — I don’t keep extras
- I make informed permission tradeoffs where needed, and revoke them later
- I don’t sandbox apps because my usage is already minimal and tightly controlled

---

## 💾 Backup & Recovery

- I don’t store sensitive files on my devices — they’re on paper only
- All my drives are encrypted
- I keep a printed and digital backup of my Proton Pass recovery keys (on a separate device)
- My resume and a few personal documents are stored on Proton Drive with E2E encryption
- I plan to expand to encrypted external drives and a NAS setup in the future


