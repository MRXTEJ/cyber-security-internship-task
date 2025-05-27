## Phishing Email Analysis Report

### 📨 Sample Email:

**Subject**: Important Account Notice: Action Required Immediately

**From**: support@paypa1.com

**Body**:
> Dear Customer,
>
> We has detect unusual activity in your account. Your account will be locked in 24 hours if you not verify it. Please click the link below to secure your account:
>
> [Verify Now](http://malicious-site.com/login)
>
> Thank you,
> PayPal Support Team

**Attachment**: invoice.js

---

### ⚠ Identified Phishing Indicators:

1. **Spoofed Sender Email**: The domain `paypa1.com` is suspicious and mimics the legitimate `paypal.com`.
2. **Urgent Language**: Phrases like "account will be locked in 24 hours" create fear and urgency.
3. **Mismatched Link**: The displayed text says "Verify Now" but links to `http://malicious-site.com/login`.
4. **Grammar and Spelling Errors**: "We has detect" and "you not verify" indicate poor language quality.
5. **Header Mismatch**: (To be analyzed using an online header analyzer if email headers are available.)
6. **Unusual Attachment**: The `.js` file can be used to execute malicious scripts.
7. **Suspicious Request**: Requests login verification through a non-secure external link.

---

### ✅ Conclusion:
This email is a phishing attempt. It uses spoofed sender information, urgent language, suspicious attachments, and grammar mistakes to trick recipients into clicking a malicious link and possibly downloading malware.

