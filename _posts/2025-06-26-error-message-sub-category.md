---
title: "Rejected Bug Review: Error Message on Sub-category Page"
date: 2025-06-26 17:10:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, website, navigation, PWA, UX]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

While navigating a home & garden e-commerce PWA, I found that tapping a certain sub-category in the menu returned an error message instead of the expected content. This looked like a broken link issue at first glance — but the report was ultimately **rejected**.

---

## ❌ Rejection Reason

> **Not a Bug (By Design)**  
> The links in the QA environment were intentionally non-functional due to unmaintained test data from the backend (DISCO API).

So, although the issue looked like a broken sub-category page, it was actually caused by incomplete data in the test environment — not a true bug in production logic or frontend implementation.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**URL:** *(QA environment, anonymized)*  
**Device:** Android Chrome Browser  

### Steps to Reproduce:
1. Visit the test site  
2. Open the navigation menu  
3. Go to: `Anleitungen & Ratgeber` → `Garten & Freizeit` → `Rasen Mähen` → `Rasensorten`  
4. Tap the final sub-category: `Rasen`

### Actual Result:
> `Entschuldigung, das hat nicht funktioniert.`  
> ("Sorry, that didn't work.")  
The page fails to load and displays a default error message.

### Expected Result:
The selected category page should load properly with all related content or product listings.

---

## 🎥 Attachment

A screen recording was submitted showing the error message appearing upon interaction.

---

## 🧠 Reflection

This was a valuable reminder that:
- Not all broken flows are bugs — sometimes they’re due to unmaintained test environments  
- It's important to understand the **difference between test data issues and actual defects**

---

## 💡 Lesson Learned

When testing on **staging or QA environments**, always:
- Confirm whether the issue is reproducible in production (if accessible)  
- Consider asking the project lead whether a specific section is fully implemented or populated

---

> ✅ *Filed under “Rejected Bug Review” — because even false alarms can sharpen your instincts as a tester.*
