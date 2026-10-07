# 20 Scenario-Based Interview Questions & STAR Answers

**Stream:** APH3 — Applied SAP SuccessFactors Performance & Goals  
**Theme:** 15 — Risk, Controls & Security  
**Target:** 20 unique scenario-based interview questions  
**Answer method:** STAR — Situation → Task → Action → Result  
**Product posture:** HCM-first, Performance & Goals-specific  
**Stable IDs:** HR-APH3-B15-Q01 → HR-APH3-B15-Q20

---

### HR-APH3-B15-Q01 — Protecting Confidential Performance Ratings
### Interview Question
How would you protect confidential performance ratings from inappropriate access?

### STAR Answer
**Situation:** A global organization found that performance ratings were visible to managers outside the intended reporting hierarchy.

**Task:** I had to restore least-privilege access without disrupting legitimate review activity.

**Action:** I mapped the business access model, reviewed role-based permissions, separated employee, manager, HR and HR-admin access, and tested positive and negative access scenarios. I also included audit evidence and a controlled access-review process.

**Result:** Unauthorized visibility was removed while legitimate review access remained available, improving confidentiality and control assurance.

**SAP SuccessFactors Performance & Goals Example:** I would use Role-Based Permissions to restrict performance forms, ratings and related employee data to the appropriate population and validate the resulting access matrix.

**SME Probe:** How would you prove that the restriction works for both direct and indirect managers?

---

### HR-APH3-B15-Q02 — Least Privilege for Performance Data
### Interview Question
How would you design least-privilege access for Performance & Goals?

### STAR Answer
**Situation:** The client had accumulated broad HR roles over several implementation phases.

**Task:** I needed to reduce excessive privileges without blocking operational HR processes.

**Action:** I classified permissions by persona, separated read, initiate, edit and administer capabilities, removed unused permissions, and introduced periodic access recertification. I validated the design against real business scenarios.

**Result:** The organization moved from broad inherited access toward a controlled persona-based security model.

**SAP SuccessFactors Performance & Goals Example:** I would design RBP around employee, manager, HR business partner, talent administrator and system-administrator personas, with population restrictions aligned to organizational responsibility.

**SME Probe:** What evidence would you retain for an access recertification?

---

### HR-APH3-B15-Q03 — Segregation of Duties
### Interview Question
How would you address segregation-of-duties concerns in performance management?

### STAR Answer
**Situation:** One administrator could configure, modify and approve performance outcomes.

**Task:** I needed to reduce the risk of inappropriate changes while preserving efficient administration.

**Action:** I separated configuration, operational administration and approval responsibilities, introduced controlled privileged access, and documented the approval path. I tested each role against conflicting activities.

**Result:** The control environment became more defensible and independent review was strengthened.

**SAP SuccessFactors Performance & Goals Example:** I would avoid giving one persona unrestricted configuration, employee-data administration and performance-outcome authority where business controls require separation.

**SME Probe:** Which conflicts would you prioritize in a performance-management SoD review?

---

### HR-APH3-B15-Q04 — Sensitive Feedback Access
### Interview Question
How would you secure sensitive manager or employee feedback?

### STAR Answer
**Situation:** Managers were entering candid feedback that contained sensitive employee information.

**Task:** I needed to preserve useful feedback while limiting unnecessary exposure.

**Action:** I defined who should view each feedback component, applied minimum-necessary access, trained managers on appropriate content, and validated access across employee, manager and HR personas.

**Result:** Sensitive feedback remained useful without becoming broadly visible.

**SAP SuccessFactors Performance & Goals Example:** I would align form sections, permissions and workflow participants so that confidential feedback is visible only to intended participants.

**SME Probe:** How would you distinguish confidentiality from simple usability restrictions?

---

### HR-APH3-B15-Q05 — HR and Manager Access Boundaries
### Interview Question
How would you resolve a conflict between HR visibility and manager confidentiality?

### STAR Answer
**Situation:** HR needed oversight for governance, while managers expected certain feedback to remain within the performance conversation.

**Task:** I needed to establish a defensible access boundary.

**Action:** I identified the legal, policy and process requirements, classified the information, defined persona-specific visibility, and obtained HR/legal agreement before configuring the control.

