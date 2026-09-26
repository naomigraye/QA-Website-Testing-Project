# Bug Reports

## BUG-001 — Incorrect Product Images Displayed

**Severity:** Medium  
**Status:** Open

### Steps to Reproduce
1. Navigate to SauceDemo.
2. Log in using the `problem_user` account.
3. View the Products page.
4. Review the images displayed for the different products.

### Expected Result
Each product should display an image that corresponds with its product name and description.

### Actual Result
Multiple products display the same dog image even though the product names and descriptions represent different items.

---

## BUG-002 — Incorrect Product Detail Page Opens

**Severity:** High  
**Status:** Open

### Steps to Reproduce
1. Log in using the `problem_user` account.
2. Navigate to the Products page.
3. Select the Sauce Labs Backpack product name.

### Expected Result
The Sauce Labs Backpack product-detail page should open.

### Actual Result
The Sauce Labs Fleece Jacket product page opens instead.

---

## BUG-003 — Product Sorting Does Not Work Correctly

**Severity:** Medium  
**Status:** Open

### Steps to Reproduce
1. Log in using the `problem_user` account.
2. Navigate to the Products page.
3. Open the product sorting menu.
4. Select a sorting option such as Name (Z to A) or Price (low to high).
5. Close the sorting menu.

### Expected Result
The selected sorting option should remain active and the products should reorder according to the selected option.

### Actual Result
The sorting selection reverts to Name (A to Z), and the products do not reorder as selected.

---

## BUG-004 — About Menu Link Leads to 404 Page

**Severity:** Medium  
**Status:** Open

### Steps to Reproduce
1. Open the SauceDemo navigation menu.
2. Select About.

### Expected Result
The About link should navigate to a valid Sauce Labs page.

### Actual Result
The link opens a page displaying “404 - Page Not Found.”
