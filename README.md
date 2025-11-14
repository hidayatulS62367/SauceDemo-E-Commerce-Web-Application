# SauceDemo-E-Commerce-Web-Application
SauceDemo is a sample e-commerce web application designed for testing, featuring login, product selection, cart, and checkout functions ideal for practicing manual and automated functional testing using Selenium or other tools.The focus is on ensuring accuracy,reliability, and consistency of the cart and checkout operations.

------------------------------------------------------------------------

## Project Overview

The purpose of this automation project is to:

-   Validate shopping cart operations\
-   Verify product price accuracy\
-   Ensure consistent sales transaction calculations\
-   Detect system discrepancies using automated test scripts

------------------------------------------------------------------------

## Tools & Technologies

  -----------------------------------------------------------------------
  Tool / Tech                         Description
  ----------------------------------- -----------------------------------
  **Java**                            Programming language used for
                                      writing test scripts

  **JUnit**                           Framework for structuring and
                                      running test cases

  **Selenium WebDriver**              Automates browser interactions and
                                      UI testing

  **Maven**                           Dependency and project management

  **ChromeDriver**                    Browser driver for executing
                                      automation tests
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Key Features Tested

### 1. **Cart Operations**

-   Adding items to cart\
-   Removing items from cart\
-   Updating product quantity\
-   Verifying cart badge count

### 2. **Price & Total Verification**

-   Validating item unit prices\
-   Checking subtotal and total calculations\
-   Ensuring tax and discount values are correct

### 3. **Checkout Flow**

-   Login validation\
-   Entering customer information\
-   Completing a purchase\
-   Verifying success page

### 4. **Data Validation**

-   Comparing displayed totals vs. calculated totals\
-   Spot-checking backend-calculation consistency

------------------------------------------------------------------------

## Test Design Techniques Used

-   **Boundary Value Analysis (BVA)**\
-   **Equivalence Partitioning (EP)**\
-   **UI Functional Testing**\


------------------------------------------------------------------------

## Project Outcomes

-   Successfully automated critical user flows in Sauce Demo.\
-   Improved test efficiency and reduced manual testing time.\
-   Identified a **2% miscalculation in sales totals**, caused by
    rounding issues --- reported and fixed by the development team.\
-   Ensured higher accuracy in cart and checkout calculations.

------------------------------------------------------------------------

## Project Structure

    SauceDemoAutomation/
    │
    ├── src/test/java/
    │   ├── tests/
    │   │   ├── LoginTest.java
    │   │   ├── CartTest.java
    │   │   ├── CheckoutTest.java
    │   │   └── PriceValidationTest.java
    │   │
    │   └── utils/
    │       └── BaseTest.java
    │
    ├── pom.xml
    └── README.md

------------------------------------------------------------------------


## Future Enhancements

-   Integrate Allure or Extent Reports for better test reporting\
-   Add cross-browser testing (Firefox, Edge)\
-   Include data-driven testing with Excel or JSON
