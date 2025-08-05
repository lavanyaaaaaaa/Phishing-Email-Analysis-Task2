# 📧 Phishing Email Analysis Task

## 🔐 Key Concepts
Phishing, email spoofing, header analysis, social engineering, threat detection

## 🎯 Objective
Analyze a suspicious email to identify phishing indicators using free tools and manual inspection techniques.

---

## 📥 Email Sample Details

- **Sender**: Amazon Account Security `<alert@amaz0n-support.com>`
- **Subject**: 🚨 Urgent: Suspicious Login Attempt Detected
- **Date**: 5 Aug 2025
- **Attachment**: `Amazon_Lock_Info.html`
- **Suspicious Link**: `http://amaz0n-verify-login.com`

---

## 🔍 Phishing Indicators Found

| Indicator               | Description |
|-------------------------|-------------|
| 📧 Spoofed Email        | From `amaz0n-support.com` (misspelled domain) |
| 🕵️ Header Analysis      | SPF fail, DKIM missing, IP from Russia |
| 🔗 Suspicious URL        | Hover reveals phishing URL |
| ⚠️ Urgent Language       | “Your account will be suspended in 24 hours” |
| 🧪 Grammar/Spelling      | Slightly unnatural language |
| 📎 Attachment            | `.html` login form that mimics Amazon |
| 🎯 Social Engineering    | Creates fear of account compromise |

---

## 🛠 Tools Used

- **MXToolbox Header Analyzer**: [https://mxtoolbox.com/EmailHeaders.aspx](https://mxtoolbox.com/EmailHeaders.aspx)
- **VirusTotal URL Scanner**: [https://www.virustotal.com/](https://www.virustotal.com/)
- **Manual inspection** (link hover, grammar check)

---

## 🧾 Files Included in Repo

| File | Purpose |
|------|---------|
| `phishing_sample.txt` | The fake phishing email |
| `raw_header.txt` | Header copied into MXToolbox |
| `suspicious_link_report.txt` | VirusTotal scan result |
| `Amazon_Lock_Info.html` | Simulated malicious attachment |
| `README.md` | Final summary/report |

---

## ✅ Conclusion

This email demonstrates multiple classic phishing characteristics:
- Spoofed sender
- Social engineering tactics
- Dangerous links
- Technical header failures

It is **confirmed phishing** and should be avoided or reported.
