---
title: "Error Message After Language Change: 'Something Went Wrong' on Content Load [Rejected as Duplicate]"
date: 2025-07-01 20:15:00 +0700
categories: [Bug Review, Mobile App, Android]
tags: [bug, localization, content error, video, rejected, Android]
---

> ⚠️ _This bug was submitted during a mobile app test cycle. All app identities, internal account details, and content names have been anonymized to focus on the bug pattern and decision rationale._

---

## 🧠 Summary

When the user changes the app language to **French** and tries to access a piece of mindfulness content titled _“Redefining success”_, the app displays a **"Something went wrong"** error screen instead of loading the video or audio as expected.

---

## 🧪 Environment

- **App Version:** 4.263.1 (424551)  
- **Device OS:** Android 15  
- **User ID (anonymized):** _USER_XXXXXXXXXXXXX_  
- **Language:** Français (after switching from English)

---

## 📝 Steps to Reproduce

1. Open the meditation app  
2. Log in with a valid test account  
3. Change the language setting to **Français**  
4. Navigate to **Explore** tab  
5. Tap on the section “you mint matter”  
6. Tap on the item titled “Redefining success”

---

## 💥 Actual Result

- Instead of opening the content page, a **"Something went wrong"** error message appears
- Content fails to load

---

## ✅ Expected Result

- The app should load the content page normally, displaying relevant media, text, and controls without showing an error

---

## 📎 Attachment

-  
  (Captures the error appearing upon tapping the content after switching language)

---

## 📌 Status & Feedback

### ❌ **Bug Rejected as Duplicate**
- This issue was already listed in the **Known Bugs tab**,
  > _Video Player: Unable to play video after switching to Chinese – “Something went wrong” error_

### 🧩 Reason for Rejection
- The **root cause is the same**: Content fails to load after language change
- Only the first report of the bug is accepted, as fixing that will resolve related variants

---

## 💡 Takeaway

Even if the **visible behavior occurs in different sections or languages**, **the root cause matters most** in crowdtesting:
- Check **Known Bugs** and **Similar Bugs** tabs carefully
- If the error message and trigger pattern match an existing report, it’s likely to be considered a duplicate

> _Still, your effort helps validate the issue’s consistency across multiple locales. Great practice and keep going!_

---
