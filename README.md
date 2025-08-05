# Phishing-Email-Analysis-Task2

# 📧 Phishing Email Analysis Report

## 🔐 Key Concepts
Phishing, email spoofing, header analysis, social engineering, threat detection

## 📌 Objective
To analyze a suspicious email and identify indicators of phishing using free tools and manual inspection.

---

## 📥 Sample Email Summary

- **Subject**: "Important Notice: Account Suspended"
- **From**: `support@paypall.com`
- **Date**: August 5, 2025

---

## 🛠 Tools Used

- Email Header Analyzer: [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)
- VirusTotal for link inspection: [https://www.virustotal.com/](https://www.virustotal.com/)
- Manual inspection (hover links, sender address)

---

## 🔍 Phishing Indicators Identified

1. **Spoofed Email Address**  
   - Display name: PayPal  
   - Actual address: `support@paypall.com` (misspelled domain)

2. **Email Header Analysis**
   - SPF: Fail  
   - DKIM: Not present  
   - Sending IP: Originates from suspicious geolocation

3. **Suspicious Link**
   - Hyperlink text: `https://paypal.com/verify`
   - Actual link: `http://malicious-phish.xyz/login`

4. **Urgent Language**
   - “Your account will be suspended in 24 hours.”
   - Classic pressure tactic

5. **Grammar/Spelling Errors**
   - “You’re account has been suspened.”

6. **Attachment**
   - `secureform.html` — contains embedded login form

---

## 📷 Screenshots

- Header analysis results
- Hovered link mismatch

*(Screenshots attached in repo)*

---

## ✅ Conclusion

This email shows **strong signs of phishing** using:
- Social engineering (urgency)
- Email spoofing
- Malicious links
- Technical red flags in headers

It is confirmed as **phishing** and should not be trusted.

---

## 📎 Files Included

- `phishing_sample.txt`
- `header_analysis_screenshot.png`
- `suspicious_link_report.txt`

---
