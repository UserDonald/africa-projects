# Okovango ERP
## Epics, Personas & Affordance Criteria
*Product Backlog Foundation Document*

---

# Introduction / Overview

Okovango ERP is an all-in-one business management platform built for African growth markets, unifying Accounting & Billing, Human Resources, CRM & Sales, Project Management, Inventory, and Reporting & Analytics into a single connected system. It serves organizations across Eswatini, South Africa, Botswana, Namibia, Nigeria, Kenya and beyond, spanning government, higher education, financial services, healthcare, retail, hospitality, manufacturing and professional services.

This document defines the product's core Epics, the personas representing Okovango's target ideal customer profiles (ICPs), and the affordance criteria that connect each persona and epic to concrete system capabilities. Each persona is written to map onto one or more epics, and each epic carries an affordance statement plus user stories with acceptance criteria — providing the foundation for entity modeling, backlog grooming and sprint planning.

---

# Personas

The following six personas represent Okovango ERP's primary ICPs: the economic buyer, departmental module owners across finance, HR and operations, the technical administrator responsible for rollout, and an SME owner-operator. Each persona lists goals, behavioral considerations, tasks, an elaborate scenario, and the system affordances they rely on.

## Persona One: Executive Sponsor

**Name:** Kwame Boateng
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Kwame, 51, is the Managing Director of a mid-size organization operating across two African countries. He signs off on major software purchases and is accountable to a board for operational efficiency and cost control.

**Goals:**
- Get one org-wide view of finance, people, projects and inventory.
- Reduce software spend by consolidating disconnected tools.

**Behavioral Considerations:** Time-poor and decision-oriented; wants summary insight he can drill into, not raw data.

**Task:** Review real-time executive dashboards and approve the ERP rollout across departments.

**Elaborate Scenario:** Kwame is shown a live dashboard during a demo that consolidates revenue, headcount cost and project status across both countries. Convinced by the single source of truth, he approves a phased rollout starting with Finance and HR.

**Affordances:**
- Present consolidated, real-time KPI dashboards across all departments and entities.
- Allow drill-down from summary metrics into underlying records.
- Surface tool-consolidation and cost-saving reporting to justify investment.

## Persona Two: Finance Director

**Name:** Fatima Nkosi
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Fatima, 44, is the Finance Director at a regional bank. She owns financial reporting, budgeting and audit-readiness, and is under pressure to tighten compliance controls.

**Goals:**
- Consolidate invoicing, expenses and budgets into one auditable system.
- Produce accurate, real-time financial reports for regulators and the board.

**Behavioral Considerations:** Detail-driven and risk-averse; values accuracy, controls and a clear audit trail over speed.

**Task:** Manage invoices, expenses and budgets, and generate compliant financial reports.

**Elaborate Scenario:** Fatima replaces a patchwork of spreadsheets with Okovango's Accounting module. She sets department budgets, tracks actual-versus-budget in real time, and exports an audit-ready statement for the quarterly board pack in minutes.

**Affordances:**
- Create and manage invoices, expenses, payments and customer statements.
- Set budgets and view live actual-versus-budget reporting.
- Generate exportable, audit-ready financial reports from live data.

## Persona Three: HR Manager

**Name:** Thabo Mokoena
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Thabo, 38, is the HR Manager at a public university managing several hundred staff and faculty records, attendance and payroll information across multiple departments.

**Goals:**
- Maintain accurate staff records, roles and attendance in one place.
- Streamline payroll and performance tracking across departments.

**Behavioral Considerations:** Process-oriented and people-focused; frustrated by manual, spreadsheet-based HR admin.

**Task:** Track staff records, attendance, roles, payroll information and performance.

**Elaborate Scenario:** Thabo onboards a new faculty member through Okovango's HR module, assigns their role and permissions, and links attendance to payroll — eliminating the duplicate data entry that previously caused payroll errors.

**Affordances:**
- Maintain staff records, roles, permissions and attendance in a single profile.
- Link attendance and role data to payroll information.
- Record and review employee performance and training.

## Persona Four: Operations / Procurement Lead

**Name:** Grace Adeyemi
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Mrs.
**About Me:** Grace, 47, leads operations and procurement at a manufacturing firm. She is accountable for supplier relationships, stock levels and keeping input costs within budget.

