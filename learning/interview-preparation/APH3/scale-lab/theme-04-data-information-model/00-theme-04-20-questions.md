# APH3 — Theme 04: Data & Information Model
## 20 Scenario-Based Interview Questions & STAR Answers

**Stream:** APH3 — Applied SAP SuccessFactors Performance & Goals  
**Theme:** 04 — Data & Information Model  
**Answer method:** STAR — Situation → Task → Action → Result  
**Stable IDs:** HR-APH3-B04-Q01 → HR-APH3-B04-Q20

---

### HR-APH3-B04-Q01 — Performance Information Model

**Interview Question:** How would you define the information model for an enterprise performance-management solution?

### STAR Answer
**Situation:** A global organization had goals, ratings, feedback and review information spread across spreadsheets and disconnected HR systems.

**Task:** I needed to define a coherent information model before solution design.

**Action:** I identified strategy-aligned goals, competencies, expectations, performance evidence, feedback, review outcomes, ratings, calibration decisions, development signals, employees, managers, organizational context and effective dates as core information domains.

**Result:** The organization gained a common model for performance information and clearer ownership of each data element.

**SAP SuccessFactors Performance & Goals Example:** Goal Management, Performance Management and Continuous Performance capabilities can manage distinct but related performance information within the broader HR information architecture.

**SME Probe:** Which performance data should be treated as authoritative, and why?

---

### HR-APH3-B04-Q02 — Employee and Organizational Context

**Interview Question:** Why is employee and organizational context important to performance data?

### STAR Answer
**Situation:** Performance records were difficult to interpret after employees changed managers or organizational units.

**Task:** I needed to ensure performance information retained the correct business context.

**Action:** I linked performance records to employee identity, manager relationships, job/position and organizational structures, while considering effective dating.

**Result:** Historical performance could be interpreted correctly even when organizational relationships changed.

**SAP SuccessFactors Performance & Goals Example:** Employee Central provides foundational employee and organizational context consumed by performance processes.

**SME Probe:** Why is effective dating important for historical performance analysis?

---

### HR-APH3-B04-Q03 — Goal Data Model

**Interview Question:** What information should be captured for a performance goal?

### STAR Answer
**Situation:** A client stored goals primarily as free-text descriptions.

**Task:** I needed to improve goal quality and analytical value.

**Action:** I considered goal title, description, owner, category, alignment, measure, target, weighting, status, dates, progress and relevant organizational context.

**Result:** Goals became more measurable and useful for performance conversations and analytics.

**SAP SuccessFactors Performance & Goals Example:** Goal Management can structure objectives and attributes required for alignment and progress tracking.

**SME Probe:** Which goal attributes are essential for meaningful performance analytics?

---

### HR-APH3-B04-Q04 — Goal Alignment and Hierarchy

**Interview Question:** How would you model goal alignment across an enterprise?

### STAR Answer
**Situation:** Employees could create goals without visibility into how their work supported organizational priorities.

**Task:** I needed to make strategic alignment visible.

**Action:** I established relationships between enterprise priorities, team objectives and individual goals while avoiding excessive hierarchy.

**Result:** Employees could understand how individual outcomes contributed to broader business objectives.

**SAP SuccessFactors Performance & Goals Example:** Goal alignment and cascading capabilities can support structured relationships among organizational and individual objectives.

**SME Probe:** What risks arise when goal hierarchies become too complex?

---

### HR-APH3-B04-Q05 — Competency Information

**Interview Question:** How would you model competencies alongside goals?

### STAR Answer
**Situation:** The organization evaluated results but lacked consistent behavioral expectations.

**Task:** I needed to incorporate both what employees achieved and how they achieved it.

**Action:** I separated outcome-oriented goals from competency definitions and associated competency evidence within the performance process.

**Result:** Performance assessments became more balanced.

**SAP SuccessFactors Performance & Goals Example:** Performance forms can evaluate goals and competencies as distinct components of performance.

**SME Probe:** Why should competencies not simply be converted into goals?

---

### HR-APH3-B04-Q06 — Performance Evidence

**Interview Question:** What constitutes useful performance evidence?

### STAR Answer
**Situation:** Ratings were frequently based on memory and recent events.

**Task:** I needed a stronger evidence model.

**Action:** I considered goal outcomes, progress, feedback, achievements, behavioral observations and relevant documented examples, with appropriate ownership and privacy controls.

**Result:** Managers had a broader and more defensible evidence base.

**SAP SuccessFactors Performance & Goals Example:** Continuous Performance and formal performance processes can provide structured places for performance evidence.

**SME Probe:** How would you distinguish evidence from opinion?

---

### HR-APH3-B04-Q07 — Feedback Data

**Interview Question:** How should feedback information be treated in a performance information model?

### STAR Answer
**Situation:** Feedback existed in emails, chats and informal conversations with little consistency.

**Task:** I needed to determine what feedback should become part of the governed performance record.

