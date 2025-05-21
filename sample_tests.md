Test Case ID: TC_MD_001
Title: Successful User Registration from Markdown
Preconditions:
- The user is on the application's registration page.
Steps:
1. Enter "new_md_user" into the username field.
2. Enter "new_md_user@example.com" into the email field.
3. Enter "secureP@ss1" into the password field.
4. Confirm "secureP@ss1" in the confirm password field.
5. Click the "Register" button.
Expected Results:
- The user account should be created successfully.
- The user should be redirected to the login page or dashboard.
- A confirmation message "Registration successful" should be displayed.
---
Test Case ID: TC_MD_002
Title: Search Functionality from Markdown
Preconditions:
- The user is on the homepage.
- The search bar is visible.
Steps:
1. Enter "Test Product MD" into the search bar.
2. Click the "Search" icon or press Enter.
Expected Results:
- Search results page is displayed.
- Products matching "Test Product MD" are listed.
- If no products match, a "No results found" message is shown.
---
Test Case ID: TC_MD_003
Title: Password Reset Request from Markdown
Preconditions:
- User is on the "Forgot Password" page.
- User "forgot_md@example.com" exists in the system.
Steps:
1. Enter "forgot_md@example.com" into the email input field.
2. Click the "Send Reset Link" button.
Expected Results:
- A message "Password reset link has been sent to your email" is displayed.
- An email with a password reset link is sent to "forgot_md@example.com".