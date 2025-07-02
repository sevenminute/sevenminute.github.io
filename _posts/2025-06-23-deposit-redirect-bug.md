---
title: "Deposit Page Fails to Redirect After Submission"
date: 2025-06-23 14:42:00 +0700
categories: [Bug Report, Android]
tags: [bug, android, deposit, functional, critical,accepted]
---
> 🛡️ _This bug log is based on a real report submitted through a crowdtesting project. All sensitive data such as company name, user info, and internal references have been anonymized for publication purposes._

## 🔍 Summary  
After submitting a deposit via bank transfer, the app fails to redirect the user to the expected payment code page. Instead, it navigates back to the payment method selection.

---

## 📱 Environment  
- Device: Infinix Note 40  
- OS: Android 14  
- Network: Telkomsel  
- App Type: Native  
- App Version: 2.3.6  
- Build: `2.3.6dep`

---

## 🎯 Steps to Reproduce  
1. Open the application  
2. Tap the cashier icon  
3. Select **Deposit**  
4. Choose **Bank Transfer**  
5. Enter a valid amount and tap **Continue**  
6. Observe the screen transition

---

## ✅ Expected Result  
User should be redirected to a **payment code page** to complete the transfer.

---

## ❌ Actual Result  
App navigates **back to the payment method selection page**. A message appears stating:  
> "Transaction was not successful"

---

## ⚠️ Severity  
**Critical** – Prevents users from completing a transaction.

---

## 💬 Notes  
- Issue occurred once during structured test execution  
- Similar issues have been reported involving redirection failures on the deposit flow  
- This report was originally filed as part of a functional test case scenario

---

> _Reported by: sevenminute_  
> _Cycle Date: June 18, 2025_  
