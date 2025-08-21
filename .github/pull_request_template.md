---
name: "Change Request"
description: "SOC2-compliant change request template"
title: "[Change Request] <Short Description>"
labels: ["change-request", "pending-approval"]
assignees:
  - team-lead
---

# Change Summary
- **Description:** <!-- What is being changed? -->
- **Reason:** <!-- Why is this change needed? -->
- **Related Issues:** Closes #<issue_number>

---

# Change Type
- [ ] Standard (planned, tested)  
- [ ] Emergency (urgent, expedited)  

---

# Risk & Impact
- [ ] Reviewed for security impact  
- [ ] Reviewed for user/ops impact  
- [ ] No material impact identified  

Notes: <!-- Short explanation of any impact -->

---

# Rollout & Validation
- [ ] Rollout plan documented  
- [ ] Rollback plan documented  
- [ ] Tested in **staging/dev** with evidence (screenshots/logs/links)  

---

# Approvals
- [ ] Requester (engineer opening PR)  
- [ ] Team Lead  
- [ ] Security/CTO (if required)  

---

# Implementation Details
- **Planned Deployment Date:** YYYY-MM-DD  
- **Approach:** <!-- Link to Google Doc for rollout plan -->

---

# Additional Notes
<!-- Any context for reviewers (links, diagrams, monitoring dashboards) -->
