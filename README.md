# BugReports

## Menu links lead to wrong pages

**Title:** Menu links lead to wrong pages  
**Description:** In the main menu, the "Contact" link redirects to the "About Us" page instead of the contact form.  

**Steps to Reproduce:**
1. Open the website.  
2. Click on the main menu → "Contact".  
3. Observe the opened page.  

**Actual Result:** The "About Us" page opens.  
**Expected Result:** The contact form should open.  
**Severity:** Major  
**Priority:** High  

---

## Product images do not load

**Title:** Product images do not load  
**Description:** On the product detail page, images appear as "broken image" (404). The issue occurs only in Chrome.  

**Steps to Reproduce:**
1. Open a product page.  
2. Check the image section.  

**Actual Result:** Images appear as "broken image" (404).  
**Expected Result:** Product images should load normally.  
**Severity:** Critical  
**Priority:** High  

---

## Registration form does not validate email

**Title:** Registration form does not validate email  
**Description:** Users can enter email addresses without the "@" symbol and the form still accepts registration.  

**Steps to Reproduce:**
1. Open the registration page.  
2. Enter an invalid email (e.g., "testmail.com").  
3. Click "Register".  

**Actual Result:** The form accepts the invalid email.  
**Expected Result:** The system should display an error message.  
**Severity:** Medium  
**Priority:** Medium  

---

## Checkout page freezes at payment step

**Title:** Checkout page freezes at payment step  
**Description:** After selecting the payment method, the "Place Order" button does not respond and the user is stuck.  

**Steps to Reproduce:**
1. Add a product to the cart.  
2. Go to checkout.  
3. Select a payment method.  
4. Click "Place Order".  

**Actual Result:** The button does not respond, user is stuck.  
**Expected Result:** The order should be completed and confirmed.  
**Severity:** Critical  
**Priority:** Highest  

---

## Footer does not display correctly on mobile

**Title:** Footer does not display correctly on mobile  
**Description:** On mobile devices, the footer overlaps the main content and buttons cannot be accessed.  

**Steps to Reproduce:**
1. Open the website on a mobile phone.  
2. Scroll down to the footer.  

**Actual Result:** The footer overlaps the content and buttons are inaccessible.  
**Expected Result:** The footer should be visible and functional.  
**Severity:** Minor  
**Priority:** Low  