**Action:** I distinguished structured performance feedback from informal communication and defined purpose, visibility, retention and access rules.

**Result:** Useful feedback became more accessible without turning every communication into formal performance data.

**SAP SuccessFactors Performance & Goals Example:** Continuous Performance capabilities can support structured feedback while broader communication remains outside the performance record.

**SME Probe:** What privacy risks arise when feedback is over-collected?

---

### HR-APH3-B04-Q08 — Rating Data

**Interview Question:** How would you design the data model for performance ratings?

### STAR Answer
**Situation:** Different business units used inconsistent rating scales.

**Task:** I needed to create comparable rating information.

**Action:** I defined rating scales, descriptions, applicability, effective dates and governance, while preserving the distinction between manager assessment and calibrated outcome.

**Result:** Rating information became more consistent and analytically useful.

**SAP SuccessFactors Performance & Goals Example:** Performance Management rating scales and calibration capabilities can support controlled rating processes.

**SME Probe:** Why should raw manager ratings and calibrated outcomes remain distinguishable?

---

### HR-APH3-B04-Q09 — Calibration Information

**Interview Question:** What information is needed to support a calibration process?

### STAR Answer
**Situation:** Leadership discussed ratings but lacked a consistent evidence base.

**Task:** I needed to make calibration data-driven.

**Action:** I identified employee context, goals, ratings, performance evidence, relevant comparison dimensions, calibration decisions and audit information.

**Result:** Calibration discussions became more structured and transparent.

**SAP SuccessFactors Performance & Goals Example:** Calibration capabilities can present performance information to authorized participants for structured rating discussions.

**SME Probe:** Which information should never be exposed broadly during calibration?

---

### HR-APH3-B04-Q10 — Effective Dating

**Interview Question:** How does effective dating affect performance data?

### STAR Answer
**Situation:** Historical reports showed current managers and organizations against prior performance records.

**Task:** I needed to preserve historical accuracy.

**Action:** I considered effective dates for employee relationships, organizational assignments, goals, cycles and performance records when designing reporting logic.

**Result:** Historical performance could be interpreted in the correct organizational context.

**SAP SuccessFactors Performance & Goals Example:** Performance reporting should align with Employee Central's effective-dated employee and organizational information.

**SME Probe:** What is the difference between current-state reporting and as-of-date reporting?

---

### HR-APH3-B04-Q11 — Performance Cycle Data

**Interview Question:** What information should identify a performance cycle?

### STAR Answer
**Situation:** Multiple performance cycles operated simultaneously across countries and employee groups.

**Task:** I needed to prevent ambiguity.

**Action:** I defined cycle identity, population, start/end dates, process stages, eligibility rules, ownership, status and applicable rating framework.

**Result:** Performance records could be associated with the correct business cycle.

**SAP SuccessFactors Performance & Goals Example:** Performance forms and goal plans can be governed according to defined cycle populations and timelines.

**SME Probe:** How would you handle employees moving between cycle populations?

---

### HR-APH3-B04-Q12 — Data Ownership

**Interview Question:** How would you determine ownership of performance data?

### STAR Answer
**Situation:** HR, managers and HRIT disputed who could change performance information.

**Task:** I needed to establish clear data ownership and stewardship.

**Action:** I separated business ownership, data stewardship, system administration and employee/manager responsibilities for each information domain.

**Result:** Changes became governed rather than dependent on individual interpretation.

**SAP SuccessFactors Performance & Goals Example:** Role-based permissions should reflect approved ownership and access rules.

**SME Probe:** Who should own the definition of a performance rating scale?

---

### HR-APH3-B04-Q13 — Data Quality

**Interview Question:** How would you improve the quality of performance data?

### STAR Answer
**Situation:** Duplicate goals, incomplete fields and inconsistent ratings affected reporting.

**Task:** I needed to establish measurable data-quality controls.

**Action:** I defined validation rules, mandatory attributes, duplicate checks, ownership, exception reporting and periodic quality reviews.

**Result:** Performance analytics became more reliable.

**SAP SuccessFactors Performance & Goals Example:** Configuration, workflow and reporting controls can help reduce incomplete or inconsistent performance information.

**SME Probe:** Which data-quality dimension would you prioritize first?

---

### HR-APH3-B04-Q14 — Performance Data Integration

**Interview Question:** Which external or adjacent HR data should be integrated with performance information?

### STAR Answer
**Situation:** Performance managers lacked relevant employee and organizational context.

**Task:** I needed to identify useful integration dependencies without creating unnecessary data movement.

**Action:** I prioritized authoritative employee, organizational, job and position context from Employee Central and defined controlled downstream relationships with development, rewards and talent processes.

**Result:** Performance decisions gained context while data ownership remained clear.

**SAP SuccessFactors Performance & Goals Example:** Employee Central can provide foundational context, while APH3 exchanges appropriate performance signals with Learning, Compensation and Succession capabilities.

**SME Probe:** How do you avoid creating multiple sources of truth?

