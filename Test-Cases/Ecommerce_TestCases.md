# Test Cases


This file contains detailed test cases for multiple enterprise modules and workflows tested using Neome. It covers mobile, web, and admin panel functionalities.

---

### Test Case: Login Functionality
**ID:** TC_001  
**Module:** Authentication  
**Precondition:** User is registered  
**Steps:**
1. Open the application (mobile/web).  
2. Enter valid username and password.  
3. Click Login button.  
**Expected Result:** User should successfully log in.  
**Actual Result:** Login successful as expected.   
**Status:** Pass  
**Priority:** High  

---

### Test Case: Responsive UI
**ID:** TC_002  
**Module:** UI/UX  
**Precondition:** Application is installed or web page is open  
**Steps:**
1. Open the app/website on mobile, tablet, and desktop.  
2. Verify layout alignment, element visibility, and scrolling behavior.  
**Expected Result:** UI should adapt correctly across devices, no overlaps, text readable.
**Actual Result:** UI adapted correctly across devices
**Status:** Pass 
**Priority:** Medium  

---

### Test Case: Dark / Light Mode
**ID:** TC_003  
**Module:** UI/UX  
**Precondition:** Mobile device supports dark/light mode  
**Steps:**
1. Enable device dark mode and open the app.  
2. Check text visibility, backgrounds, icons, and element contrast.  
**Expected Result:** All UI elements remain readable and functional.  
**Status:** Pass 
**Priority:** Medium  

---

### Test Case: Push Notifications
**ID:** TC_004  
**Module:** Notifications  
**Precondition:** App installed on mobile device  
**Steps:**
1. Trigger notification from the app.  
2. Observe notification in foreground, background, and closed states.  
3. Click notification to verify redirection.  
**Expected Result:** Notifications received properly and redirect to the correct screen.
**Actual Result:** Notification received and redirected correctly.
**Status:** Pass 
**Priority:** High  

---

### Test Case: Deep Link / Dynamic Link
**ID:** TC_005  
**Module:** Navigation  
**Precondition:** App installed  
**Steps:**
1. Open app via deep/dynamic link.  
2. Verify the correct module/page opens.  
**Expected Result:** App opens the target module correctly.
**Actual Result:** App opened the target module correctly.
**Status:** Pass  
**Priority:** Medium  

---

### Test Case: Chat Functionality
**ID:** TC_006  
**Module:** Messaging  
**Precondition:** User logged in  
**Steps:**
1. Send message to another user.  
2. Verify delivery and display order.  
**Expected Result:** Messages sent and received correctly with correct order.
**Actual Result:** Messages sent and received successfully with correct order.  
**Status:** Pass 
**Priority:** High  

---

### Test Case: Admin Panel
**ID:** TC_007  
**Module:** Admin  
**Precondition:** Admin login credentials available  
**Steps:**
1. Log in to admin panel.  
2. Create, update, and delete records.  
3. Verify changes on user side.  
**Expected Result:** Admin changes reflect correctly; workflows remain functional.
**Actual Result:** Admin changes reflected correctly; workflows remain functional. 
**Status:** Pass  
**Priority:** High  

---

### Test Case: Reminder / Date Logic
**ID:** TC_008  
**Module:** Reminders  
**Precondition:** Reminder feature enabled  
**Steps:**
1. Set reminders in different timezones (e.g., Bangkok).  
2. Verify correct filtering and notification.  
**Expected Result:** Reminders appear correctly according to timezone.
**Actual Result:** Reminders appeared correctly according to timezone.  
**Status:** Pass  
**Priority:** Medium  

---

### Test Case: Order Work Flow
**ID:** TC_009  
**Module:** Order  
**Precondition:** Items are available for ordering.
**Steps:**
1. Select the desired items.  
2. Add basic details(Name, Number, Address). 
3. Click on send
4. Verify that the Order is created.
**Expected Result:** The user should be able to place an order successfully, and the order should be associated with that user.
**Actual Result:** The user placed the order successfully, and it was created correctly.
**Status:** Pass  
**Priority:** High  

---

### Test Case: Basic Payment Flow
**ID:** TC_010 
**Module:** Payment  
**Precondition:** Payment method available (Razorpay)  
**Steps:**
1. Navigate to payment page.  
2. Enter valid payment details and submit.  
**Expected Result:** Payment redirects correctly; calculation reflected.
**Actual Result:** Payment redirected correctly; calculation reflected.  
**Status:** Pass  
**Priority:** Medium


**Note:** Basic payment testing done; advanced scenarios can be added.  
