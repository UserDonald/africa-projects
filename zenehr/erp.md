# ZenEHR
## Epics, Personas & Affordance Criteria
*Product Backlog Foundation Document*

---

# Introduction / Overview

ZenEHR is a cloud-based Electronic Health Record platform that helps clinics, hospitals, health networks, and public health systems across Africa and emerging markets deliver safer, faster, and more connected care. It unifies patient records, e-prescriptions, analytics, integrations, security and pharmacy management into one platform — engineered for low-bandwidth and offline environments, multi-language teams, and local data-residency compliance, and scalable from a single clinic to a national system.

This document defines the product's core Epics, the personas representing ZenEHR's target ideal customer profiles (ICPs) across every level of care, and the affordance criteria that connect each persona and epic to concrete system capabilities. Each persona is written to map onto one or more epics, and each epic carries an affordance statement plus user stories with acceptance criteria — providing the foundation for entity modeling, backlog grooming and sprint planning.

---

# Personas

The following six personas represent ZenEHR's primary ICPs: the frontline clinician, the pharmacy operator, the facility/network administrator, the public-health decision-maker, the patient, and the technical/compliance owner. Each persona lists goals, behavioral considerations, tasks, an elaborate scenario, and the system affordances they rely on.

## Persona One: Frontline Clinician

**Name:** Dr. Thandi Dlamini
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Dr.
**About Me:** Thandi, 41, is a physician and Medical Superintendent at a busy regional hospital. She sees a high volume of patients and needs complete, current clinical information at the point of care.

**Goals:**
- Access complete patient histories, vitals, allergies and medications quickly.
- Spend less time on paperwork and more time delivering care.

**Behavioral Considerations:** Time-pressured and safety-focused; distrusts fragmented paper files and values fast, reliable access to accurate records.

**Task:** Review patient history, record notes, order labs and issue prescriptions during a visit.

**Elaborate Scenario:** Thandi opens a patient's unified record during a consultation, reviews prior visits and current medications, flags an allergy conflict, and sends an e-prescription straight to the pharmacy — all without leaving the record.

**Affordances:**
- Present complete patient histories, vitals, allergies, medications and notes at the point of care.
- Allow clinical notes, lab requests and referrals to be recorded during a visit.
- Send electronic prescriptions directly from the patient record to the pharmacy.

## Persona Two: Pharmacy Operator

**Name:** Kwame Mensah
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Kwame, 39, manages a pharmacy connected to a clinic network. He fulfills prescriptions, controls stock, and is accountable for dispensing safety and compliance.

**Goals:**
- Receive and fulfill clinician prescriptions accurately and quickly.
- Keep medication stock, refills and controlled items under control.

**Behavioral Considerations:** Detail-driven and compliance-minded; needs a clear audit trail and reliable stock visibility to avoid shortages and errors.

**Task:** Review incoming prescriptions, dispense medication, track refills and manage inventory.

**Elaborate Scenario:** Kwame receives an electronic prescription linked to the patient's clinical history, checks stock, dispenses and records the fulfillment, logs a substitution, and updates inventory — with every action captured in the audit trail.

**Affordances:**
- Receive, review and fulfill prescriptions linked to the patient's clinical history.
- Track medication dispensing, refills and substitutions.
- Show inventory levels for medicines, consumables and controlled items with audit trails.

## Persona Three: Facility / Network Administrator

**Name:** Grace Achieng
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Mrs.
**About Me:** Grace, 48, is the administrator for a health network spanning several clinics and a hospital. She is accountable for facility performance, staffing workflows and connected patient visibility across sites.

**Goals:**
- Connect multiple facilities around shared, unified patient records.
- Monitor facility performance and reporting across the network.

**Behavioral Considerations:** Operationally focused and coordination-oriented; frustrated by fragmented files and siloed facilities.

**Task:** Manage appointments, queues, role permissions and cross-facility patient visibility.

**Elaborate Scenario:** Grace configures appointment queues and follow-ups across three clinics, ensures a patient moving between facilities keeps their full history, and reviews facility performance dashboards to balance workload.

**Affordances:**
- Connect multiple facilities through shared records and unified patient visibility.
- Manage appointments, queues, follow-ups and role permissions across sites.
- Present facility performance dashboards and operational reporting.

## Persona Four: Public Health Decision-Maker

