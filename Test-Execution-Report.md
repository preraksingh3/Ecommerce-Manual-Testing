# Test Execution Report – E-commerce Website

## 1. Project Information

- **Project Name:** E-commerce Website Manual Testing
- **Application:** https://www.saucedemo.com/
- **Testing Type:** Manual Functional Testing
- **Environment:** Windows 11, Google Chrome
- **Execution Status:** In Progress

## 2. Test Execution Summary

 Test Case ID     |      Test Scenario                      |       Expected Result                    |              Actual Result                     | Status |
_________________________________________________________________________________________________________________________________________________________________
| TC_LOGIN_001    | Login with valid credentials            | User reaches the products page           | Products page displayed after login             | Pass |
| TC_LOGIN_002    | Login with invalid password             | Login rejected with an error message     | Login rejected and error message displayed      | Pass |
| TC_LOGIN_003    | Login with empty fields                 | Login rejected with a validation message | Login rejected and validation message displayed | Pass |
| TC_CART_001     | Add a product to the cart               | Selected product appears in cart         | Selected product appeared in cart               | Pass |
| TC_CHECKOUT_001 | Checkout with valid customer details    | User reaches the order summary           | The order summary displayed the selected product and correct total. After clicking Finish, the order confirmation page displayed “Thank you for your order!”                               | PASS |

## 3. Execution Metrics

- **Total Test Cases Listed:** 5
- **Passed:** 5
- **Failed:** 0
- **Not Executed:** 0
- **Blocked:** 0

## 4. Observations

- Login with valid credentials was successful.
- Invalid-password login was rejected with an error message.
- Login with empty fields was rejected with a validation message.
- The selected product appeared in the shopping cart.
- Checkout testing is pending.

## 5. Conclusion

Testing is in progress. Four test cases have passed based on the recorded observations. Checkout testing remains pending. No confirmed defects have been recorded so far.
