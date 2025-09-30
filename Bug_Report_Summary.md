# 🐞 Bug Report Summary

## 🧾 Student Details  
**Name**: Nkosingiphile Maseko  
**Cohort**: July 2025  
**Date**: 30 September 2025

---

## ✅ Expected Behaviors  
List 3 things you expect the To-Do app to do correctly.

1.Tasks should **not** be added if the input field is empty (Input Validation).
2. Tasks should **remain** on the list after the page is reloaded (Data Persistence).
3. Clicking “Complete” should **strike through** the task text but not remove it immediately.



---

## 🐛 Reported Bugs  

### 🐞 BUG-001  
**Title**: Task disappears after refresh  
**GitHub Link**: https://github.com/PLP-Database-Design/wk-1-Prudie90-1/issues/1 
**Requirement Affected**: Input Validation
**Severity**: Medium 
**Summary**:  
[1–2 sentences describing the bug and its impact.]

---

### 🐞 BUG-002  
**Title**: App allows adding empty tasks  
**GitHub Link**: https://github.com/PLP-Database-Design/wk-1-Prudie90-1/issues/2 
**Requirement Affected**: Data Persistence 
**Severity**: Low 
**Summary**:  
[1–2 sentences describing the bug and its impact.]

---

## 💭 Reflection  

My testing approach was based on functional testing and negative testing. I started with the "happy path" by successfully adding, completing, and deleting tasks. I then moved on to testing common failure points: first by checking input validation (submitting an empty field, which revealed BUG-002), and then by checking data persistence (reloading the page after adding content, which revealed the higher-severity BUG-001).


I found it easy to spot the major functional bugs, especially the persistence issue, as it's a critical failure point for any tracking application. The most difficult part was deciding on the appropriate Severity level, as "Task disappears after refresh" (Medium) is a much more critical failure than "App allows adding empty tasks" (Low), even though both are bugs. This required careful thinking about the real-world impact on the user.


I feel confident now in my ability to identify and clearly report bugs. The process of documenting the Steps to Reproduce and clearly stating the difference between the Expected and Actual results is a valuable skill that I feel I've grasped well through this assignment
