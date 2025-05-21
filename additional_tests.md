## Additional Markdown Test Cases

Title: Add Multiple Items to Wishlist MD
Preconditions:
- User is logged in.
- Products "Wireless Keyboard" and "Gaming Mouse" exist.
Steps:
1. Navigate to "Wireless Keyboard" product page.
2. Click "Add to Wishlist".
3. Navigate to "Gaming Mouse" product page.
4. Click "Add to Wishlist".
5. Go to Wishlist page.
Expected Results:
- "Wireless Keyboard" is present in the wishlist.
- "Gaming Mouse" is present in the wishlist.
- Wishlist count reflects 2 items.
---
Title: Attempt to Access Admin Page as Regular User MD
Preconditions:
- User "normal_user_md" is logged in with regular privileges.
- Admin page exists at "/admin/dashboard".
Steps:
1. User "normal_user_md" attempts to navigate directly to "/admin/dashboard".
Expected Results:
- User is redirected to a "403 Forbidden" or "Access Denied" page.
- User is not shown the admin dashboard content.
