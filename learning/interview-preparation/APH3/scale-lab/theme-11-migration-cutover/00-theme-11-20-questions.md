# APH3 — Theme 11: Migration & Cutover
## 20 Scenario-Based Interview Questions & STAR Answers

**Stream:** APH3 — Applied SAP SuccessFactors Performance & Goals  
**Theme:** 11 — Migration & Cutover  
**Answer method:** STAR — Situation → Task → Action → Result  
**Stable IDs:** HR-APH3-B11-Q01 → HR-APH3-B11-Q20

---

### HR-APH3-B11-Q01 — Migration Strategy

**Interview Question:** How would you define a migration strategy for Performance & Goals?

### STAR Answer
**Situation:** A global organization was replacing a legacy appraisal platform with SuccessFactors Performance & Goals.

**Task:** I needed to determine what should move, what should be transformed and what could be retired.

**Action:** I classified active goals, current-cycle performance records, historical reviews, ratings, competencies and reference data by business value, retention requirements, target-model compatibility and migration complexity.

**Result:** The program adopted a risk-based migration scope rather than attempting to copy the legacy system wholesale.

**SAP SuccessFactors Performance & Goals Example:** Goal and performance information was mapped to the approved SuccessFactors target structures, with historical data migrated only where justified.

**SME Probe:** What principle should determine migration scope?

---

### HR-APH3-B11-Q02 — Migration Data Inventory

**Interview Question:** How would you build a migration inventory for Performance & Goals?

### STAR Answer
**Situation:** The legacy system contained many years of performance information with inconsistent structures.

**Task:** I needed to establish exactly what existed before designing mappings.

**Action:** I inventoried goals, goal attributes, ratings, competencies, forms, review cycles, employee references, dates, statuses and historical records and identified ownership and data quality.

**Result:** The team had a reliable baseline for migration planning.

**SAP SuccessFactors Performance & Goals Example:** Legacy goal and performance objects were catalogued against the target Goal Management and Performance Management model.

**SME Probe:** Why should data profiling precede mapping?

---

### HR-APH3-B11-Q03 — Data Mapping

**Interview Question:** How would you map legacy performance data into SuccessFactors?

### STAR Answer
**Situation:** The legacy platform used different goal fields and rating definitions.

**Task:** I needed to preserve business meaning rather than simply match field names.

**Action:** I mapped each source attribute to the target semantic model, documented transformations, default handling, exclusions and unresolved values.

**Result:** Migration became traceable and business meaning was preserved.

**SAP SuccessFactors Performance & Goals Example:** Legacy goals, ratings and competencies were mapped to approved SuccessFactors structures and rating definitions.

**SME Probe:** What should happen when a legacy field has no valid target equivalent?

---

### HR-APH3-B11-Q04 — Data Cleansing

**Interview Question:** What data-quality problems would you address before migrating performance information?

### STAR Answer
**Situation:** Legacy records contained duplicate goals, missing managers, inconsistent ratings and invalid dates.

**Task:** I needed to prevent poor-quality data from contaminating the new platform.

**Action:** I defined cleansing rules, ownership, exception reports and approval criteria for correcting or excluding records.

**Result:** The target system received more reliable information.

**SAP SuccessFactors Performance & Goals Example:** Employee references, goals, ratings and historical performance records were cleansed before loading.

**SME Probe:** Who should approve business-sensitive data cleansing decisions?

---

### HR-APH3-B11-Q05 — Historical Performance Data

**Interview Question:** How would you decide how much historical performance data to migrate?

### STAR Answer
**Situation:** Stakeholders wanted all historical reviews available in the new system.

**Task:** I needed to balance employee value, legal retention, privacy, migration effort and usability.

**Action:** I assessed retention policy, employee needs, reporting requirements, historical comparability and target-system suitability before defining the migration window.

**Result:** The organization migrated meaningful history without unnecessary legacy burden.

**SAP SuccessFactors Performance & Goals Example:** Historical performance information was migrated only where it had approved business or compliance value.

**SME Probe:** Why can migrating every historical record be harmful?

---

### HR-APH3-B11-Q06 — Active Performance Cycle

**Interview Question:** How would you migrate an organization that is already partway through a performance cycle?

### STAR Answer
**Situation:** A platform replacement was scheduled during an active review cycle.

**Task:** I needed to protect employee performance records and business continuity.

**Action:** I assessed cycle state, data completeness, cutover timing and whether the current cycle should be completed in the legacy system or transferred under a controlled migration approach.

**Result:** Leadership could make a deliberate decision instead of creating a partially migrated cycle.

**SAP SuccessFactors Performance & Goals Example:** Active goals and performance forms were treated separately from historical records and migrated only when the target process could preserve their integrity.

**SME Probe:** When is it safer to complete a cycle in the legacy platform?

---

### HR-APH3-B11-Q07 — Mock Migration

**Interview Question:** Why are mock migrations important for Performance & Goals?

### STAR Answer
**Situation:** A first migration rehearsal revealed unexpected rating and employee-reference issues.

