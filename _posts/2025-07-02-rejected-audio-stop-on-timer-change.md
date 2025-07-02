---
title: "Audio Playback Stops After Time Skip in Meditation App [Accepted but Not Fixed]"
date: 2025-07-02 19:45:00 +0700
categories: [Bug Review, Mobile App, Android]
tags: [bug, audio, playback, UX, rejected, Android]
---

> ⚠️ _This bug report was submitted during a crowdtest of a mental wellness mobile app. All product names, account details, and internal content titles have been anonymized for privacy and learning purposes._

---

## 🔍 Summary

While testing the single audio player in a meditation app on Android 15, I discovered that **the audio stops completely when the user skips forward using the time scrubber**. The player interface updates visually, but **no sound is played afterward**.

---

## 🎯 Environment

- **App Version:** 4.263.1 (424551)  
- **Device OS:** Android 15  
- **Module:** Single Audio Player  
- **User ID (anonymized):** _User.xxxxxxxxxxxxxxxxx  

---

## 🧪 Steps to Reproduce

1. Clear the app data  
2. Launch the meditation app  
3. Log in using valid test credentials  
4. On the home screen, tap the heart icon (Favorites)  
5. Tap on a meditation titled around _“burnout awareness”_  
6. Tap the "Begin" button  
7. While the audio is playing, swipe the time scrubber to skip forward  

---

## 💥 Actual Result

- The player updates the timer UI
- **No sound is played after the time is changed**
- Audio playback is completely lost

---

## ✅ Expected Result

- Audio should continue playing seamlessly from the new timestamp after the user adjusts the playback position

---

## 🎥 Attachment

-  
  (Demonstrates the audio cutting off after using the scrubber)

---

## 📌 Status & Feedback

### 🔴 **Bug Severity Adjusted**
- **Initial Report:** Critical  
- **Downgraded to:** High  
  _“Not a critical impact or blocker to users continuing to use the app.”_

### ✅ **Accepted (Paid), But Will Not Be Fixed**
- This issue was acknowledged but deemed **not relevant to the customer** at this time.
- It **will not be addressed** in the product roadmap, and **resubmissions are discouraged**.

---

## 💡 Takeaway

Even bugs that are accepted may not always lead to fixes — especially when:
- They don’t align with customer priorities
- Their impact is limited or considered edge-case
- The workaround (e.g., restarting playback) is simple enough

> _Still, reporting these edge cases helps paint a more complete QA picture — and you can still be compensated even if a bug won't be fixed._

---
