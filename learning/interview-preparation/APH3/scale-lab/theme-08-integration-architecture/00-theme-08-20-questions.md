# APH3 — Theme 08: Integration & Architecture
## 20 Scenario-Based Interview Questions & STAR Answers

**Stream:** APH3 — Applied SAP SuccessFactors Performance & Goals  
**Theme:** 08 — Integration & Architecture  
**Answer method:** STAR — Situation → Task → Action → Result  
**Stable IDs:** HR-APH3-B08-Q01 → HR-APH3-B08-Q20

---

### HR-APH3-B08-Q01 — Integration Architecture for Performance

**Interview Question:** How would you architect Performance & Goals integration within an enterprise HR landscape?

### STAR Answer
**Situation:** Performance data was isolated from the broader HR ecosystem.

**Task:** I needed to create a connected architecture without creating duplicate systems of record.

**Action:** I established Employee Central as the authoritative source for employee and organizational context, defined APH3 performance information ownership, and designed governed interfaces with adjacent HR capabilities and analytics.

**Result:** Performance became a connected enterprise capability while ownership remained clear.

**SAP SuccessFactors Performance & Goals Example:** Performance & Goals was integrated with Employee Central and connected to relevant Learning, Compensation, Succession and analytics capabilities through controlled interfaces.

**SME Probe:** What is the first architecture question you ask before designing an integration?

---

### HR-APH3-B08-Q02 — Employee Central Integration

**Interview Question:** What Employee Central information is typically important to Performance & Goals?

### STAR Answer
**Situation:** Performance forms contained outdated manager and organizational information.

**Task:** I needed reliable employee context.

**Action:** I identified employee identity, manager relationships, job/position and organizational attributes required by the performance process and established Employee Central as the authoritative source.

**Result:** Performance processes used more reliable organizational context.

**SAP SuccessFactors Performance & Goals Example:** Employee Central information supported eligibility, routing, population selection and contextual performance reporting.

**SME Probe:** Why should performance maintain as little employee master data as possible?

---

### HR-APH3-B08-Q03 — Integration Ownership

**Interview Question:** How would you determine which system owns a data element in an integrated HR architecture?

### STAR Answer
**Situation:** Multiple HR applications stored employee and performance attributes.

**Task:** I needed to eliminate conflicting sources of truth.

**Action:** I evaluated business ownership, lifecycle responsibility, update authority, data quality and downstream usage before assigning system-of-record status.

**Result:** Integration contracts became based on explicit ownership rather than convenience.

**SAP SuccessFactors Performance & Goals Example:** Employee Central remained authoritative for worker context while Performance & Goals owned performance-specific information.

**SME Probe:** What happens when two applications both claim ownership?

---

### HR-APH3-B08-Q04 — API-Led Integration

**Interview Question:** When would you prefer API-led integration for Performance & Goals?

### STAR Answer
**Situation:** A client had point-to-point integrations between multiple HR applications.

**Task:** I needed to reduce coupling and improve maintainability.

**Action:** I assessed reusable business information, interface frequency, ownership and security and introduced API-led patterns where they created reusable services.

**Result:** The integration landscape became more manageable and extensible.

**SAP SuccessFactors Performance & Goals Example:** Relevant SuccessFactors APIs and integration services could expose governed performance information to authorized consumers.

**SME Probe:** When would a simple scheduled interface be more appropriate than an API?

---

### HR-APH3-B08-Q05 — Integration with Learning

**Interview Question:** How would you integrate performance outcomes with Learning without blurring process ownership?

### STAR Answer
**Situation:** Managers identified capability gaps during performance reviews but development actions were disconnected.

**Task:** I needed to connect the processes.

**Action:** I defined performance as the source of relevant development signals while Learning remained the owner of learning execution and completion.

**Result:** Performance conversations could lead to meaningful development actions without duplicating learning data.

**SAP SuccessFactors Performance & Goals Example:** Performance & Goals can provide development signals to Learning through governed integration.

**SME Probe:** Why should completion status remain owned by Learning?

---

### HR-APH3-B08-Q06 — Integration with Compensation

**Interview Question:** How would you integrate performance outcomes with Compensation?

### STAR Answer
**Situation:** Compensation planners needed approved performance information as an input to reward decisions.

**Task:** I needed to enable the data exchange without making performance ratings an automatic compensation rule.

**Action:** I defined the approved performance outcome, timing, ownership, security and interface contract, while Compensation retained reward decision logic.

**Result:** Performance became a governed input to rewards rather than an uncontrolled calculation dependency.

**SAP SuccessFactors Performance & Goals Example:** APH3 provides approved performance outcomes; ARP5 applies its own compensation process and decision rules.

**SME Probe:** Why should a performance rating not automatically determine a merit increase?

---

### HR-APH3-B08-Q07 — Integration with Succession

**Interview Question:** How would you integrate Performance & Goals with Succession & Development?

### STAR Answer
**Situation:** Talent leaders wanted performance ratings directly converted into succession decisions.

**Task:** I needed to preserve the distinction between performance and potential.