**Result:** The organization achieved a clear, documented access model instead of relying on informal expectations.

**SAP SuccessFactors Performance & Goals Example:** I would design RBP and form permissions according to the approved HR policy rather than granting universal HR access by default.

**SME Probe:** What would you do if the business policy itself is ambiguous?

---

### HR-APH3-B15-Q06 — Auditability of Performance Changes
### Interview Question
How would you ensure performance changes are auditable?

### STAR Answer
**Situation:** A client could not confidently explain who changed a performance outcome and when.

**Task:** I needed to improve traceability for material changes.

**Action:** I identified critical transactions and fields, established audit requirements, validated available audit mechanisms, restricted administrative access, and defined evidence-retention expectations.

**Result:** The organization could investigate material changes with stronger evidence and accountability.

**SAP SuccessFactors Performance & Goals Example:** I would validate the relevant audit/history capabilities and ensure sensitive administrative activities are controlled and reviewable.

**SME Probe:** What is the difference between functional history and an enterprise audit control?

---

### HR-APH3-B15-Q07 — Data Minimization
### Interview Question
How would you apply data minimization to Performance & Goals?

### STAR Answer
**Situation:** Performance forms contained information that was not required for the business process.

**Task:** I needed to reduce unnecessary collection and exposure.

**Action:** I mapped each data element to a business purpose, removed unnecessary fields, challenged free-text collection, and aligned retention with policy and regulatory requirements.

**Result:** The solution collected less sensitive information and reduced privacy exposure.

**SAP SuccessFactors Performance & Goals Example:** I would keep only performance information necessary for goal setting, review, calibration and approved downstream processes.

**SME Probe:** How would you handle a stakeholder who insists that a field might be useful someday?

---

### HR-APH3-B15-Q08 — Retention and Disposal
### Interview Question
How would you incorporate retention requirements into performance-management architecture?

### STAR Answer
**Situation:** The client had no consistent policy for retaining historical performance records.

**Task:** I needed to avoid both premature deletion and indefinite retention.

**Action:** I worked with HR, legal and privacy stakeholders to define retention categories, documented the lifecycle, identified system capabilities and dependencies, and built governance checkpoints.

**Result:** Retention became an explicit architecture concern rather than an unmanaged accumulation of historical data.

**SAP SuccessFactors Performance & Goals Example:** I would align performance-record retention with enterprise policy and validate what can be controlled natively versus through broader information-governance processes.

**SME Probe:** What risks arise from retaining performance data longer than necessary?

---

### HR-APH3-B15-Q09 — Secure Integration of Performance Data
### Interview Question
How would you secure integrations carrying performance information?

### STAR Answer
**Situation:** Performance outcomes were being sent to downstream HR analytics and talent processes.

**Task:** I needed to protect sensitive data while enabling legitimate business integration.

**Action:** I classified the payload, minimized transmitted attributes, secured interfaces and credentials, restricted receiving-system access, and tested unauthorized access and failure scenarios.

**Result:** Downstream consumption remained available with a smaller and better-controlled data footprint.

**SAP SuccessFactors Performance & Goals Example:** I would design integrations so that only approved Performance & Goals attributes move to downstream applications through controlled integration patterns and identities.

**SME Probe:** How would you prevent an integration from becoming a security bypass?

---

### HR-APH3-B15-Q10 — Third-Party Vendor Risk
### Interview Question
How would you assess a third-party tool that consumes performance data?

### STAR Answer
**Situation:** A client wanted to introduce an external analytics solution using employee performance information.

**Task:** I needed to determine whether the integration was acceptable from a security and privacy perspective.

**Action:** I assessed data necessity, vendor controls, access model, data location, contractual requirements, retention, incident handling and integration security. I proposed a minimized dataset where possible.

**Result:** The business could make an informed go/no-go decision based on risk rather than functionality alone.

**SAP SuccessFactors Performance & Goals Example:** I would treat any external performance-data consumer as part of the HR security architecture and establish explicit data-flow and control requirements before integration.

**SME Probe:** What would make you reject the integration even if the business value is high?

---

