---
title: "Rejected Bug Review: No Back Navigation on Order Overview Page"
date: 2025-06-26 18:30:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, UX, navigation, ecommerce]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

On the Order Overview page of a PWA checkout flow, I noticed that there was **no visible back navigation**, requiring users to rely on the browser's back button to return. Initially flagged as a UX issue, this report was ultimately **rejected**.

---

## ❌ Rejection Reason

> **Not a Bug (Intentional Design)**  
> The project team confirmed that this was a deliberate design choice. While a back button might enhance usability, its absence does not break functionality — making this a **feature suggestion**, not a defect.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**Device:** Android Chrome  
**Test Environment:** QA site

### Steps to Reproduce:
1. Visit the site  
2. Tap on cart  
3. Proceed to checkout (`Zur Kasse`)  
4. Choose "TWINT" as the payment method  
5. Tap `Weiter zur Bestellübersicht` to go to Order Overview

### Actual Result:
There is no in-app navigation (e.g., back arrow or button). Users can only go back using the **browser’s back** button.

### Expected Result:
A back button or visible navigation should be present to allow returning to the previous screen more intuitively.

---

## 🎥 Attachment

A screen recording was submitted, demonstrating the navigation issue during checkout.

---

## 💡 Lesson Learned

> 🔍 *Not everything inconvenient is a bug.*  
Some missing elements — even those that impact usability — might reflect product decisions. If core functionality isn’t broken, UX concerns can fall outside the scope of accepted bugs.

When in doubt:
- Ask the test lead if it's an oversight or intentional
- Check if it fits as a **usability suggestion** rather than a functional defect

---

> ✅ *Filed under “Rejected Bug Review” — because every rejection can teach you how to test smarter.*
