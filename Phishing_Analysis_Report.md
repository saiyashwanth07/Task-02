# 🧠 Phishing Email Analysis – Task 2 (Cyber Security Internship)

## 📋 Objective
Analyze a suspicious email to identify phishing characteristics such as spoofed sender domains, malicious links, and deceptive language.

---

## 📧 Email Sample Used
**Subject:** “Please verify your email address”  
**Sender:** `GitHub@bigdogdomains.co`  
**Impersonated Organization:** GitHub  
**Body Summary:**  
The email claimed to be from GitHub and asked the user to verify their email via a blue button labeled *“Verify email address.”*

---

## 🕵️‍♂️ Observations & Indicators

| Category | Finding | Reason for Suspicion |
|-----------|----------|----------------------|
| Sender Domain | `GitHub@bigdogdomains.co` | Not an official GitHub domain |
| Recipient | Mentions `ethan@hooksecurity.co` | Mismatched and suspicious |
| Salutation | “Almost done, Demo!” | Generic greeting – typical in phishing |
| Link Button | “Verify email address” | Hidden/masked link (potentially malicious) |
| Urgency | “To complete your sign-up…” | Social engineering technique |
| Grammar | Professional but templated | Copied style from real GitHub emails |

---

## 🧰 Tools Used
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [VirusTotal URL Scanner](https://www.virustotal.com)
- Hover-over link inspection (manual verification)

---

## 🔍 Analysis Summary
The email is a **phishing attempt** that impersonates GitHub using:
- **Spoofed sender domain**
- **Deceptive verification link**
- **Social engineering language**

It likely leads users to a fake GitHub login page to **harvest credentials**.

---

## 🛡️ Preventive Measures
- Always verify sender domain authenticity.
- Hover over links to inspect real URLs before clicking.
- Never enter credentials on redirected pages.
- Enable 2FA (Two-Factor Authentication).
- Report and delete suspected phishing emails.

---

## 🧾 Outcome
Gained awareness of:
- Phishing detection methods  
- Email spoofing and header analysis  
- How social engineering is used to deceive users  

---

## 📁 Repository Files