### HR-APH3-B15-Q11 — Migration Security
### Interview Question
How would you secure historical performance data during migration?

### STAR Answer
**Situation:** Historical performance records had to be migrated from a legacy HR platform.

**Task:** I needed to protect sensitive data throughout extraction, transformation, transfer and loading.

**Action:** I limited migration-team access, used controlled transfer mechanisms, minimized temporary copies, protected files and credentials, validated reconciliation, and defined secure disposal of temporary data.

**Result:** Historical performance data was migrated with stronger confidentiality and traceability controls.

**SAP SuccessFactors Performance & Goals Example:** I would include performance-history security requirements in the migration workstream, including controlled extracts, restricted migration roles and post-load access validation.

**SME Probe:** How would you secure a migration file that temporarily contains highly sensitive ratings?

---

### HR-APH3-B15-Q12 — Emergency Access
### Interview Question
How would you handle emergency administrative access to performance data?

### STAR Answer
**Situation:** A production issue required elevated access outside normal administration procedures.

**Task:** I needed to restore service without creating uncontrolled privileged access.

**Action:** I used a time-bound emergency-access process, required authorization, recorded the reason and activity, limited the scope of access, and performed a post-event review.

**Result:** The issue was resolved while preserving accountability for privileged activity.

**SAP SuccessFactors Performance & Goals Example:** I would use the enterprise privileged-access model and ensure any elevated SuccessFactors administration is approved, limited and reviewed.

**SME Probe:** Why is emergency access different from a permanent administrator role?

---

### HR-APH3-B15-Q13 — Security Testing
### Interview Question
How would you test security controls before releasing Performance & Goals changes?

### STAR Answer
**Situation:** A new performance process introduced new roles, form sections and workflow participants.

**Task:** I needed to prove that intended users could perform their work without exposing restricted information.

**Action:** I created a security test matrix covering positive, negative, boundary and cross-population scenarios. I tested employee, manager, HR and administrator personas and retained evidence.

**Result:** Security defects were identified before production release and the release decision had objective evidence.

**SAP SuccessFactors Performance & Goals Example:** I would include RBP and population-security tests in the Performance & Goals SIT/UAT and regression strategy.

**SME Probe:** Which negative-security test would you never omit?

---

### HR-APH3-B15-Q14 — Role Lifecycle and Recertification
### Interview Question
How would you prevent access from remaining after an employee changes role?

### STAR Answer
**Situation:** Employees moving between HR roles retained permissions from their previous responsibilities.

**Task:** I needed to reduce stale-access risk.

**Action:** I linked role changes to access-management processes, defined joiner-mover-leaver controls, introduced periodic recertification and assigned ownership for exceptions.

**Result:** Security became a lifecycle process rather than a one-time implementation task.

**SAP SuccessFactors Performance & Goals Example:** I would ensure Performance & Goals permissions reflect current organizational responsibilities and are reviewed when HR roles or populations change.

**SME Probe:** Who should own the business approval for continued privileged access?

---

### HR-APH3-B15-Q15 — Insider Risk
### Interview Question
How would you address insider-risk concerns around performance information?

### STAR Answer
**Situation:** A privileged HR user had broad access to employee performance information.

**Task:** I needed to reduce the opportunity for inappropriate use without preventing legitimate HR work.

**Action:** I reduced unnecessary privileges, separated duties, strengthened monitoring and review, and ensured sensitive exports were controlled.

**Result:** The organization reduced exposure while maintaining required HR operations.

**SAP SuccessFactors Performance & Goals Example:** I would combine least privilege, population restrictions, controlled administrative access and governance over exports/reporting.

**SME Probe:** Why is monitoring alone insufficient for insider risk?

---

### HR-APH3-B15-Q16 — Global Privacy Requirements
### Interview Question
How would you design Performance & Goals security for a global workforce?

### STAR Answer
**Situation:** A multinational organization operated under different privacy expectations across jurisdictions.

**Task:** I needed a common architecture that could accommodate legitimate regional differences.

**Action:** I established global security principles, identified regional constraints with privacy/legal teams, minimized sensitive data, documented data flows and designed controlled exceptions.

**Result:** The solution supported global consistency without assuming that one access model fits every jurisdiction.

