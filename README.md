# Email-analysis
# Phishing Email Analysis Report

## 1. Sample Phishing Email
- **From:** Microsoft Support `<support@micros0ft.com>`
- **Subject:** URGENT: Your Microsoft account will be closed in 24 hours
- **Attachment:** `Account_Details.zip`
- **Link:** `http://bit.ly/AcctVerify123`

---

## 2. Sender’s Email Address
- Looks like Microsoft, but real domain is `micros0ft.com` (typo → zero instead of “o”).
- **Status:** Spoofed/Impersonated.

---

## 3. Email Header Check
- SPF/DKIM/DMARC = **fail**
- `Received` IP does not belong to Microsoft.
- **Status:** Header discrepancies confirm spoofing.

---

## 4. Suspicious Links/Attachments
- Link uses URL shortener → redirects to malicious site.
- Attachment is a `.zip` file → high malware risk.
- **Status:** Malicious indicators present.

---

## 5. Urgent/Threatening Language
- "Your account will be closed in 24 hours."
- **Status:** Creates fear/urgency → classic phishing trick.

---

## 6. Mismatched URLs
- Visible URL looks safe, but hover reveals different destination.
- **Status:** URL mismatch confirmed.

---

## 7. Spelling/Grammar Errors
- Minor typos, odd formatting, generic greeting ("Dear Customer").
- **Status:** Low professionalism → phishing sign.

---

## 8. Summary of Traits Found
- Spoofed sender (`micros0ft.com`)
- Header authentication failed
- Malicious shortened link
- Unsafe attachment (`.zip`)
- Threatening language
- URL mismatch
- Grammar mistakes + generic greeting

---

## ✅ Conclusion
This is a **phishing email** designed to trick the user into clicking a malicious link or opening an infected file.  

**Recommended Action:**
- Do not click/open any link or attachment.  
- Report to IT/security team.  
- Delete the email after reporting.  

---

## 🔁 Steps to Reproduce (Analysis Process)
1. **Obtain sample phishing email** (from training datasets or online repositories).  
2. **Inspect sender address** → check for spoofing/typos.  
3. **Analyze headers** → confirm SPF/DKIM/DMARC results using an online header analyzer.  
4. **Hover over links** → verify if URL matches the text shown.  
5. **Check for suspicious attachments** (`.zip`, `.exe`, `.docm`).  
6. **Look for urgency/threats** → “immediate action,” “account closed,” etc.  
7. **Check for spelling/grammar issues** and generic greetings.  
8. **Summarize findings** → list phishing traits and mark email as malicious.  

---

## 📊 Phishing Workflow Diagram

![Phishing Workflow](https://raw.githubusercontent.com/erichurst/markdown-images/master/phishing-workflow.png)

---

📌 *This report is created for educational and cybersecurity awareness purposes.*  
