# Project 1: Mini Compliance Program (ISO 27001 / NIST)

## 🎯 Objective
Act as a compliance officer for a fictional startup. Build a mini ISO 27001:2022 compliance program by mapping controls, identifying gaps, assigning owners, and documenting the compliance scope.

## 🏢 Fictional Company: NovaCloud AI Solutions
- **Business:** AI-powered analytics for e-commerce
- **Employees:** 50
- **Assets in scope:**
  - AWS cloud (2 EC2 instances, 1 S3 bucket with customer data)
  - 50 company laptops (Windows & Mac)
  - SaaS tools: Google Workspace, Slack, GitHub, Jira
  - Customer database (encrypted)

## 📋 Compliance Framework
**ISO 27001:2022** (Annex A controls) – preparing for certification audit readiness.

## 📊 Deliverables
1. [ISO 27001 Control Matrix (Excel)](./assets/iso27001-control-matrix.xlsx)
2. [1-Page Scope & Gap Summary (PDF)](./assets/scope-summary.pdf)

## 🔍 Control Matrix Preview (15 Controls)

| Control ID | Control Title | Status | Owner | Action Needed |
|------------|---------------|--------|-------|----------------|
| A.5.1 | Information security policies | Partially | CISO | Draft policy by Q3 |
| A.5.2 | Segregation of duties | Not implemented | CTO | Map roles, split admin/dev |
| A.6.5 | Access control | Implemented | IT Manager | N/A – maintain monthly |
| A.7.4 | Physical security monitoring | N/A | N/A | Document as out of scope |
| A.8.1 | Asset inventory | Partially | IT Manager | Complete SaaS asset list |
| A.8.7 | Removable media | Not implemented | IT Manager | Disable USB ports |
| A.8.8 | Equipment security | Planned | IT Manager | Create disposal procedure |
| A.8.9 | Clear desk & screen | Partially | HR | Training + spot checks |
| A.9.4 | Password management | Implemented | CISO | Verify every 6 months |
| A.9.5 | Multi-factor authentication | Implemented | CISO | Enforce on all SaaS |
| A.12.1 | Operational procedures | Not implemented | CTO | Create change control |
| A.12.4 | Logging & monitoring | Partially | DevOps | Enable CloudTrail + weekly review |
| A.12.6 | Vulnerability management | Planned | DevOps | Schedule monthly scans |
| A.13.1 | Network controls | Implemented | DevOps | Review quarterly |
| A.16.1 | Incident management | Planned | CISO | Draft IR plan |

*Full matrix available in the assets folder*

## 📝 Gap Analysis Summary
- **Total controls reviewed:** 15
- **Fully implemented:** 7
- **Partially implemented:** 3
- **Not implemented / Planned:** 5
- **Overall compliance gap:** 40%

### Top 3 Risks from Gaps
| Risk | Impact | Mitigation |
|------|--------|-------------|
| No change management (A.12.1) | Unapproved system changes | Create change control process by Q2 |
| No vulnerability scanning (A.12.6) | Unpatched exploits | Schedule monthly scans starting next month |
| No incident response plan (A.16.1) | Delayed breach response | Draft IR plan and tabletop test |

## 🚀 How I Built This Project
1. Downloaded ISO 27001:2022 Annex A control list
2. Created a spreadsheet with Control ID, Title, Status, Owner, Action Needed
3. Mapped 15 controls to NovaCloud's assets and environment
4. Identified gaps and assigned remediation owners
5. Wrote a 1-page scope summary with next steps

## 🧠 Skills Demonstrated
- Framework alignment (ISO 27001)
- Control evaluation & gap analysis
- Risk-based prioritization
- Compliance documentation

## 📎 Files in This Project
