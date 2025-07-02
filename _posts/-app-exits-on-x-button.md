---
title: "Rejected Bug Review: App Exits Instead of Going Back (Video Player)"
date: 2025-07-01 16:30:00 +0700
categories: [Bug Review, Android]
tags: [bug, rejected, mobile, UX, player, app crash, crowdtesting]
---

> ⚠️ _This bug report was originally submitted for a mobile testing cycle. All app names, account details, and user IDs have been anonymized. Shared for learning and portfolio purposes only._

---

## 🔍 Summary

While testing a video playback feature on a meditation and wellness app (v4.263.1, Android 15), I encountered a behavior where tapping the **X** button on the video player caused the entire app to close instead of returning to the previous screen.

At first, I believed it was a critical UX issue. However, it was later **rejected** by the test lead.

---

## ❌ Rejection Reason

> **Duplicate**  
> A similar bug had already been reported in the Known Bugs tab, with a slight difference in the steps.

In my video, I had pressed the device’s **Back** button first, then tapped the **X**, which triggered the issue. This step was missing in the written bug report — making it different from what I claimed.

---

## 🧪 Bug Behavior

**Platform:** Android 15  
**App Version:** 4.263.1  
**Device:** Generic Android device  
**Environment:** Native mobile app

### Steps Performed:
1. Open the app and log in  
2. Tap on a video from the home screen  
3. (Unstated in report, but seen in video) Press the device's **Back** button  
4. Then tap the **X** button on the player

### Actual Result:
App exited completely and closed

### Expected Result:
The video player should close and return to the previous screen inside the app

---

## 🎥 Attachment

A screen recording was submitted, showing the behavior, but missing written explanation of the extra step.

---

## 🧠 Reflection

This bug helped me realize two key things:
- **Mismatch between written steps and actual behavior in video** can cause confusion
- Always **check for similar known issues**, even if the flow seems slightly different

---

## 💡 Lesson Learned

For future reports:
- I will include all exact interactions, even subtle ones like pressing the **Back** button
- I’ll take time to carefully scan Known Bugs, especially for similar UX flows

---

> ✅ *Filed under “Rejected Bug Review” — because not every mistake is a failure; it’s a chance to level up.*