**Goals:**
- Track products, stock levels and suppliers in real time.
- Keep purchasing costs visible and aligned with budgets.

**Behavioral Considerations:** Efficiency-driven and cost-conscious; needs live visibility to prevent stockouts and overspend.

**Task:** Manage inventory, suppliers and purchase movement, tied back to financial reporting.

**Elaborate Scenario:** Grace uses the Inventory module to monitor stock against reorder points, links suppliers to products, and sees purchase costs flow directly into finance reporting — giving her an accurate real-time cost picture for production planning.

**Affordances:**
- Add products with purchase price, sales price, category and units.
- Track stock levels and warehouse movement in real time.
- Link supplier records to products and feed costs into financial reporting.

## Persona Five: Systems Administrator

**Name:** Lindiwe Dube
**Pronouns:** She/Her
**Gender:** Female
**Preferred Title:** Ms.
**About Me:** Lindiwe, 33, is the IT / Systems Administrator responsible for configuring Okovango, managing user access and driving adoption across the organization.

**Goals:**
- Configure roles, permissions and departments cleanly.
- Ensure data integrity and a smooth rollout across teams.

**Behavioral Considerations:** Security-minded and methodical; wants granular control and a predictable implementation path.

**Task:** Set up role-based access, import data, and manage the discovery-to-launch rollout.

**Elaborate Scenario:** Lindiwe defines roles and per-module permissions, bulk-imports staff, customers and inventory during data collection, tests workflows, and gates go-live until each department is trained and ready.

**Affordances:**
- Create roles and assign granular, per-module permissions.
- Bulk-import staff, customer and inventory data with validation.
- Move the organization through discovery, data collection, training and launch with tracked status.

## Persona Six: SME Owner-Operator

**Name:** Daniel Kamau
**Pronouns:** He/Him
**Gender:** Male
**Preferred Title:** Mr.
**About Me:** Daniel, 36, owns a growing multi-store retail business. He runs sales, stock and cash from several disconnected apps and wants to scale without adding administrative chaos.

**Goals:**
- See customers, sales, stock and cash flow in one platform.
- Add modules and locations as the business grows.

**Behavioral Considerations:** Hands-on and growth-focused; averse to high upfront cost and long, complex setups.

**Task:** Manage CRM, sales, inventory and billing from a single connected system.

**Elaborate Scenario:** Daniel starts with CRM, Inventory and Accounting, tracks leads through to won deals that flow into billing, and later enables Project Management as he opens a third store — all under one account.

**Affordances:**
- Capture leads and convert them to deals and invoices without re-entry.
- Track products, stock and sales activity across multiple stores.
- Enable additional modules and add new locations as the business scales.

---

# Epics, Affordances & User Stories

Each epic below carries an affordance statement describing what the platform enables, followed by user stories tied to the personas above and the acceptance criteria that define done. Together these form the affordance criteria that link every persona and ICP to concrete Okovango ERP capabilities.

## Epic 1: Onboarding & Implementation (Lindiwe)

**Affordance:** Guides an organization from discovery through data collection, training and launch, so teams understand the workflow, data and adoption plan before go-live.

**User Story 1 (Systems Administrator):** Move the organization through a structured discovery-to-launch rollout.

**Acceptance Criteria:**
- The system should track rollout status across discovery, data collection, training and launch phases.
- The system should allow go-live to be gated until workflows are tested and users are trained.

**User Story 2 (Systems Administrator):** Bulk-import existing staff, customer and inventory data.

**Acceptance Criteria:**
- The system should support bulk import of staff, customer and inventory records.
- The system should validate imported data and report errors before committing.

## Epic 2: Identity, Roles & Permissions (Lindiwe)

**Affordance:** Provides a central role-based access layer governing what every user can see and do across all modules, protecting sensitive data.

**User Story 1 (Systems Administrator):** Create roles and assign granular per-module permissions.

**Acceptance Criteria:**
- The system should allow the creation of roles with per-module permission settings.
- The system should restrict each user to only the data and actions their role permits.
- The system should apply permission changes immediately across all modules.

## Epic 3: Dashboards, Reporting & Analytics (Kwame)

**Affordance:** Turns operational data into real-time dashboards, KPIs and visual reports, giving decision-makers cross-department visibility.