**Task:** I needed to make migration repeatable before production cutover.

**Action:** I performed multiple mock loads, reconciled source and target data, documented defects and refined transformation rules.

**Result:** The production migration became more predictable.

**SAP SuccessFactors Performance & Goals Example:** Mock migrations validated goal, rating, competency and employee-context transformations before final loading.

**SME Probe:** What should each mock migration improve?

---

### HR-APH3-B11-Q08 — Migration Reconciliation

**Interview Question:** How would you reconcile migrated performance data?

### STAR Answer
**Situation:** The team reported that migration was complete based only on successful load messages.

**Task:** I needed business-level reconciliation.

**Action:** I compared record counts, employee populations, key attributes, dates, ratings, goal statuses and selected source-to-target samples.

**Result:** Technical load success was separated from actual migration correctness.

**SAP SuccessFactors Performance & Goals Example:** Source legacy records were reconciled against target SuccessFactors goals and performance information.

**SME Probe:** Why is record count alone insufficient?

---

### HR-APH3-B11-Q09 — Migration Security

**Interview Question:** How would you protect sensitive performance information during migration?

### STAR Answer
**Situation:** Historical performance data was being extracted from a legacy platform and loaded into SuccessFactors.

**Task:** I needed to minimize privacy and security exposure.

**Action:** I restricted migration access, minimized extracts, secured transfer mechanisms, controlled temporary files, limited personnel access and defined disposal procedures.

**Result:** Sensitive employee information remained governed throughout migration.

**SAP SuccessFactors Performance & Goals Example:** Performance records were handled according to enterprise HR privacy and access controls during extraction and loading.

**SME Probe:** What should happen to temporary migration files after successful loading?

---

### HR-APH3-B11-Q10 — Cutover Planning

**Interview Question:** How would you create a cutover plan for Performance & Goals?

### STAR Answer
**Situation:** Multiple teams owned data, configuration, integrations and business readiness.

**Task:** I needed a single executable cutover sequence.

**Action:** I defined freeze activities, final extraction, transformation, load, reconciliation, integration activation, smoke testing, business validation, communications and go/no-go decisions with owners and timings.

**Result:** Cutover became coordinated and measurable.

**SAP SuccessFactors Performance & Goals Example:** Cutover covered employee-context validation, goal/performance data loading, workflow readiness and cycle activation.

**SME Probe:** Which cutover task should never run without an exit criterion?

---

### HR-APH3-B11-Q11 — Data Freeze

**Interview Question:** How would you manage a data freeze before Performance & Goals migration?

### STAR Answer
**Situation:** Employees and managers continued changing goals while final migration files were being prepared.

**Task:** I needed a stable source dataset.

**Action:** I defined the freeze scope, timing, business communication, exception process and reconciliation between the freeze extract and final production state.

**Result:** Delta risk was reduced.

**SAP SuccessFactors Performance & Goals Example:** Goal and performance changes were controlled during the final migration window according to the approved cutover strategy.

**SME Probe:** How do you handle a critical business change during a freeze?

---

### HR-APH3-B11-Q12 — Delta Migration

**Interview Question:** When would you use a delta migration for Performance & Goals?

### STAR Answer
**Situation:** A mock migration was completed several days before production cutover and source data continued to change.

**Task:** I needed to capture changes without repeating the entire migration.

**Action:** I defined the delta window, change-identification logic, sequencing and reconciliation between the initial load and final delta.

**Result:** The final migration remained current while reducing unnecessary rework.

**SAP SuccessFactors Performance & Goals Example:** New or changed goals and relevant performance information after the mock load were included through a controlled delta process.

**SME Probe:** What makes delta identification difficult?

---

### HR-APH3-B11-Q13 — Employee and Manager Mapping

**Interview Question:** How would you handle employee and manager identity mapping during migration?

### STAR Answer
**Situation:** Legacy employee IDs differed from SuccessFactors identifiers and manager relationships had changed.

**Task:** I needed accurate ownership and routing in the target system.

**Action:** I created authoritative cross-reference mappings, validated manager relationships against Employee Central and handled unresolved records through controlled exceptions.

**Result:** Performance records were associated with the correct employees and organizational context.

**SAP SuccessFactors Performance & Goals Example:** Employee Central identity and organizational data were used as the target reference for performance records.

**SME Probe:** Why is manager mapping especially important for performance data?

---

### HR-APH3-B11-Q14 — Rating Scale Transformation

**Interview Question:** How would you migrate ratings when the legacy and target rating scales differ?

### STAR Answer
**Situation:** The legacy platform used a five-level scale while the target design used different rating definitions.

**Task:** I needed to preserve historical meaning without creating false equivalence.

**Action:** I worked with HR to define approved semantic mappings, retained original context where required and documented transformations.

**Result:** Historical ratings remained interpretable without pretending the scales were identical.

**SAP SuccessFactors Performance & Goals Example:** Legacy ratings were mapped to approved SuccessFactors rating structures only where semantic equivalence was defensible.

