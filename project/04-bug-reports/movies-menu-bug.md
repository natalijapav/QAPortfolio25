# Bug Report – Unable to Access "Movies" Section via Menu

---

## 🐞 Description

When accessing the "Movies" section through the app’s menu, an error occurs and the user is redirected to a support page.  
The issue does **not** occur when accessing the same section via the search box.

---

## 🔍 Background

- Reported by multiple users
- Discovered during general browsing
- Reproducible on specific devices only

---

## 📋 Bug Details

- **Workaround:** Accessible via search box, but **not** via menu
- **Environment:** Production
- **Device:** Hisense TV
- **OS:** Android
- **Not Affected:** Browser, Mobile App

---

## ✅ Steps to Reproduce

1. Open the application  
2. Log in to a user profile  
3. Navigate to Home page  
4. Open the side menu  
5. Click on the “Movies” button  
6. Observe the error message

---

## ✅ Expected Result

- User is redirected to the “Movies” section of the app

## ❌ Actual Result

- Error appears and user is redirected to a customer support page

---

## ✅ Acceptance Criteria

- Movies section can be accessed via menu without error  
- Fix works consistently across all supported devices and OS (iOS/Android)  
- Issue is resolved on latest and previous app versions  
- Error page no longer appears when using the menu  
- Search functionality for Movies continues to work correctly  
- UAT confirms issue is resolved  
- E2E test ticket created and passed

---

## 🧪 Testing

- **Environment:** Staging (before release)
- **Coverage:** iOS & Android on phones, tablets, TVs

### ✔️ What Will Be Tested:

**Access Through Menu:**
- Confirm no errors when using menu to access Movies  
- Verify redirection works correctly on all platforms

**Search Functionality:**
- Confirm search returns correct movie content

**Regression Testing:**
- Ensure no other navigation paths are broken  
- Validate overall menu functionality remains intact

---

## ⚠️ Risks

- UI/UX may be affected if navigation structure changes  
- Backend/API dependencies may delay fix  
- Coordination with UI/Design team may be needed if layout is involved

---

## 🎯 Severity & Priority

- **Severity:** High – blocks access to a key feature  
- **Priority:** High – impacts major functionality

---

## 🔗 Related Tickets

> (Add links if applicable – e.g. JIRA, Trello, GitHub Issues)

