# Role Interaction Matrix

This matrix summarizes how the five new roles interact with the three existing OctoAcme roles (Developers, Product Managers, Project Managers).

---

## Matrix

| New Role | Developers | Product Managers | Project Managers |
|---|---|---|---|
| **Project Sponsor** | Receives high-level progress updates; unblocks resource or priority conflicts | Aligns on product strategy and business value; approves major scope decisions | Receives milestone reports and escalations; approves project charter and budget |
| **Change Manager** | Communicates approved change requests and updated scope; coordinates rework planning | Shares change impact assessments; ensures changes align with product priorities | Submits changes through the Change Manager; receives change log updates and risk assessments |
| **QA Lead / Test Manager** | Reviews acceptance criteria with developers; verifies bug fixes and regression test results | Aligns test coverage with product requirements and success metrics; confirms acceptance criteria | Reports on quality status and release readiness; flags test-blocking issues as risks |
| **Release Manager** | Coordinates deployment readiness and release branching with developers | Confirms feature readiness and release scope with the Product Manager; distributes release notes | Aligns release dates with project milestones; escalates go/no-go decisions |
| **Stakeholder** | Provides UAT feedback on implemented features; reports usability issues | Supplies business requirements and priorities; validates solutions against department needs | Surfaces constraints, dependencies, and risks from their area; participates in status reviews |

---

## Interaction Patterns

### Project Sponsor ↔ Project Managers
The Project Sponsor and Project Manager maintain a close communication loop. The Project Manager provides regular status updates, escalates risks and decisions requiring executive input, and secures sponsor sign-off on milestones. The sponsor provides strategic direction and budget protection.

### Change Manager ↔ Project Managers
All change requests flow through the Change Manager before being actioned. The Project Manager coordinates with the Change Manager to log, assess, and communicate changes. The Change Manager maintains the change control register and notifies the Project Manager of approvals and rejections.

### QA Lead / Test Manager ↔ Developers
The QA Lead and Developers collaborate closely during sprint execution. Developers implement fixes and features to meet acceptance criteria defined or verified by the QA Lead. The QA Lead verifies fixes and reports defect status back to the team.

### Release Manager ↔ Project Managers and QA Lead
The Release Manager coordinates with the Project Manager on release scheduling and milestone alignment. The Release Manager works with the QA Lead to confirm quality gates are met before a go/no-go decision is called.

### Stakeholders ↔ Product Managers
Stakeholders provide input and requirements that Product Managers translate into backlog items and acceptance criteria. Product Managers ensure stakeholder needs are represented in the roadmap and communicate product decisions back to stakeholders.