**Name:** Dr. Samuel Okonkwo
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Dr.
**About Me:** Samuel, 53, leads a digital health program at a Ministry of Health / NGO. He is responsible for deploying secure regional health infrastructure and turning data into policy insight.

**Goals:**
- Deploy secure national or regional digital health infrastructure.
- Turn population health data into reporting and policy decisions.

**Behavioral Considerations:** Strategic and outcomes-driven; prioritizes data security, residency, scale and reliable analytics over feature breadth.

**Task:** Roll out ZenEHR across regions and monitor aggregate health outcomes and facility performance.

**Elaborate Scenario:** Samuel deploys ZenEHR across a region with local data-residency compliance, then uses aggregated analytics to track patient outcomes and facility performance, informing where to direct resources.

**Affordances:**
- Deploy secure regional or national digital health infrastructure with data-residency options.
- Provide aggregate analytics on patient outcomes, reporting and facility performance.
- Scale from single clinics to national systems without re-platforming.

## Persona Five: Patient

**Name:** Amara Banda
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Amara, 34, is a patient who receives care across more than one facility. She wants continuity of care and safe access to her own medication and clinical history.

**Goals:**
- Keep critical history and medication details as she moves between facilities.
- Receive safe, coordinated care without repeating tests or losing records.

**Behavioral Considerations:** Wants continuity and safety; relies on care teams having her accurate, up-to-date information.

**Task:** Move between facilities while her record stays complete and available to authorized teams.

**Elaborate Scenario:** Amara is referred from a clinic to a hospital. Her full record — history, medications, clinical context — is available to the hospital's authorized team in real time, so no critical detail is lost in the transition.

**Affordances:**
- Keep patient records securely synced across clinics, hospitals, labs and pharmacies.
- Preserve history, medication details and clinical context during transfers between facilities.
- Give authorized care teams real-time access to current patient information across locations.

## Persona Six: IT / Compliance Owner

**Name:** Lindiwe Ndlovu
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Lindiwe, 35, is the IT and compliance lead responsible for deploying ZenEHR, managing access controls, and satisfying data-protection and audit requirements.

**Goals:**
- Configure role-based access and encryption cleanly.
- Ensure records, integrations and data residency meet compliance requirements.

**Behavioral Considerations:** Security-minded and methodical; needs granular control, audit trails and dependable operation in low-bandwidth settings.

**Task:** Set up role permissions, integrations and compliance controls, and support offline-capable deployment.

**Elaborate Scenario:** Lindiwe defines role-based permissions, connects labs, billing and insurance systems through integrations, verifies encrypted records and audit trails, and confirms the deployment works reliably in low-bandwidth and offline conditions.

**Affordances:**
- Configure role-based permissions, encryption and audit trails.
- Connect labs, billing, insurance, pharmacies and legacy systems through integrations.
- Support low-bandwidth and offline operation with local data-residency options.

---

# Epics, Affordances & User Stories

Each epic below carries an affordance statement describing what the platform enables, followed by user stories tied to the personas above and the acceptance criteria that define done. Together these form the affordance criteria that link every persona and ICP to concrete ZenEHR capabilities.

## Epic 1: Patient Records & Clinical Documentation (Thandi)

**Affordance:** Gives clinicians complete patient histories, vitals, allergies, medications, notes and treatment plans at the point of care.

**User Story 1 (Frontline Clinician):** View a complete patient history during a visit.

**Acceptance Criteria:**
- The system should present the patient's history, vitals, allergies and medications in one record.
- The system should flag allergy or medication conflicts to the clinician.

**User Story 2 (Frontline Clinician):** Record clinical notes, lab requests and referrals during a visit.

**Acceptance Criteria:**
- The system should allow notes, lab requests and referrals to be recorded against the visit.
- The system should update the patient record immediately and preserve visit history.

## Epic 2: e-Prescriptions (Thandi)

**Affordance:** Lets clinicians send prescriptions electronically to pharmacies and manage medication records from the patient record.

**User Story 1 (Frontline Clinician):** Send an electronic prescription to the pharmacy.

**Acceptance Criteria:**
- The system should allow a prescription to be created and sent electronically from the patient record.
- The system should link the prescription to the patient's clinical and medication history.

**User Story 2 (Frontline Clinician):** Manage a patient's medication records.

**Acceptance Criteria:**
- The system should show current and past medications on the patient record.
- The system should reflect dispensing and refill status back to the clinician.

