---
title: "Rejected Bug Review: No Newsletter Confirmation Email Received"
date: 2025-07-02 19:30:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, email, UX, account, newsletter]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

While testing the **newsletter subscription flow** under the personal account section of a PWA, I noticed that no **confirmation email** was sent even after tapping “Abonniert” and saving the preferences. This blocked the user from completing their newsletter opt-in — but the report was **rejected**.

---

## ❌ Rejection Reason

> **Duplicate Bug**  
> This same issue had already been reported in the same test cycle under:  
> _"[Failed User Story] User cannot complete newsletter subscription in Account section due to missing confirmation email"_  
>  
> As per testing policy, only the first report of a bug with a shared root cause will be accepted.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**Section:** Personal Data → Newsletter  
**Browser:** Mobile Chrome  

### Steps to Reproduce:
1. Log in and go to **Meine Daten**  
2. Tap **"Ändern"** in the Newsletter section  
3. Select **"Abonniert"** and choose a local store  
4. Tap **"Speichern"**  
5. Tap **"Bestätigungs-E-Mail erneut senden"**  
6. Check inbox

### Actual Result:
No confirmation email is received at any point in the process.

### Expected Result:
User should receive a confirmation email allowing them to finalize the subscription process.

---

## 🎥 Attachment

A screen recording was provided demonstrating the full process and the lack of any confirmation email despite success messages.

---

## 🧠 Reflection

This is another classic example of a **duplicate functional issue**. Even if it’s well-documented and reproducible, if someone else reports the same root cause first, later reports won’t be accepted.

---

## 💡 Tips to Avoid Duplicate Rejections

- Always scan the **"Similar Bugs"** panel during report submission  
- Read through earlier entries under “Already Submitted Bugs” in the test overview  
- Ask the test lead if unsure whether an issue is already known  

---

> ✅ *Filed under “Rejected Bug Review” — a reminder that crowdtesting is not just about finding bugs, but also about timing and awareness.*
