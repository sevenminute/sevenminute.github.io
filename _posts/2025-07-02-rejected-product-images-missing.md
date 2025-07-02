---
title: "Rejected Bug Review: Missing Product Images in Category Overview Page"
date: 2025-07-02 19:05:00 +0700
categories: [Bug Review, PWA, Web]
tags: [bug, rejected, ecommerce, UI, scope, content]
---

> ⚠️ _This bug report was submitted during a crowdtesting session on a progressive web app (PWA). All identifiers and sensitive links have been redacted or anonymized for privacy and learning purposes._

---

## 🔍 Summary

While exploring the **"Reinigung & Haushalt"** category on an e-commerce PWA, I noticed that **product images failed to load** on the overview page. However, despite its impact on visual UX, the bug was **rejected** as **out of scope**.

---

## ❌ Rejection Reason

> **Out of Scope – Content Bug**  
> The issue was classified as a **content bug**, which was outside the scope of the test session.  
> According to test guidelines, missing or incorrect media assets (like images) fall under content-related problems, not functional issues — and were not part of the test coverage for this cycle.

---

## 🧪 Bug Behavior

**Platform:** PWA  
**Environment:** QA Site  
**Browser:** Android Chrome  

### Steps to Reproduce:
1. Open the QA site  
2. Scroll to the footer  
3. Tap on **Sortiment**  
4. Choose **Reinigung & Haushalt**

### Actual Result:
The product overview page shows **missing or broken image placeholders** for several items, resulting in a blank or incomplete layout.

### Expected Result:
Each product should have a clearly visible image to allow users to visually browse and differentiate between options.

---

## 🎥 Attachment

The video recording clearly demonstrated how most product cards on the page had no image displayed.

---

## 💡 Lesson Learned

Just because something looks broken, doesn't always mean it's **in-scope** for reporting. Crowdtesters should:

- **Review test instructions carefully**, especially regarding excluded bug types  
- Understand the difference between **functional bugs** (logic, behavior) and **content bugs** (text, images, metadata)  
- Use academy resources and test chat to confirm any gray areas

---

> ✅ *Filed under “Rejected Bug Review” — because even out-of-scope bugs can teach us something important about scope boundaries.*
