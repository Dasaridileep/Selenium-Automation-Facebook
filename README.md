<h1>Facebook Account Creation</h1>
What is Facebook Sign Up?
Facebook’s account creation page is the entry point for new users to join the platform. It collects essential personal information to generate a unique user profile, which then unlocks access to Facebook’s social and business tools.
Business Problem Being Solved
Facebook must ensure that every new user can successfully create an account with valid details across all browsers and devices. Key challenges include:
•	Proper form validation
•	Correct field acceptance
•	Smooth submission flow without errors
👤 Complete Business Scenario
🔵A new user who wants to create a Facebook account
1️⃣ Visit Sign Up Page User visits facebook.com and sees the registration form. Why it matters: Page must load correctly across browsers.
2️⃣ Enter First & Last Name User types their name in the fields. Why it matters: Fields must accept alphabets, spaces, and special characters.
3️⃣ Enter Mobile Number or Email User provides a phone number or email. Why it matters: Used for verification and login — must validate correctly.
4️⃣ Enter Password User creates a password. 
🔍 What an Automation Framework Would Validate
Field acceptance	All fields accept correct input
Mandatory fields	Form doesn’t submit if empty
DOB dropdown	All 3 dropdowns function correctly
Error messages	Correct errors shown for invalid input
Submit button	Clicking Sign Up triggers correct action
Cross browser	Works on Chrome, Edge


🧪 Test Cases You Can Derive
Positive Test Cases
•	Register with valid mobile number ✅
•	Register with all mandatory fields filled ✅
Negative Test Cases
•	Submit form with empty first name ❌
•	Enter invalid Number format ❌
•	Leave password blank ❌



