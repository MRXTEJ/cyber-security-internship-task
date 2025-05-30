# 🔒 Task 4 – Firewall Configuration (Cyber Security Internship)

## 🛠 Tools Used:
- Windows Firewall
- Telnet Client (enabled via Windows Features)
- PowerShell / CMD for testing

---

## ✅ What I Did:
1. Opened Windows Defender Firewall with Advanced Security.
2. Created a new inbound rule to **block TCP port 23 (Telnet)**.
3. (Optional) Created another rule to **allow TCP port 22 (SSH)**.
4. Enabled Telnet Client on Windows using PowerShell.
5. Used `telnet localhost 23` to test if the port was blocked.
6. Took screenshots of:
   - The created firewall rules
   - The failed Telnet test result

---

## 💻 Commands Used:

### ➕ Enable Telnet Client:
```powershell
dism /online /Enable-Feature /FeatureName:TelnetClient