**SAP SuccessFactors Performance & Goals Example:** I would treat employee performance information as sensitive HR data and align SuccessFactors access, integration and reporting with the organization's approved regional privacy model.

**SME Probe:** How do you avoid creating uncontrolled regional customizations?

---

### HR-APH3-B15-Q17 — Secure Reporting and Analytics
### Interview Question
How would you secure performance reports and analytics?

### STAR Answer
**Situation:** Leaders wanted enterprise-wide performance dashboards while managers required only their authorized populations.

**Task:** I needed to provide useful insight without creating a reporting-based security bypass.

**Action:** I classified reports by sensitivity, aligned reporting access with business populations, minimized detailed data, and tested whether users could infer restricted information.

**Result:** Leadership received decision-support insight while detailed employee performance information remained controlled.

**SAP SuccessFactors Performance & Goals Example:** I would validate report permissions, population scope and sensitive-field exposure for Performance & Goals analytics.

**SME Probe:** What is the difference between restricting a report and restricting the underlying data?

---

### HR-APH3-B15-Q18 — AI Governance for Performance Insights
### Interview Question
How would you address security and governance when AI is used with performance data?

### STAR Answer
**Situation:** The business wanted AI-generated performance insights from employee data.

**Task:** I needed to ensure the use case did not create unauthorized access, inappropriate inference or uncontrolled automated decisions.

**Action:** I defined the permitted data scope, access boundaries, human oversight, transparency expectations and security controls. I also challenged whether every proposed attribute was necessary for the AI use case.

**Result:** The organization could explore AI value with explicit governance instead of treating AI as outside the existing HR security model.

**SAP SuccessFactors Performance & Goals Example:** I would apply the same least-privilege and data-minimization principles to AI-enabled Performance & Goals scenarios and require human governance for consequential decisions.

**SME Probe:** What additional risk does AI introduce beyond conventional reporting?

---

### HR-APH3-B15-Q19 — Security Incident Response
### Interview Question
How would you respond if confidential performance information were exposed?

### STAR Answer
**Situation:** A security review identified that restricted performance information had been visible to an unauthorized population.

**Task:** I needed to contain the exposure, understand scope and restore the control.

**Action:** I coordinated with security and HR stakeholders, restricted the affected access path, preserved evidence, assessed affected data and users, corrected the permission model, and supported the organization's incident process.

**Result:** Exposure was contained and the organization had a documented remediation path rather than an ad-hoc configuration change.

**SAP SuccessFactors Performance & Goals Example:** I would treat the incident as both a security event and an HR-data governance issue, then validate the corrected RBP/population model through targeted regression testing.

**SME Probe:** What would you document before changing the configuration?

---

### HR-APH3-B15-Q20 — Security by Design
### Interview Question
How would you embed security by design into a Performance & Goals implementation?

### STAR Answer
**Situation:** A project team had historically treated security as a final testing activity.

**Task:** I needed to make security an architecture concern from requirements through operations.

**Action:** I introduced security requirements during discovery, mapped personas and data flows, designed least-privilege access, included privacy and integration controls, built security test cases, and defined operational recertification.

**Result:** Security moved from a release gate to a continuous design principle, reducing rework and improving confidence in the solution.

**SAP SuccessFactors Performance & Goals Example:** I would embed RBP, population security, data minimization, secure integration, auditability and security testing into the Performance & Goals lifecycle from design through production support.

**SME Probe:** What security requirement would you define before configuring the first performance form?

---

## Completion Standard

- **20/20 unique scenario-based interview questions**
- **20/20 STAR answers**
- **20/20 SAP SuccessFactors Performance & Goals examples**
- **20/20 SME probes**
- Coverage includes confidentiality, least privilege, SoD, auditability, privacy, retention, secure integration, vendor risk, migration security, emergency access, security testing, access lifecycle, insider risk, global privacy, analytics security, AI governance, incident response and security-by-design.
- Explicitly distinct from Theme 13 (Troubleshooting & RCA) and Theme 14 (Scenario-Based Problem Solving).

**APH3 cumulative status after Theme 15: 15/22 themes = 300/440 scenarios.**
