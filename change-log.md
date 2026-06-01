# Change Log — ShopWave AI Chatbot Project
---

## Change Request Form Fields

Each change request is recorded using the following standard fields:

| Field | Description |
|-------|-------------|
| Change Request ID | Unique reference number (e.g. CR-001) |
| Date Raised | Date the change request was submitted |
| Requested By | Name of the person requesting the change |
| Description of Change | Clear explanation of what is being requested |
| Reason / Justification | Why the change is needed |
| Impact Assessment | Effect on scope, time, cost, quality and risk |
| Priority | Low / Medium / High / Urgent |
| CCB Decision | Approved / Rejected / Deferred, with reason and date |

---

## Change Request Log

---

### CR-001

| Field | Details |
|-------|---------|
| **Change Request ID** | CR-001 |
| **Date Raised** | Week 3 — during Requirements Gathering |
| **Requested By** | ShopWave Client Representative |
| **Description of Change** | Add SMS as a second messaging channel in addition to the website chatbot |
| **Reason / Justification** | Many ShopWave customers contact support via SMS; adding this channel would increase chatbot reach |
| **Impact Assessment** | Scope: increases integration work; Time: +1 week estimated; Cost: minor API cost increase; Risk: adds complexity to Channel & API Integration (CHAT-9) |
| **Priority** | Medium |
| **CCB Decision** | ✅ **Approved** — Decision Date: Week 4. SMS channel added to scope. Schedule adjusted to accommodate extra integration work. |

---

### CR-002

| Field | Details |
|-------|---------|
| **Change Request ID** | CR-002 |
| **Date Raised** | Week 5 — during Support Data Analysis |
| **Requested By** | Suraj |
| **Description of Change** | Include French language support in the initial chatbot release |
| **Reason / Justification** | A small percentage of ShopWave customers have French as their primary language |
| **Impact Assessment** | Scope: significantly expands NLP training requirements; Time: +3 weeks estimated; Cost: high increase in model training costs; Risk: high — could delay go-live |
| **Priority** | Low |
| **CCB Decision** | ❌ **Rejected** — Decision Date: Week 5. French language support is listed as Out of Scope in the approved scope statement. May be considered for a future release. |

---

### CR-003

| Field | Details |
|-------|---------|
| **Change Request ID** | CR-003 |
| **Date Raised** | Week 7 — during Conversation Flow & UX Design |
| **Requested By** | ShopWave Client Representative |
| **Description of Change** | Add a product recommendation feature to the chatbot so it can suggest items to customers |
| **Reason / Justification** | Client believes this would improve upselling opportunities during customer interactions |
| **Impact Assessment** | Scope: major addition beyond agreed scope; Time: +4 weeks estimated; Cost: significant increase; Risk: high — scope creep risk (R3 in risk register) |
| **Priority** | High |
| **CCB Decision** | ⏸️ **Deferred** — Decision Date: Week 7. Change deferred to Phase 2 of the project. Current scope and timeline must be protected. Client notified and agreement documented. |

---

### CR-004

| Field | Details |
|-------|---------|
| **Change Request ID** | CR-004 |
| **Date Raised** | Week 9 — during NLP Model Development |
| **Requested By** | Abishek |
| **Description of Change** | Switch NLP platform from custom-built model to Google Dialogflow to reduce development time |
| **Reason / Justification** | Custom NLP model development is taking longer than estimated due to data quality issues (linked to Risk R1). Using Dialogflow would speed up delivery. |
| **Impact Assessment** | Scope: no change to features; Time: saves approximately 1 week; Cost: ongoing API usage cost for Dialogflow; Quality: Dialogflow is a proven enterprise platform — reduces risk of inaccuracy |
| **Priority** | High |
| **CCB Decision** | ✅ **Approved** — Decision Date: Week 9. Switch to Google Dialogflow approved. Budget updated to include API costs. Risk R1 status updated to mitigated. |

---

### CR-005

| Field | Details |
|-------|---------|
| **Change Request ID** | CR-005 |
| **Date Raised** | Week 13 — during Integration & System Testing |
| **Requested By** | Salin Chhunju |
| **Description of Change** | Extend the system testing phase by one additional week due to unresolved integration defects |
| **Reason / Justification** | Several API authentication failures were found during testing (Issue I2 in issues register). An extra week is needed to resolve and retest before UAT begins. |
| **Impact Assessment** | Scope: no change; Time: +1 week — pushes UAT and go-live back by one week; Cost: minor team time cost; Risk: low — better to resolve defects now than during UAT |
| **Priority** | Urgent |
| **CCB Decision** | ✅ **Approved** — Decision Date: Week 13. Testing extended by one week. UAT moved to Week 16. Deployment moved to Week 17. Client informed and schedule baseline updated. |

---

## Change Request Summary

| CR ID | Requested By | Description | Priority | Decision | Date Decided |
|-------|-------------|-------------|----------|----------|-------------|
| CR-001 | ShopWave Client | Add SMS messaging channel | Medium | ✅ Approved | Week 4 |
| CR-002 | Suraj | Add French language support | Low | ❌ Rejected | Week 5 |
| CR-003 | ShopWave Client | Add product recommendation feature | High | ⏸️ Deferred | Week 7 |
| CR-004 | Abishek | Switch to Google Dialogflow | High | ✅ Approved | Week 9 |
| CR-005 | Salin Chhunju | Extend testing phase by 1 week | Urgent | ✅ Approved | Week 13 |

---

## Change Management Process Reference

This change log follows the 7-step Change Request Management Process defined in the project plan:

1. **Change Request Submitted** — Stakeholder submits request using standard form
2. **Request Logged** — Recorded in this change log with unique CR-ID
3. **Impact Assessment** — Team analyses impact on scope, schedule, cost, quality and risk
4. **CCB Review** — Change Control Board reviews the assessment
5. **Approve / Reject / Defer** — CCB makes decision with reason and date
6. **Implementation** — Approved changes implemented and communicated
7. **Verification and Closure** — Change verified and log updated

*Last updated: May 2026 — Suraj (Student ID: 68767)*
