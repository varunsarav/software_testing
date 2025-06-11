# 🧪 Registration Page Functional Testing – CAPTCHA Issue

## 📄 Project Overview
This repository contains manual functional testing artifacts for the **registration page** of the Testing World web application. The focus is on validating CAPTCHA functionality as part of the signup flow.

### 🔎 Objective
- Verify the correct display and operation of the CAPTCHA during user registration.
- Ensure users cannot proceed without completing the CAPTCHA challenge.

---

## ⚙️ Environment & Test Setup

- **Application Under Test**: Testing World – Experienced in making experts  
- **Test URL**: Registration page accessible via the “Register” link at the top-right corner  
- **Environment**:
  - Browser: Chrome / Firefox / Safari / Edge
  - OS: Windows 10, macOS, Android, iOS
  - Network: Standard and high-latency/VPN

---

## 🧩 Test Plan Overview

1. Navigate to the registration page.
2. Confirm presence of CAPTCHA image or widget.
3. Attempt to enter registration data without captcha.
4. Attempt to complete registration after interacting with captcha.
5. Verify user cannot submit the form if CAPTCHA is missing or incorrect.
6. Log any defects found (e.g., missing CAPTCHA, broken challenge).

---

## ⚠️ Bug Report: Missing CAPTCHA on Registration Page

- **Issue Summary**: CAPTCHA is not displayed and input is not enforced.
- **Steps to Reproduce**:
  1. Go to Testing World registration page.
  2. Observe registration form—CAPTCHA element should be visible.
  3. Attempt registration without completing CAPTCHA.
- **Expected Result**:
  - CAPTCHA challenge should display (image, checkbox, etc.).
  - Form should not submit until CAPTCHA is validated.
- **Actual Result**:
  - No CAPTCHA element on the registration page.
  - User can submit registration without completing CAPTCHA.

---

## 📊 Test Results (Link)

Public test report & results are available here:  
➡️ [View Detailed Test Plan & Results](https://testcollab.io/project/16171/test_plans/66564/view?public_token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJjb21wYW55Ijo5NjUyLCJwcm9qZWN0IjoiMTYxNzEiLCJlbnRpdHkiOiJ0ZXN0cGxhbiIsImVudGl0eUlkIjo2NjU2NCwiaWF0IjoxNzQ5NjI3NDE2fQ.31qyrfn7VookVIMfhZX0eKGmdPMt4PnLHe-429dEyLI&region=US)

---

## ✅ Outcome & Next Steps

- CAPTCHA functionality is missing entirely—critical issue.  
- Registration can be completed without validation—security & spam risk.  
- **Recommendation**: Block form submission and implement or repair CAPTCHA flow.

---

## 📝 How to Contribute

1. Fork this repository.
2. Create a branch for your proposed change (e.g., `fix/add-captcha`).
3. Update README, test cases, or add new defect reports.
4. Submit a pull request detailing the added tests, logs, or fixes.

---

## 📇 Contact / Project Maintainer

- **Name:** [Varun]  
- **Email:** [varunsaravanan2004@gmail.com]  
- **Project Tool:** TestCollab (See link above for reports)

---

## 🏁 License

This project is released under the [MIT License](LICENSE).

