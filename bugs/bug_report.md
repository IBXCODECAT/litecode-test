**Bug Report**

**Platform:** LiteCode  
**Version:** [Specify Version if known]  
**Date:** October 26, 2leshoot  

---

### **Issue Summary**
Users cannot directly enable Design Mode for individual modules. The toggle button within a 
module's foldout block is initially disabled and unresponsive. To enter Design Mode, users must 
first navigate to the "Manage" section, select "Follow Me," generate a QR code, and then attempt 
to access design mode via an indirect method.

---

### **Steps to Reproduce**
1. Log in to LiteCode.
2. Navigate to any module (e.g., from GitHub custom modules or example modules).
3. Fold out the selected module block by clicking on its header or expansion icon.
4. Attempt to enable Design Mode by toggling the "Design Mode" switch within the foldout 
interface.

**Expected Result:**  
The toggle should activate, allowing users to enter Design Mode directly for the module.

**Actual Behavior:**  
- The "Design Mode" toggle is disabled (grayed out or visually unclickable).
- It remains in an off state.
- Users cannot proceed through this method.

---

### **Suggested Solution**
1. **Direct Toggle for Each Module:**  
   Enable the "Design Mode" toggle directly within each foldout block to provide immediate user 
control.
   
2. **Clarify Activation Workflow (if QR code method remains):**  
   If Design Mode requires an additional step, ensure users are clearly informed of this 
requirement and avoid confusing them with unrelated processes like QR code generation.

---

### **Priority**
**Medium Priority** – This issue impacts core functionality, such as module customization and 
debugging. Users may become frustrated if they cannot directly enable Design Mode, however there is an
alternative method to acheiving this functionality documented above.

### **Affected Components**
- Module foldout interfaces.
- "Design Mode" toggle button within modules.
- Potential ties to server-side rendering logic or account management features ("Follow Me").

---

### **Recommendations**
1. Add explicit instructions in the LiteCode documentation for users encountering this issue.
2. Conduct a review of the Design Mode activation process to ensure it aligns with user 
expectations.
3. Evaluate whether QR code generation is part of the standard design mode workflow or an 
unrelated feature.
