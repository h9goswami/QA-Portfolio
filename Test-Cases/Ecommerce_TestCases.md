# E-commerce Application – Test Cases

##  Module: Login

###  TC_01: Valid Login
- **Precondition:** User is registered
- **Steps:**
  1. Enter valid email
  2. Enter valid password
  3. Click Login
- **Test Data:** test@gmail.com / Password123
- **Expected Result:** User should be redirected to dashboard
- **Actual Result:** To be executed
- **Status:** Not Executed

---

###  TC_02: Invalid Password
- **Precondition:** User is registered
- **Steps:**
  1. Enter valid email
  2. Enter incorrect password
  3. Click Login
- **Expected Result:** Error message should be displayed
- **Actual Result:** To be executed
- **Status:** Not Executed

---

###  TC_03: Empty Fields
- **Steps:**
  1. Click Login without entering credentials
- **Expected Result:** Validation message should appear
- **Actual Result:** To be executed
- **Status:** Not Executed

---

##  Module: Cart

###  TC_04: Add Product to Cart
- **Steps:**
  1. Select a product
  2. Click "Add to Cart"
- **Expected Result:** Product should be added to cart
- **Actual Result:** To be executed
- **Status:** Not Executed

---

###  TC_05: Remove Product from Cart
- **Steps:**
  1. Go to cart
  2. Remove product
- **Expected Result:** Product should be removed successfully
- **Actual Result:** To be executed
- **Status:** Not Executed
