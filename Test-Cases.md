# Test Cases – E-commerce Website

**Project:** E-commerce Website Manual Testing  
**Application:** https://www.saucedemo.com/  
**Testing Type:** Functional Testing

## TC_LOGIN_001 – Login with Valid Credentials

- **Test Scenario:** Verify that a user can log in with valid credentials.
- **Preconditions:** The application login page is open.
- **Test Data:** Use valid credentials provided by the demo application.
- **Steps:**
  1. Open the application.
  2. Enter a valid username.
  3. Enter the corresponding password.
  4. Click the Login button.
- **Expected Result:**  Login was successful, and the products page was displayed. The URL ended in /inventory.html.
- **Actual Result:**  Pass.
- **Status:** Not Executed.

## TC_LOGIN_002 – Login with Invalid Password

- **Test Scenario:** Verify login behavior when an incorrect password is entered.
- **Preconditions:** The application login page is open.
- **Test Data:** Valid username and incorrect password.
- **Steps:**
  1. Open the application.
  2. Enter a valid username.
  3. Enter an incorrect password.
  4. Click the Login button.
- **Expected Result:** Login should be rejected, and an appropriate error message should appear.
- **Actual Result:** Pending execution.
- **Status:** Not Executed.

## TC_LOGIN_003 – Login with Empty Fields

- **Test Scenario:** Verify login behavior when both fields are empty.
- **Preconditions:** The application login page is open.
- **Test Data:** Username: Empty; Password: Empty.
- **Steps:**
  1. Open the application.
  2. Leave the username and password fields empty.
  3. Click the Login button.
- **Expected Result:** Login should be rejected, and a suitable validation message should appear.
- **Actual Result:** Pending execution.
- **Status:** Not Executed.

## TC_CART_001 – Add a Product to the Cart

- **Test Scenario:** Verify that a user can add a product to the shopping cart.
- **Preconditions:** The user is logged in and the products page is displayed.
- **Test Data:** Any available product.
- **Steps:**
  1. Select a product.
  2. Click its Add to Cart button.
  3. Open the shopping cart.
- **Expected Result:** The selected product should appear in the shopping cart.
- **Actual Result:** Pending execution.
- **Status:** Not Executed.

## TC_CHECKOUT_001 – Checkout with Valid Customer Details

- **Test Scenario:** Verify that a user can proceed through checkout with valid required details.
- **Preconditions:** The user is logged in and has added a product to the cart.
- **Test Data:** Valid first name, last name, and postal code.
- **Steps:**
  1. Open the shopping cart.
  2. Click Checkout.
  3. Enter the required customer details.
  4. Continue to the order summary.
- **Expected Result:** The user should reach the order summary with the selected product and correct displayed totals.
- **Actual Result:** Pending execution.
- **Status:** Not Executed.

## Execution Note
All test cases must be executed against the application before actual results and final statuses are recorded.