**Action:** I defined controlled performance signals for AGL4 while keeping potential, readiness and succession decisions within the Succession & Development domain.

**Result:** The architecture enabled useful information sharing without creating an invalid decision model.

**SAP SuccessFactors Performance & Goals Example:** Performance outcomes can be consumed by Succession processes while AGL4 remains accountable for talent-pool, readiness and succession decisions.

**SME Probe:** Why is performance not equivalent to potential?

---

### HR-APH3-B08-Q08 — Integration with Analytics

**Interview Question:** How would you architect performance data for enterprise analytics?

### STAR Answer
**Situation:** Executives received inconsistent performance reports from multiple sources.

**Task:** I needed to establish reliable analytical consumption.

**Action:** I defined common KPI semantics, source ownership, data lineage, refresh requirements, security and analytical dimensions before exposing performance information.

**Result:** Leadership gained more consistent performance insights.

**SAP SuccessFactors Performance & Goals Example:** Performance information could feed governed people analytics rather than allowing every report to calculate ratings differently.

**SME Probe:** What should be standardized before building an executive dashboard?

---

### HR-APH3-B08-Q09 — Integration Error Handling

**Interview Question:** How would you design error handling for a performance integration?

### STAR Answer
**Situation:** Employee-context updates occasionally failed before a performance cycle.

**Task:** I needed to prevent silent data corruption.

**Action:** I defined validation, error detection, logging, retry behavior, reconciliation, alerting and operational ownership.

**Result:** Integration failures became visible and recoverable.

**SAP SuccessFactors Performance & Goals Example:** Integration monitoring and controlled error handling were included for Employee Central and downstream performance interfaces.

**SME Probe:** Which errors should be retried automatically?

---

### HR-APH3-B08-Q10 — Reconciliation

**Interview Question:** How would you reconcile Performance & Goals information across systems?

### STAR Answer
**Situation:** Performance populations did not match Employee Central populations after an organizational change.

**Task:** I needed to identify and correct discrepancies.

**Action:** I defined reconciliation keys, expected counts, exception reports, ownership and timing for comparison between source and target.

**Result:** Population mismatches were detected before they affected performance cycles.

**SAP SuccessFactors Performance & Goals Example:** Employee IDs and effective-dated organizational context can be used as reconciliation anchors.

**SME Probe:** What is the difference between validation and reconciliation?

---

### HR-APH3-B08-Q11 — Event-Driven vs Batch Integration

**Interview Question:** How would you choose between event-driven and scheduled integration for performance processes?

### STAR Answer
**Situation:** The client wanted every employee change to update performance information immediately.

**Task:** I needed to determine the appropriate integration pattern.

**Action:** I assessed business urgency, transaction volume, consistency needs, failure handling and operational complexity.

**Result:** Time-sensitive information used appropriate near-real-time patterns while less urgent synchronization remained scheduled.

**SAP SuccessFactors Performance & Goals Example:** Employee-context synchronization was designed according to the actual timing needs of the performance process.

**SME Probe:** When is real-time integration unnecessary?

---

### HR-APH3-B08-Q12 — Security of Integrations

**Interview Question:** How would you secure Performance & Goals integrations?

### STAR Answer
**Situation:** Performance information was being exchanged with multiple HR systems.

**Task:** I needed to protect sensitive employee information.

**Action:** I applied least privilege, secure authentication, data minimization, authorized interfaces, encryption expectations, logging and access monitoring.

**Result:** Integration remained useful while reducing unnecessary exposure.

**SAP SuccessFactors Performance & Goals Example:** SuccessFactors integration mechanisms were designed around approved authentication, authorization and data-access controls.

**SME Probe:** Why should integration security be designed differently from user-interface security?

---

### HR-APH3-B08-Q13 — Integration with External HR Systems

**Interview Question:** How would you integrate Performance & Goals with a non-SAP HR application?

### STAR Answer
**Situation:** A business unit retained an external workforce platform while adopting SuccessFactors Performance & Goals.

**Task:** I needed to integrate without compromising the enterprise architecture.

**Action:** I defined system ownership, canonical data, interface contracts, transformation rules, security, monitoring and lifecycle responsibilities.

**Result:** The hybrid landscape operated with explicit boundaries.

**SAP SuccessFactors Performance & Goals Example:** SuccessFactors performance capabilities could participate in a hybrid HR architecture through governed APIs or integration services.

**SME Probe:** What should be defined before selecting the technical integration mechanism?

---

### HR-APH3-B08-Q14 — Identity and Access Integration

**Interview Question:** Why is identity architecture important to Performance & Goals integration?

### STAR Answer
**Situation:** Users sometimes received incorrect performance access after organizational changes.

**Task:** I needed consistent identity and authorization behavior.

**Action:** I aligned employee identity, organizational context, role assignment and access lifecycle across the HR architecture.

**Result:** Access became more consistent and easier to govern.

**SAP SuccessFactors Performance & Goals Example:** Identity and role information supports controlled access to sensitive Performance & Goals information.

**SME Probe:** How can stale identity data create a performance-data risk?

---

### HR-APH3-B08-Q15 — Integration During Organizational Change

