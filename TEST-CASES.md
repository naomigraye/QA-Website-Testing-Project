# Manual QA Test Cases

## TC-001 — Valid User Login

**Steps**
1. Navigate to SauceDemo.
2. Enter valid standard user credentials.
3. Click Login.

**Expected Result:** User successfully logs in and reaches the Products page.

**Actual Result:** Products page displayed successfully.

**Status:** PASS

---

## TC-002 — Add Product to Cart

**Steps**
1. Select Add to cart for Sauce Labs Backpack.
2. Verify the cart quantity.
3. Open the cart.

**Expected Result:** Cart displays a quantity of 1 and contains Sauce Labs Backpack for $29.99.

**Actual Result:** Correct product was added and cart quantity updated to 1.

**Status:** PASS

---

## TC-003 — Remove Product From Cart

**Steps**
1. Open the shopping cart.
2. Remove Sauce Labs Backpack.

**Expected Result:** Product disappears and cart quantity returns to zero.

**Actual Result:** Product and cart quantity indicator were removed.

**Status:** PASS

---

## TC-004 — Checkout With Required Fields Blank

**Steps**
1. Begin checkout.
2. Leave all customer information fields blank.
3. Click Continue.

**Expected Result:** Checkout is blocked and a required-field error appears.

**Actual Result:** "Error: First Name is required" displayed.

**Status:** PASS

---

## TC-005 — Checkout With Missing Last Name

**Expected Result:** Checkout is blocked when Last Name is blank.

**Actual Result:** "Error: Last Name is required" displayed.

**Status:** PASS

---

## TC-006 — Checkout With Missing ZIP/Postal Code

**Expected Result:** Checkout is blocked when ZIP/postal code is blank.

**Actual Result:** ZIP/postal code required error displayed.

**Status:** PASS

---

## TC-007 — Complete Checkout

**Steps**
1. Enter valid checkout information.
2. Continue to Checkout Overview.
3. Verify Sauce Labs Backpack is listed for $29.99.
4. Complete the order.

**Expected Result:** Correct product information appears and the order completes successfully.

**Actual Result:** Order completed and "Thank you for your order!" displayed.

**Status:** PASS

---

## TC-008 — Verify Product Images

**Account:** problem_user

**Expected Result:** Product images correspond with their product names and descriptions.

**Actual Result:** Multiple products displayed the same dog image.

**Status:** FAIL

**Related Bug:** BUG-001

---

## TC-009 — Add Backpack to Cart as Problem User

**Expected Result:** Sauce Labs Backpack is added to the cart.

**Actual Result:** Sauce Labs Backpack was correctly added.

**Status:** PASS

---

## TC-010 — Product Detail Navigation

**Account:** problem_user

**Expected Result:** Selecting Sauce Labs Backpack opens its corresponding product-detail page.

**Actual Result:** Sauce Labs Fleece Jacket product page opened instead.

**Status:** FAIL

**Related Bug:** BUG-002

---

## TC-011 — Product Sorting

**Account:** problem_user

**Expected Result:** Selecting a sorting option changes the product order and the selected option remains active.

**Actual Result:** Sorting reverted to Name (A to Z), and products did not reorder as selected.

**Status:** FAIL

**Related Bug:** BUG-003

---

## TC-012 — About Menu Navigation

**Expected Result:** About opens a valid Sauce Labs page.

**Actual Result:** A "404 - Page Not Found" page displayed.

**Status:** FAIL

**Related Bug:** BUG-004
