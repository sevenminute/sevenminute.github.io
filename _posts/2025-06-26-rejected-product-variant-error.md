---
title: "Rejected Bug Review: Error Page on Product Variant Selection"
date: 2025-06-26 18:10:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, variant, product, UX, website]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

While browsing a product detail page on a QA e-commerce PWA, I encountered an error when attempting to select a variant. Tapping on a specific wood type option (`Eiche`) led to an error screen — but this bug report was eventually **rejected** as a duplicate.

---

## ❌ Rejection Reason

> **Duplicate Bug**  
> A similar issue involving product variant selection had already been reported in the same test cycle (ID #2723568).  
> According to the test team, both issues shared the same root cause — thus only the first report was accepted.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**Device:** Android Chrome  
**Test Environment:** QA site

### Steps to Reproduce:
1. Visit the test site  
2. Search for: `Regalstollen eiche`  
3. Click the product from search results  
4. Scroll to the **Holzart** (wood type) section  
5. Tap the **Eiche** variant

### Actual Result:
User is redirected to an error page with the message:  
> `Entschuldigung, das hat nicht funktioniert.`  
> ("Sorry, that didn’t work.")

### Expected Result:
The page should display the product list for the selected variant (oak wood), fully loaded without errors.

---

## 🎥 Attachment

A screen recording showing the issue in action was included with the original report.

---

## 💡 Lesson Learned

> 🧠 *Always check for duplicates before submitting!*  
Even when an issue seems specific, it might be part of a broader problem already reported by another tester.

When working with **product variants**, errors in loading can often stem from the same backend/API flaw — and those are treated as **one root cause**.

---

> ✅ *Filed under “Rejected Bug Review” — because testing isn’t just about finding bugs, it’s about learning from the process too.*
