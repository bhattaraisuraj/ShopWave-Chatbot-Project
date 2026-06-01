## 2.4 Risk and Issues Management Strategy

It is important to separate risks from issues. A risk is an uncertain event that may affect the project objectives if it occurs. An issue is a problem that has already occurred and requires immediate action. Effective risk management involves identifying, analysing, responding to, and continuously monitoring risks throughout the project lifecycle [8], [9].

### 2.4.1 Risk Management Approach

Each risk is assessed based on its probability and impact. These values are combined to determine an overall risk score. Risks with higher scores require greater attention and more detailed mitigation strategies. Common risk response strategies include avoidance, mitigation, transfer, and acceptance [8].

| ID | Risk Description | Probability | Impact | Risk Score | Response / Mitigation |
|----|-----------------|-------------|--------|------------|----------------------|
| R1 | Poor quality or insufficient training data, leading to inaccurate chatbot answers | Medium | High | 7 | Validate and clean support data early, involve support staff in reviewing intents, and retrain the model iteratively. |
| R2 | Integration problems with the existing website or CRM | Medium | High | 6 | Run a technical feasibility check during design and test integration in a staging environment before deployment. |
| R3 | Scope creep from stakeholders requesting additional features | High | Medium | 6 | Apply the change request process (Section 2.5) and maintain the agreed scope statement as the project baseline. |
| R4 | Key team member becomes unavailable | Low | Medium | 4 | Cross-train team members and document work in shared tools such as Jira and GitHub. |
| R5 | Customer data handled in breach of privacy requirements | Low | High | 6 | Apply privacy-by-design principles, minimise collection of sensitive information, and ensure compliance with the Australian Privacy Principles (APPs) [7]. |
| R6 | Low user adoption because customers prefer human agents | Medium | Medium | 4 | Provide smooth escalation to live agents, conduct pilot testing, and collect user feedback before full deployment. |

### 2.4.2 Issues Management

The occurrence of a risk, or any unexpected problem, is recorded as an issue in the issue log. Each issue is assigned an owner, priority level, and target resolution date. Issues are monitored until closure, and major issues that may affect project scope, schedule, cost, or quality are escalated to project stakeholders for review [9].

### 2.4.3 Issues Register

During project execution, issues may arise that require immediate attention. Unlike risks, issues have already occurred and must be actively managed to minimise project disruption.

| Issue ID | Issue Description | Priority | Owner | Status |
|-----------|------------------|----------|--------|---------|
| I1 | Delay in receiving customer support data | High | Project Manager | Open |
| I2 | API authentication failure during testing | Medium | Developer | Closed |
| I3 | Stakeholder unavailable for workshop | Medium | Business Analyst | In Progress |
| I4 | Delayed approval of chatbot design | Medium | Client Representative | Open |

Issues will be reviewed weekly and escalated to project sponsors if they significantly impact project scope, schedule, cost, or quality.
