# Saucedemo Test Automation

This project automates the end-to-end scenario on the website "www.saucedemo.com" using Katalon Studio. The test suite will be run with two different profiles (default and custom) to verify functionality.

## Prerequisites

- Katalon Studio installed on your machine
- Basic understanding of Katalon Studio and web automation
- Access to the "www.saucedemo.com" website

## Test Suite Structure

### Test Suite

- **Test Suite Name:** `DemoTestSuite`

### Profiles

- **default:** 
- **custom:** 

### Global Variables

- **Price:** Used to store and verify the price of the selected product.

## Test Steps

1. **Open Browser**
   - Start the browser session.

2. **Navigate to "www.saucedemo.com"**
   - Navigate to the Saucedemo website.

3. **Verify on Login Page**
   - Ensure that the login page is displayed correctly.

4. **Enter Username**
   - Use a global variable for the username. The username will differ based on the selected profile.

5. **Enter Password**
  

6. **Click Login Button**
   - Click the login button to proceed to the products page.

7. **Verify on Products Page**
   - Ensure that the products page is displayed correctly.

8. **Select Price as Low to High**
   - Sort the products by price from low to high.

9. **Add "Sauce Labs Onesie" to Your Cart**
   - Add the "Sauce Labs Onesie" item to the cart.

10. **Go to Your Cart**
    - Navigate to the cart page.

11. **Click Checkout**
    - Click on the checkout button.

12. **Enter First Name**
    - Enter the first name in the checkout form.

13. **Enter Last Name**
    - Enter the last name in the checkout form.

14. **Enter Zip/Postal Code**
    - Enter the Zip/Postal Code in the checkout form.

15. **Click Continue**
    - Proceed to the next step by clicking the continue button.

16. **Verify on Checkout Screen**
    - Ensure that the checkout overview page is displayed correctly.

17. **Verify the Price**
    - Verify that the price matches the expected value stored in the `Price` variable.

18. **Click Finish**
    - Complete the purchase by clicking the finish button.

19. **Verify the "Thank you for your order!" Text**
    - Confirm that the order completion message is displayed.

20. **Click Back Home**
    - Return to the home page.

21. **Click Menu (Top Left Corner)**
    - Open the side menu by clicking the menu button.

22. **Log Out of the Account**
    - Log out of the current session.

23. **Verify on Login Page**
    - Ensure that the login page is displayed after logging out.

24. **Close Browser**
    - Close the browser session.

## Test Collection

- **Test Collection Name:** `DemoCollection`
- Add the `DemoTestSuite` twice:
  - First instance: Run with the `default` profile.
  - Second instance: Run with the `custom` profile.




