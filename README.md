# Test Automation Project – Online Store

## Test Scope
This project aims to automate the **functional testing** of a shopping website. The automated tests validate core functionalities such as **login, logout, adding products to the cart, removing products, and completing the checkout process**.

## Tools and Technologies
- **Language**: JavaScript  
- **Automation Framework**: Playwright  
- **Version Control**: Git  
- **Development Environment**: IntelliJ IDEA, Node.js  

## Test Cases

### 1. Login Test
- **Description**: Verify that users can log in with valid credentials.
- **Steps**:
  1. Open the login page.
  2. Enter username and password.
  3. Confirm redirection to the homepage.
- **Expected Result**: User is successfully authenticated and redirected to the homepage.

### 2. Add to Cart Test
- **Description**: Ensure that products are correctly added to the shopping cart.
- **Steps**:
  1. Access the website.
  2. Select a product and add it to the cart.
  3. Check that the product appears in the cart.
- **Expected Result**: The selected product is added correctly to the cart.

*Additional test cases (like remove from cart, logout, and checkout) may be added in future updates.*

## How to Run the Tests

1. Clone this repository:
   ```bash
   git clone https://github.com/cejasmd/Proyecto-Aut.softw.git
