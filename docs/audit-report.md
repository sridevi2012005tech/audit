# Accessibility Audit Report

Website Audited: wikipedia.org
Tool Used: Google Lighthouse + Keyboard Navigation
Date: 11 Nov 2026

## 1. Images Missing Alt Text
Issue: Many images have no alt text
Priority: High
Fix: Add alt="description" to all <img> tags

## 2. Low Color Contrast
Issue: Light grey text on white background is hard to read
Priority: High
Fix: Use darker color, contrast ratio 4.5:1

## 3. Keyboard Navigation Issue
Issue: Tab key does not show focus clearly
Priority: Medium
Fix: Add :focus style in CSS

## 4. Heading Order Wrong
Issue: H1 after H3, order not correct
Priority: Medium
Fix: Use H1 -> H2 -> H3 in order

## 5. Form Labels Missing
Issue: Search box has no label
Priority: High
Fix: Add <label> for every input

Conclusion: Website is usable but needs accessibility fixes.