**SME Probe:** What should you do when no defensible mapping exists?

---

### HR-APH3-B11-Q15 — Goal Transformation

**Interview Question:** How would you migrate goals when the target goal model is more structured than the legacy system?

### STAR Answer
**Situation:** Legacy goals were mostly free text while the target model required structured attributes.

**Task:** I needed to preserve useful information without inventing data.

**Action:** I mapped available values, transformed only approved attributes and identified fields that required defaulting, enrichment or historical preservation.

**Result:** Migrated goals remained useful while data integrity was protected.

**SAP SuccessFactors Performance & Goals Example:** Legacy goal descriptions were mapped into approved Goal Management structures without fabricating measures or weights.

**SME Probe:** Why is it dangerous to infer missing goal measures during migration?

---

### HR-APH3-B11-Q16 — Cutover Validation

**Interview Question:** What would you validate immediately after the final Performance & Goals migration?

### STAR Answer
**Situation:** The production load completed successfully according to the technical migration team.

**Task:** I needed business confirmation before opening the process.

**Action:** I validated employee populations, goal counts, critical historical records, ratings, manager relationships, permissions, workflows and representative end-to-end journeys.

**Result:** Business users could confirm that the migrated solution was fit for use.

**SAP SuccessFactors Performance & Goals Example:** HR and selected managers verified migrated goals and performance information before cycle activation.

**SME Probe:** Which validation sample would you prioritize first?

---

### HR-APH3-B11-Q17 — Migration Go/No-Go

**Interview Question:** How would you make the final migration go/no-go decision?

### STAR Answer
**Situation:** A few migration exceptions remained shortly before cutover.

**Task:** I needed to provide leadership with a defensible recommendation.

**Action:** I quantified affected records, business impact, privacy/security risk, workaround availability, reconciliation status and recovery options.

**Result:** Leadership could make an evidence-based go/no-go decision.

**SAP SuccessFactors Performance & Goals Example:** Migration readiness considered goals, ratings, employee references, forms, integrations and business validation.

**SME Probe:** What migration defect would automatically force a no-go?

---

### HR-APH3-B11-Q18 — Rollback and Recovery

**Interview Question:** How would you prepare recovery if a Performance & Goals cutover failed?

### STAR Answer
**Situation:** A production migration could potentially leave incomplete performance information.

**Task:** I needed to protect business continuity.

**Action:** I preserved source data and validated backups/baselines, defined rollback or restoration options, documented decision thresholds and prepared a contingency process for the active performance cycle.

**Result:** The organization had a controlled response to migration failure.

**SAP SuccessFactors Performance & Goals Example:** The last validated source and target states were retained as recovery references before activating the new performance process.

**SME Probe:** When is rollback more appropriate than corrective loading?

---

### HR-APH3-B11-Q19 — Cutover Communication

**Interview Question:** How would you communicate a Performance & Goals migration cutover to employees and managers?

### STAR Answer
**Situation:** Users needed to understand when the old system would stop and the new process would begin.

**Task:** I needed to prevent confusion during transition.

**Action:** I communicated freeze dates, access changes, what information would be available, what actions users needed to take, support channels and key milestones.

**Result:** Users had clearer expectations during the transition.

**SAP SuccessFactors Performance & Goals Example:** Communication covered access to SuccessFactors goals and performance forms, cycle timing and post-cutover actions.

**SME Probe:** What information should never be left ambiguous during cutover?

---

### HR-APH3-B11-Q20 — Migration as Transformation

**Interview Question:** How would you ensure migration supports the future Performance & Goals architecture rather than recreating the legacy system?

### STAR Answer
**Situation:** Stakeholders wanted every legacy field and workflow reproduced in SuccessFactors.

**Task:** I needed to protect the target-state design.

**Action:** I classified legacy information as required, useful, obsolete or incompatible, mapped only justified information to the target model and used the migration exercise to remove legacy complexity.

**Result:** Migration became a transformation activity rather than a technical copy exercise.

**SAP SuccessFactors Performance & Goals Example:** Standard SuccessFactors Goal Management and Performance Management structures were used as the target model instead of reproducing unnecessary legacy customizations.

**SME Probe:** What is the clearest sign that a migration has become a legacy-system replication exercise?

---

## Completion Standard

- **20 / 20 unique scenarios**
- **20 / 20 STAR answers**
- **20 / 20 SME probes**
- Stable IDs: **HR-APH3-B11-Q01 → HR-APH3-B11-Q20**
- Focus: migration strategy, data inventory, mapping, cleansing, historical data, active cycles, mock migration, reconciliation, security, cutover, freeze, delta migration, identity mapping, rating/goal transformation, validation, go/no-go, recovery, communication and transformation.
- Boundary maintained against AGL4 Succession & Development and ARP5 Compensation.

**Theme 11 complete: 20 / 20 scenarios.**
**Cumulative APH3 coverage: 11 / 22 themes = 220 / 440 scenarios.**