**Interview Question:** How would you design integration for a merger or acquisition affecting performance processes?

### STAR Answer
**Situation:** Two organizations had different employee structures and performance systems.

**Task:** I needed to support transition without losing performance context.

**Action:** I mapped employee identities, organizational structures, performance cycles and ownership, then defined interim and target integration patterns.

**Result:** The organization could transition performance processes in controlled stages.

**SAP SuccessFactors Performance & Goals Example:** Employee Central became the target employee context while performance information was migrated or integrated according to the approved transformation roadmap.

**SME Probe:** What should be standardized first in an HR integration during M&A?

---

### HR-APH3-B08-Q16 — Integration Testing Architecture

**Interview Question:** How would you design end-to-end integration testing for Performance & Goals?

### STAR Answer
**Situation:** Individual systems passed testing, but integrated performance scenarios failed.

**Task:** I needed to validate the complete business journey.

**Action:** I tested employee lifecycle changes, population selection, goal and form behavior, downstream performance outcomes, errors, security and reconciliation across system boundaries.

**Result:** Integration defects were identified before business acceptance.

**SAP SuccessFactors Performance & Goals Example:** Employee Central → Performance & Goals → downstream talent/analytics flows were tested using realistic employee scenarios.

**SME Probe:** Why is interface-level testing insufficient?

---

### HR-APH3-B08-Q17 — Integration Performance

**Interview Question:** How would you prevent integration design from creating performance problems during the annual review cycle?

### STAR Answer
**Situation:** The annual cycle created a large peak in HR transactions and reporting.

**Task:** I needed to protect system and integration performance.

**Action:** I assessed transaction volumes, timing, payload size, batch windows, API usage, reporting load and downstream dependencies.

**Result:** Integration was sequenced and optimized for peak-cycle conditions.

**SAP SuccessFactors Performance & Goals Example:** Performance-cycle integrations were designed with appropriate scheduling and monitoring for high-volume periods.

**SME Probe:** Which integration metrics would you monitor during peak performance cycles?

---

### HR-APH3-B08-Q18 — Integration Observability

**Interview Question:** What observability would you expect for critical Performance & Goals integrations?

### STAR Answer
**Situation:** Support teams learned about integration failures only when employees reported problems.

**Task:** I needed proactive operational visibility.

**Action:** I defined monitoring for transaction status, failures, latency, volume anomalies, reconciliation differences and business-impacting exceptions.

**Result:** Support teams could identify and resolve integration issues earlier.

**SAP SuccessFactors Performance & Goals Example:** Critical Employee Central and Performance & Goals interfaces were included in operational monitoring and reconciliation.

**SME Probe:** Why should monitoring include business outcomes, not only technical status?

---

### HR-APH3-B08-Q19 — Integration Architecture Trade-Off

**Interview Question:** How would you choose between a direct point-to-point interface and an enterprise integration layer?

### STAR Answer
**Situation:** A team proposed a direct interface between Performance & Goals and an external application for a single requirement.

**Task:** I needed to make an architecture decision based on long-term value.

**Action:** I assessed reuse, coupling, volume, security, ownership, change frequency, operational complexity and future integration demand.

**Result:** The selected pattern balanced immediate delivery with enterprise maintainability.

**SAP SuccessFactors Performance & Goals Example:** SAP Integration Suite or an appropriate integration layer can be considered where reuse, orchestration and governance justify it.

**SME Probe:** When is point-to-point integration architecturally acceptable?

---

### HR-APH3-B08-Q20 — Connected Performance Architecture

**Interview Question:** How would you describe the target integration architecture for Performance & Goals to an enterprise architecture board?

### STAR Answer
**Situation:** The architecture board wanted assurance that Performance & Goals would not become another HR silo.

**Task:** I needed to demonstrate how performance would participate in the connected HR ecosystem.

**Action:** I presented Employee Central as foundational employee context, Performance & Goals as the performance capability, governed interfaces to Learning, Compensation and Succession, analytics consumption, identity/security controls, integration monitoring and clear data ownership.

**Result:** The board approved an architecture that connected performance information while preserving domain boundaries.

**SAP SuccessFactors Performance & Goals Example:** SuccessFactors Performance & Goals operated as part of an integrated HR architecture with controlled interfaces and clear system-of-record responsibilities.

**SME Probe:** What architecture principle prevents integration from becoming uncontrolled data duplication?

---

## Completion Standard

- **20 / 20 unique scenarios**
- **20 / 20 STAR answers**
- **20 / 20 SME probes**
- Stable IDs: **HR-APH3-B08-Q01 → HR-APH3-B08-Q20**
- Focus: Employee Central integration, Learning, Compensation, Succession, analytics, API-led integration, batch/event patterns, ownership, reconciliation, error handling, security, identity, external systems, M&A, testing, performance, observability and enterprise integration architecture.
- Boundary maintained against AGL4 Succession & Development, ARP5 Compensation and other HR domains.

**Theme 08 complete: 20 / 20 scenarios.**
**Cumulative APH3 coverage: 8 / 22 themes = 160 / 440 scenarios.**
