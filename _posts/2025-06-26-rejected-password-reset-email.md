---
title: "Rejected Bug Review: No Password Reset Email Received After Success Message"
date: 2025-06-26 19:20:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, account, email, UX, authentication]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

While testing the **password recovery flow** on a PWA, I encountered a case where the UI displayed a **success message**, but **no reset email** was actually received. This mismatch between frontend feedback and backend delivery raised a red flag — however, the report was ultimately **rejected**.

---

## ❌ Rejection Reason

> **Duplicate Bug**  
> A similar issue had already been reported by another tester during the same test cycle:  
> _"[Failed User Story] Password recovery link not received after requesting reset"_  
>  
> Since both reports shared the same root cause, only the first one was accepted per standard duplicate policy.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**Page:** Password Reset (`/login/reset`)  
**Browser:** Android Chrome  

### Steps to Reproduce:
1. Open the QA site  
2. Tap the **User icon**  
3. Tap **"Passwort vergessen?"**  
4. Enter a registered email  
5. Tap **"Absenden"**

### Actual Result:
A success message is displayed, but no recovery email arrives in the inbox.

### Expected Result:
An email containing the password reset link should be received promptly after the confirmation message.

---

## 🎥 Attachment

A screen recording was submitted showing the form being filled and the success message appearing — with no email received afterward.

---

## 🔁 Duplicate Learning

This bug was a **valid issue**, but timing matters — in crowdtesting, **duplicates get rejected** even if they’re well-reported. To avoid this:

- Always check the **“Similar Bugs”** panel during submission  
- Browse previously reported bugs if available in the test UI  
- When in doubt, ask in the test chat or TL notes

---

> ✅ *Filed under “Rejected Bug Review” — a good bug at the wrong time can still be a valuable experience.*