---

### HR-APH3-B04-Q15 — Performance Data Security

**Interview Question:** How would you protect sensitive performance information?

### STAR Answer
**Situation:** Performance ratings and feedback contained sensitive employee information.

**Task:** I needed to balance useful access with confidentiality.

**Action:** I classified sensitive information, defined role-based access, minimized unnecessary exposure and incorporated audit and privacy requirements.

**Result:** Authorized users received the information needed for their responsibilities without broad access.

**SAP SuccessFactors Performance & Goals Example:** Role-Based Permissions and appropriate form visibility controls can enforce governed access.

**SME Probe:** Why is performance data particularly sensitive?

---

### HR-APH3-B04-Q16 — Historical Data Retention

**Interview Question:** How would you design retention for historical performance records?

### STAR Answer
**Situation:** The organization retained performance records indefinitely without a clear policy.

**Task:** I needed to balance historical value, legal requirements and privacy.

**Action:** I worked with HR, legal and privacy stakeholders to define retention periods, access rules, archival requirements and deletion processes.

**Result:** Historical information remained available when justified without uncontrolled accumulation.

**SAP SuccessFactors Performance & Goals Example:** Retention and deletion practices should align with enterprise data-governance policy and applicable SuccessFactors capabilities.

**SME Probe:** Who should approve the retention policy?

---

### HR-APH3-B04-Q17 — Performance Analytics Data

**Interview Question:** What data model is needed to analyze performance trends?

### STAR Answer
**Situation:** Leadership wanted to understand performance trends but reports were inconsistent.

**Task:** I needed to establish an analytical foundation.

**Action:** I standardized dimensions such as cycle, organization, role, rating, goal outcome, competency, population and time, while preserving source-system definitions.

**Result:** Leadership could analyze trends more consistently.

**SAP SuccessFactors Performance & Goals Example:** Performance data can contribute to broader people analytics when definitions and data lineage are governed.

**SME Probe:** Why is semantic consistency more important than simply having more data?

---

### HR-APH3-B04-Q18 — Data Lineage

**Interview Question:** How would you establish lineage for a performance KPI?

### STAR Answer
**Situation:** Executives questioned how a performance KPI had been calculated.

**Task:** I needed to make the metric traceable.

**Action:** I documented the source record, transformation logic, business definition, calculation, reporting layer and ownership.

**Result:** Stakeholders could trace the KPI from business definition to source data.

**SAP SuccessFactors Performance & Goals Example:** Performance reporting should preserve clear definitions for ratings, goal completion and other measures used in executive analytics.

**SME Probe:** What would you do if two reports used different definitions for the same KPI?

---

### HR-APH3-B04-Q19 — Performance Data and Adjacent Processes

**Interview Question:** How would you prevent performance data from being incorrectly reused by compensation or succession processes?

### STAR Answer
**Situation:** A client wanted to use performance ratings directly as automatic inputs to rewards and succession decisions.

**Task:** I needed to preserve process boundaries while enabling useful integration.

**Action:** I distinguished performance outcomes from downstream decision criteria and established controlled data interfaces and governance with the relevant process owners.

**Result:** Performance information became a governed input rather than an uncontrolled decision rule.

**SAP SuccessFactors Performance & Goals Example:** APH3 owns performance information; ARP5 owns Compensation and AGL4 owns Succession & Development. Integration should preserve these boundaries.

**SME Probe:** Why is a performance rating not equivalent to employee potential?

---

### HR-APH3-B04-Q20 — Enterprise Performance Information Architecture

**Interview Question:** How would you architect performance information for a global enterprise?

### STAR Answer
**Situation:** A global organization needed reliable performance information across countries, business units and technology platforms.

**Task:** I needed to create an enterprise information architecture that supported operations, analytics and future transformation.

**Action:** I established authoritative sources, core performance entities, effective dating, data ownership, quality rules, security, lineage, integration contracts and analytical definitions.

**Result:** Performance information became a trusted enterprise asset supporting employee conversations, leadership decisions and workforce outcomes.

**SAP SuccessFactors Performance & Goals Example:** SuccessFactors Performance & Goals would operate within the broader HR data architecture, using Employee Central as foundational employee context and controlled interfaces to adjacent talent capabilities.

**SME Probe:** What architecture principle would you use to prevent performance data from becoming another silo?

---

## Completion Standard

- **20 / 20 unique scenarios**
- **20 / 20 STAR answers**
- **20 / 20 SME probes**
- Stable IDs: **HR-APH3-B04-Q01 → HR-APH3-B04-Q20**
- Focus: performance information model, goals, competencies, evidence, feedback, ratings, calibration, effective dating, data ownership, quality, security, retention, analytics, lineage and integration.
- Boundary maintained against AGL4 Succession & Development and ARP5 Compensation.

**Theme 04 complete: 20 / 20 scenarios.**
**Cumulative APH3 coverage: 4 / 22 themes = 80 / 440 scenarios.**