## Epic 3: Pharmacy Management (Kwame)

**Affordance:** Supports pharmacies with prescription fulfillment, dispensing, refills, substitution tracking and inventory, connected to the patient record.

**User Story 1 (Pharmacy Operator):** Receive, review and fulfill prescriptions linked to the patient record.

**Acceptance Criteria:**
- The system should deliver incoming prescriptions linked to the patient's clinical history.
- The system should record dispensing, refills and substitutions against the prescription.

**User Story 2 (Pharmacy Operator):** Track medication stock and controlled items.

**Acceptance Criteria:**
- The system should show inventory levels for medicines, consumables and controlled items.
- The system should track stock movement, shortages and replenishment needs.

## Epic 4: Single Source of Truth & Care Continuity (Amara)

**Affordance:** Securely syncs patient records across facilities so authorized care teams access the right information when it matters most.

**User Story 1 (Patient):** Keep a complete record when moving between facilities.

**Acceptance Criteria:**
- The system should sync patient records across clinics, hospitals, labs and pharmacies.
- The system should preserve history, medications and clinical context during transfers.

**User Story 2 (Facility / Network Administrator):** Give authorized teams real-time cross-location access.

**Acceptance Criteria:**
- The system should provide authorized teams real-time access to current patient information across locations.
- The system should enforce secure access controls on cross-facility data.

## Epic 5: Clinic Portal & Workflow Management (Grace)

**Affordance:** Provides a simple, secure portal to manage appointments, patients, prescriptions, visits, notes and referrals from one place.

**User Story 1 (Facility / Network Administrator):** Manage appointments, queues and follow-ups.

**Acceptance Criteria:**
- The system should allow appointments, queues and follow-ups to be scheduled and tracked.
- The system should support patient registration and visit history.

**User Story 2 (Facility / Network Administrator):** Run prescription, referral and lab request workflows.

**Acceptance Criteria:**
- The system should support prescription, referral and lab request workflows from the portal.
- The system should route each workflow to the correct role or facility.

## Epic 6: Analytics & Reporting (Samuel)

**Affordance:** Turns clinical and operational data into dashboards for patient outcomes, facility performance and insights.

**User Story 1 (Public Health Decision-Maker):** Monitor aggregate patient outcomes and facility performance.

**Acceptance Criteria:**
- The system should present dashboards for patient outcomes, reporting and facility performance.
- The user should be able to view aggregate data across facilities and regions.

**User Story 2 (Facility / Network Administrator):** Generate reporting for a facility or network.

**Acceptance Criteria:**
- The system should generate reports from live clinical and operational data.
- The user should be able to filter reporting by facility, date and outcome.

## Epic 7: Security, Roles & Compliance (Lindiwe)

**Affordance:** Protects records with role-based permissions, encryption, audit trails and compliance controls.

**User Story 1 (IT / Compliance Owner):** Configure role-based permissions and encryption.

**Acceptance Criteria:**
- The system should allow role-based permissions to be created and assigned.
- The system should encrypt records and restrict each user to permitted data and actions.

**User Story 2 (IT / Compliance Owner):** Maintain audit trails for compliance.

**Acceptance Criteria:**
- The system should record audit trails of access and clinical/dispensing actions.
- The system should support compliance and data-residency requirements.

## Epic 8: Integrations (Lindiwe)

**Affordance:** Connects ZenEHR with labs, billing systems, pharmacies, insurance and legacy systems.

**User Story 1 (IT / Compliance Owner):** Connect external systems to ZenEHR.

**Acceptance Criteria:**
- The system should support integration with labs, billing, insurance, pharmacies and legacy systems.
- The system should keep integrated data consistent with the patient record.

## Epic 9: Africa-Ready Deployment & Scale (Samuel)

**Affordance:** Runs in low-bandwidth and offline environments, supports multiple languages and data residency, and scales from a single clinic to national systems.

**User Story 1 (Public Health Decision-Maker):** Deploy across regions with local compliance.

**Acceptance Criteria:**
- The system should support local compliance and data-residency options.
- The system should scale from single clinics to regional and national systems.

**User Story 2 (IT / Compliance Owner):** Operate reliably in low-bandwidth and offline settings.

**Acceptance Criteria:**
- The system should function in low-bandwidth and offline environments.
- The system should provide multi-language support for diverse teams.