# Internal Notes – Windows 11 Hardening

## 🔍 Key Observations
- BitLocker with TPM and PIN is smooth on boot and doesn’t affect performance
- Microsoft Defender provides solid protection when reconfigured (PUP detection, controlled folder access)
- Default telemetry, background services, and cloud sync are overkill — stripping them down noticeably improved responsiveness

## ⚠️ Personal Trade-offs
- Skipped Windows Hello and Dynamic Lock to avoid pairing personal devices or relying on Bluetooth
- MAS activation used for full Pro features — not activated via Microsoft account
- Updates are handled manually — no automatic reboots or stealth patches

## 🧪 Things to Watch
- Periodically check Defender exclusions to ensure nothing was added without authorization
- Monitor Event Viewer for unauthorized service triggers or silent elevation attempts
- Still considering full manual firewall rulesets — but current defaults are fine for now
****
