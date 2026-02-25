# Contact Form Automation System (n8n)

A production-style workflow built with n8n to automate inquiry handling, data tracking, and instant response management.

---

##  Problem Statement

Many small businesses and course creators manually track inquiries and respond late, leading to:
- Missed leads
- Slow response time
- Disorganized data

This workflow eliminates manual handling and ensures every inquiry is logged and acknowledged instantly.

---

##  System Architecture

**Trigger → Data Storage → Automated Response**

1. **Form Submission (Trigger)**
   - Captures user input (Name, Email, Description, Course Type)

2. **Google Sheets Integration**
   - Automatically appends submission as structured data
   - Enables tracking and reporting

3. **Gmail Automation**
   - Sends immediate confirmation email
   - Improves user experience and response speed

---

##  Tech Stack

- n8n (Workflow Automation)
- Google Sheets API
- Gmail API

---

##  Key Features

- Automated data capture
- Structured lead storage
- Instant email confirmation
- No manual intervention required

---

## Business Impact

- Reduces manual data entry
- Prevents lost inquiries
- Improves response time to seconds
- Creates scalable inquiry management system

---

## How to Run

1. Import `workflow/contact-form.json` into n8n.
2. Configure Google Sheets OAuth credentials.
3. Configure Gmail OAuth credentials.
4. Update email recipient field to use submitted email dynamically.
5. Activate workflow.
---
## Future Improvements

- Conditional routing based on course type
- Slack/CRM notification integration
- Lead scoring logic
- AI-based inquiry classification
















