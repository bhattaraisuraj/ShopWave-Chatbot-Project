# 2. Task 1: Project Plan

## 2.1 Project Scope Statement

A well-defined scope statement is important because it states what the project will and will not deliver and provides the baseline on which progress and success are measured. A well-defined scope minimizes uncertainty, facilitates stakeholder agreement and helps to avoid uncontrolled growth of work, commonly called scope creep [6].

The scope statement for this project is provided below.

---

## 2.1.1 Project Justification and Objectives

ShopWave today is managed on a ticketing system via e-mail, with a small group of human agents. Recent support data analysis shows a significant proportion of queries are repetitive and could be automated.

The project is therefore justified on the grounds that an AI chatbot will reduce workload, improve response times and deliver a more consistent customer experience.

### Objectives

- Deploy an AI chatbot capable of resolving at least 80% of routine enquiries without human intervention.
- Provide 24/7 availability across the company website and one major messaging channel.
- Reduce the average first-response time for routine enquiries from several hours to under one minute.
- Deliver the solution within the approved budget and a timeframe of approximately 17 weeks.

---

## 2.1.2 In Scope and Out of Scope

| In Scope | Out of Scope |
|-----------|-------------|
| Requirements gathering and analysis of historical support tickets | Replacement of the existing CRM or ticketing platform |
| Conversation flow design and chatbot user experience | Voice-based or telephone (IVR) assistants |
| Development and training of the NLP/intent model on company data | Support for languages other than English in the initial release |
| Integration with the website, one messaging channel and human-agent handover | Integration with third-party marketplaces (e.g., eBay, Amazon) |
| Testing, pilot, go-live and staff training | Long-term maintenance beyond the agreed warranty period |

---

## 2.1.3 Major Deliverables

- Approved project plan and scope statement.
- Requirements specification based on analysis of real support enquiries.
- Conversation flow designs and a system architecture/integration design.
- Trained AI chatbot integrated with the website and messaging channel.
- System and user acceptance test reports, plus user/training documentation.
- Deployed live chatbot and a final project review and handover report.

---

## 2.1.4 Assumptions, Constraints and Acceptance Criteria

### Assumptions

The project assumes that historical customer support records will be made available by ShopWave Pty Ltd for the purpose of chatbot training and testing.

It is also assumed that key stakeholders will be available to participate in requirements gathering, reviews, and acceptance testing throughout the project life cycle.

The project team assumes that appropriate cloud infrastructure and AI services will be available with no significant service disruption.

### Constraints

- Fixed project duration of 17 weeks.
- Fixed project budget.
- Compliance with the Australian Privacy Principles (APPs) relating to customer information and data handling.
- The chatbot must integrate into the current customer support environment without requiring significant operational changes.

### Acceptance Criteria

The project will be considered successful when:

- The chatbot resolves at least 80% of routine customer enquiries automatically.
- Average response time is below 60 seconds.
- Customer satisfaction rating exceeds 85% during pilot testing.
- System availability remains above 99%.
- Human handover functionality operates correctly for unsupported requests.
- No critical defects remain unresolved during final acceptance testing.
- Formal client sign-off is received following deployment.

---

# 2.2 Project Activities and Interdependencies

Before a Gantt chart can be produced, the work is broken down into activities with estimated durations and predecessors. Predecessors define which tasks must finish before another can begin, and these finish-to-start relationships create the interdependencies in the schedule [3].

The activities for this project are listed below.

| ID | Activity | Schedule | Duration | Predecessor(s) |
|----|----------|----------|----------|---------------|
| 1 | Project charter & kick-off | Week 1 | 1 week | - |
| 2 | Stakeholder identification & registration | Week 2 | 1 week | 1 |
| 3 | Requirements gathering | Weeks 3–4 | 2 weeks | 2 |
| 4 | Support data analysis & intent definition | Weeks 5–6 | 2 weeks | 3 |
| 5 | Conversation flow & UX design | Weeks 7–8 | 2 weeks | 4 |
| 6 | System architecture & integration design | Weeks 7–8 | 2 weeks | 4 |
| 7 | NLP / intent model development & training | Weeks 9–11 | 3 weeks | 5, 6 |
| 8 | Chatbot backend development | Weeks 9–11 | 3 weeks | 6 |
| 9 | Channel & API integration | Week 12 | 1 week | 8 |
| 10 | Integration & system testing | Weeks 13–14 | 2 weeks | 7, 9 |
| 11 | User Acceptance Testing (UAT) | Week 15 | 1 week | 10 |
| 12 | Deployment & Go-Live | Week 16 | 1 week | 11 |
| 13 | Project review & handover | Week 17 | 1 week | 12 |

### Interdependencies

The dependencies show the logical flow of the project from one stage to the next.

- Activity 4 (Support Data Analysis) cannot begin until Requirements Gathering (Activity 3) has been completed.
- Activities 5 (Conversation Flow & UX Design) and 6 (System Architecture & Integration Design) depend on Activity 4 and can run in parallel.
- Activities 7 (NLP Model Development & Training) and 8 (Chatbot Backend Development) also run in parallel to shorten the project schedule.
- Activity 9 (Channel & API Integration) depends on completion of Activity 8.
- Activity 10 (Integration & System Testing) can only begin when both the trained model (Activity 7) and the integrated system (Activity 9) are complete.
- User Acceptance Testing, Deployment, and Project Handover occur sequentially as the final project phases.

These interdependencies are represented in the project Gantt chart and ensure a structured and efficient progression from planning through to deployment and handover.
