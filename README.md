# Siva-Rajesh-Patnam-Bug-Report

 Bug Report: Siva Rajesh Patnam — Software Tester
1. Form allows invalid email
Steps to Reproduce: Go to “Apply Now” → Enter test@ in email field → Submit

Expected Behavior: Should show “Invalid email format” error

Actual Behavior: Form accepts and proceeds

Severity: Medium

Suggestion: Use stricter email validation

2. No error for empty required field
Steps to Reproduce: Go to “Get in Touch” → Leave all fields blank → Submit

Expected Behavior: Should show “Required field” errors

Actual Behavior: No error shown, form reloads

Severity: High

Suggestion: Add required field validation

3. Long input breaks layout
Steps to Reproduce: Enter 200+ characters in name field → Submit

Expected Behavior: Should wrap or truncate input

Actual Behavior: Layout breaks, text overflows

Severity: Medium

Suggestion: Limit character count or auto-wrap

4. Submit button not responsive on Firefox
Steps to Reproduce: Open “Apply Now” form in Firefox → Fill fields → Click Submit

Expected Behavior: Should submit form

Actual Behavior: Button does nothing

Severity: High

Suggestion: Fix browser compatibility for button click

5. Mobile layout overlaps
Steps to Reproduce: Open kraftshala.com on mobile → Scroll to form section

Expected Behavior: Should show clean layout

Actual Behavior: Fields overlap, hard to tap

Severity: Medium

Suggestion: Improve mobile responsiveness

6. No confirmation after form submission
Steps to Reproduce: Submit “Get in Touch” form

Expected Behavior: Should show success message

Actual Behavior: Page reloads with no feedback

Severity: Medium

Suggestion: Add confirmation message or redirect

