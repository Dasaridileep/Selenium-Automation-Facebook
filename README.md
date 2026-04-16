# Facebook Sign-Up Automation Testing

This repository contains a comprehensive automation testing suite for the **Facebook Sign-Up** process. The goal is to ensure a seamless onboarding experience by validating form fields, data integrity, and cross-browser compatibility.

## 📌 Project Overview
Facebook’s account creation page is the primary entry point for new users. This project focuses on automating the validation of personal information collection, ensuring that unique user profiles are generated without friction across various environments.

### Business Problem Solved
To maintain high user acquisition, Facebook must ensure the registration process is flawless. This framework addresses:
* **Form Validation:** Ensuring only valid data is processed.
* **Field Acceptance:** Verifying that names, emails, and passwords meet specific criteria.
* **Flow Integrity:** Guaranteeing a smooth submission process without runtime errors.

---

## 👤 Business Scenario: User Registration
1.  **Visit Sign-Up Page:** Verify the page loads correctly across all supported browsers (Chrome, Edge, etc.).
2.  **Name Input:** Validate that First and Last Name fields accept alphabets, spaces, and special characters.
3.  **Contact Info:** Validate Mobile Number or Email for correct formatting, as these are critical for account verification.
4.  **Security:** Ensure the Password field meets security requirements.
5.  **Date of Birth:** Verify the functionality of the three distinct dropdowns (Day, Month, Year).

---

## 🔍 Automation Scope
The automation framework is designed to validate the following key areas:

| Category | Validation Logic |
| :--- | :--- |
| **Field Acceptance** | All fields accept correct input types. |
| **Mandatory Fields** | Form prevents submission if required fields are empty. |
| **DOB Logic** | All 3 dropdowns function correctly and hold valid data. |
| **Error Handling** | Correct error messages appear for invalid or missing input. |
| **UI Actions** | Clicking the "Sign Up" button triggers the intended registration flow. |
| **Cross-Browser** | Consistent behavior across Chrome and Microsoft Edge. |

---

## 🧪 Test Cases
### ✅ Positive Test Cases
* **Successful Registration (Mobile):** Register using a valid mobile number and mandatory fields.
* **Successful Registration (Email):** Register using a valid email address and all required information.
* **Dropdown Selection:** Successfully select a valid Date of Birth using the UI dropdowns.

### ❌ Negative Test Cases
* **Empty Name:** Attempt to submit the form with the "First Name" field blank.
* **Invalid Format:** Enter an incorrectly formatted mobile number or email address.
* **Missing Password:** Attempt to register while leaving the password field empty.
* **Underage Validation:** (Optional) Verify system behavior when DOB indicates a user below the required age.

---

## 🛠️ Tech Stack
* **Language:** Java
* **Automation Tool:** Selenium WebDriver
* **Browser Support:** Chrome, Microsoft Edge
* **Testing Pattern:** Page Object Model (POM)

---

## 🚀 How to Run the Tests
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/facebook-signup-automation.git](https://github.com/your-username/facebook-signup-automation.git)