**User Story 1 (Executive Sponsor):** View real-time KPI dashboards across departments and entities.

**Acceptance Criteria:**
- The system should present live KPI dashboards filterable by department, date and entity.
- The user should be able to drill from a summary metric into the underlying records.

**User Story 2 (Executive Sponsor):** Generate and export visual reports for the board.

**Acceptance Criteria:**
- The system should generate visual reports from live operational data.
- The user should be able to export or share reports without leaving the platform.

## Epic 4: Accounting & Billing (Fatima)

**Affordance:** Controls invoicing, expenses, budgets, payments and financial reporting from one connected dashboard.

**User Story 1 (Finance Director):** Create invoices, log expenses and record payments against a customer.

**Acceptance Criteria:**
- The system should allow creation of invoices and logging of expenses and payments.
- The system should link financial transactions to the correct customer and statement.

**User Story 2 (Finance Director):** Set budgets and produce audit-ready financial reports.

**Acceptance Criteria:**
- The system should allow budgets to be set and show actual-versus-budget in reporting.
- The system should generate exportable financial reports and customer statements from live data.

## Epic 5: Human Resources & Payroll (Thabo)

**Affordance:** Manages employee records, attendance, roles, payroll information and performance with minimal manual admin.

**User Story 1 (HR Manager):** Maintain staff records, roles and attendance in one profile.

**Acceptance Criteria:**
- The system should store staff records, roles, permissions and attendance in a single profile.
- The system should link attendance and role data to payroll information.

**User Story 2 (HR Manager):** Record and review employee performance and training.

**Acceptance Criteria:**
- The system should allow performance and training records to be logged per employee.
- The system should let managers review performance history for their team.

## Epic 6: CRM & Deal Management (Daniel)

**Affordance:** Tracks leads, customers, deals, estimates and contracts through a complete sales pipeline, flowing into billing.

**User Story 1 (SME Owner-Operator):** Capture leads and move them through pipeline stages to won deals.

**Acceptance Criteria:**
- The system should allow leads to be captured and converted to deals with pipeline stages.
- The system should generate estimates and contracts from customer and deal records.

**User Story 2 (SME Owner-Operator):** Convert won deals into invoices without re-entering data.

**Acceptance Criteria:**
- The system should allow a won deal to flow into billing without re-keying data.
- The system should keep customer records consistent between CRM and Accounting.

## Epic 7: Project Management (Daniel)

**Affordance:** Organizes tasks, deadlines, priorities, timesheets and progress so projects stay on time and on budget.

**User Story 1 (SME Owner-Operator):** Create and track tasks on a Kanban board with priorities and deadlines.

**Acceptance Criteria:**
- The system should allow tasks to be created with priorities, deadlines and a Kanban view.
- The system should track project progress against schedule and budget.

**User Story 2 (SME Owner-Operator):** Log time against tasks and projects.

**Acceptance Criteria:**
- The system should allow team members to log timesheets against tasks and projects.
- The system should roll logged time up into project progress and billing.

## Epic 8: Inventory & Supply Management (Grace)

**Affordance:** Tracks products, stock levels, purchase and sales prices, suppliers and warehouse movement in real time.

**User Story 1 (Operations / Procurement Lead):** Add products and track stock levels against reorder points.

**Acceptance Criteria:**
- The system should allow products to be added with purchase price, sales price, category and units.
- The system should update stock levels on movement and show them in real time.

**User Story 2 (Operations / Procurement Lead):** Link suppliers to products and feed costs into finance.

**Acceptance Criteria:**
- The system should link supplier records to products and purchasing.
- The system should feed purchase costs into financial reporting.

## Epic 9: Scalability & Multi-Entity Expansion (Kwame)

**Affordance:** Lets the organization add modules, departments, entities and countries under one account as it grows, using a shared business data layer.

**User Story 1 (Executive Sponsor):** Enable additional modules without disrupting existing data.

**Acceptance Criteria:**
- The system should allow new modules to be enabled against the same central data layer.
- The system should preserve existing records and permissions when modules are added.

**User Story 2 (Executive Sponsor):** Add new departments, entities or countries under one account.

**Acceptance Criteria:**
- The system should support multiple departments, entities and countries under one account.
- The system should scope data and reporting by entity and country.