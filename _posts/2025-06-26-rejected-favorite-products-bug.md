---
title: "Rejected Bug Review: Missing Favorite Products in Wishlist"
date: 2025-06-26 20:40:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, website, wishlist, PWA, UX, duplicate]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All product names, URLs, and identifiers have been anonymized for documentation purposes._

---

## 🔍 Summary

While testing the wishlist functionality in a home improvement PWA, I noticed that after favoriting four products from the search results, only one of them appeared in the favorites list. The other three were missing — but the bug was ultimately **rejected as a duplicate**.

---

## ❌ Rejection Reason

> **Duplicate Bug**  
> The issue had already been reported by another tester during the same test cycle. Although my steps were slightly different, the root cause and outcome were considered the same as an existing bug (ID: #2723457).

The takeaway: **only the first report of a bug with a shared root cause will be accepted**, even if the symptoms appear through different workflows.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**URL:** *(QA environment, anonymized)*  
**Device:** Android Chrome Browser  

### Steps to Reproduce:
1. Go to the QA site  
2. Use the search bar and type `'Star LED-Leuchtmittel'`  
3. From the results page, favorite 4 different products  
4. Tap the user icon  
5. Go to `'Merkliste'` (favorites list)

### Actual Result:
Only **1 out of 4** favorited products appears in the wishlist.

### Expected Result:
All 4 selected items should be visible in the favorites list, as they were actively marked during the session.

---

## 🎥 Attachment

A screen recording was submitted showing the missing items in the favorites list after selection.

---

## 🧠 Reflection

This bug surfaced a **real UX issue**, but since it had already been captured earlier in the test by another tester, the system flagged it as a duplicate.

It’s a good reminder to:
- Review existing submitted bugs before posting  
- Check for **similar symptoms caused by the same backend or sync logic issue**

---

## 💡 Lesson Learned

When testing:
- Always **check the Similar Bugs section** before submitting  
- Understand that **different workflows** may still lead to the **same underlying defect**

---

> ✅ *Filed under “Rejected Bug Review” — because duplicates still provide insight into reproducibility and help sharpen bug reading awareness.*
