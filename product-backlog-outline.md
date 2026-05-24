# Product Backlog Outline: Enterprise Mainframe Product Triage Dashboard

## 1. Product Vision
The Enterprise Mainframe Product Triage Dashboard helps Product Managers evaluate customer requests for mature enterprise software products where operational continuity, regulatory reporting, modernization pressure, and retention risk must be balanced carefully.

## 2. Product Goals
- Help PMs prioritize customer requests using consistent criteria
- Make renewal and retention risk visible
- Highlight regulatory and audit-sensitive requests
- Identify modernization-linked opportunities
- Support better conversations with Engineering, Sales, Support, Architecture, and Product Owners
- Provide a clear visual artifact for roadmap tradeoff discussions

## 3. Target Users
- **Product Manager:** Needs a consistent, transparent way to compare requests and justify roadmap tradeoffs.
- **Product Owner:** Needs clear backlog structure, acceptance criteria, and priority context for delivery planning.
- **Engineering Lead:** Needs effort visibility and business context to align sequencing with technical constraints.
- **Support Lead:** Needs recurring customer friction surfaced as structured product opportunities.
- **Sales / Account Team:** Needs retention and adoption framing for customer conversations and renewal planning.
- **Architecture Team:** Needs modernization-linked demand visibility to align technical strategy.
- **Executive Stakeholder:** Needs concise risk and priority summaries to support governance decisions.

## 4. Core User Problems
- Customer requests arrive from multiple channels and lack consistent prioritization
- High-value customer issues can be hidden inside support noise
- Regulatory and audit-related requests need visibility
- Modernization requests are hard to compare against maintenance work
- Engineering needs clearer requirements and tradeoffs
- Sales needs better language for customer adoption and retention
- Leadership needs a simple view of roadmap pressure

## 5. Product Themes / Epics
### Epic 1: Customer Request Intake
**Purpose:** Capture fictional customer requests in a consistent structure.

**User stories:**
- As a Product Manager, I want to capture customer type, request summary, business driver, and affected stakeholders so that I can understand the request context.
- As a Support Lead, I want repeated support issues to be visible as product candidates so that recurring friction can be addressed.
- As a Sales partner, I want renewal-sensitive requests flagged so that account risk is visible.

**Acceptance criteria:**
- Request has customer type, request summary, business driver, risk if ignored, affected stakeholders, and PM notes
- Request can be categorized by regulatory impact, renewal risk, modernization value, and severity
- Request is displayed in the UI table

### Epic 2: Triage Scoring Model
**Purpose:** Score requests using PM-relevant prioritization criteria.

**User stories:**
- As a Product Manager, I want to score requests by renewal risk, regulatory impact, customer severity, revenue impact, engineering effort, support burden reduction, adoption potential, modernization value, and strategic fit.
- As an Engineering Lead, I want engineering effort shown clearly so that product decisions account for delivery cost.
- As an Executive Stakeholder, I want high-risk items surfaced quickly so that retention and compliance risks are visible.

**Acceptance criteria:**
- Each request includes 1–5 scores for core prioritization criteria
- Priority is calculated or assigned as P0, P1, P2, or P3
- Scoring definitions are documented
- High regulatory or high renewal-risk items are visually distinguishable

### Epic 3: Prioritization Dashboard UI
**Purpose:** Give recruiters and interviewers a visual way to understand the product thinking.

**User stories:**
- As a recruiter, I want to see a clear dashboard so that I can quickly understand the candidate’s product judgment.
- As a hiring manager, I want to see how requests are prioritized so that I can assess PM thinking.
- As a PM, I want to filter requests by priority, regulatory impact, renewal risk, and modernization value so that roadmap tradeoffs are easier to discuss.

**Acceptance criteria:**
- Dashboard includes title and subtitle
- Dashboard includes overview cards
- Dashboard includes customer request table
- Dashboard includes filters
- Dashboard includes request detail panel
- Dashboard includes scoring explanation
- Dashboard includes public portfolio disclaimer

### Epic 4: Request Detail and PM Recommendation
**Purpose:** Show the reasoning behind each prioritization decision.

**User stories:**
- As a Product Manager, I want to select a request and see why it matters, the risk if ignored, suggested PM response, and Engineering notes.
- As an Engineering Lead, I want enough context to understand the customer problem without needing to read a full support ticket.
- As a Sales partner, I want a concise PM recommendation that can support customer conversations.

**Acceptance criteria:**
- Selecting a request updates the detail panel
- Detail panel shows why it matters
- Detail panel shows risk if ignored
- Detail panel shows suggested PM response
- Detail panel shows Engineering/Product Owner notes
- Detail panel shows adoption or retention impact

### Epic 5: Adoption and Retention View
**Purpose:** Connect product decisions to customer adoption and retention.

**User stories:**
- As a PM, I want to identify requests tied to renewal or retention risk so that I can prioritize customer trust.
- As a Sales partner, I want to understand which roadmap items support adoption so that I can communicate value to customers.
- As an Executive Stakeholder, I want a summary of P0/P1 items tied to customer retention.

**Acceptance criteria:**
- Dashboard includes count of high renewal-risk requests
- Dashboard includes count of P0/P1 items
- Requests include adoption or retention impact
- Prioritization model explains how retention risk affects priority

### Epic 6: Regulatory and Audit Impact View
**Purpose:** Make compliance-sensitive customer needs visible.

**User stories:**
- As a PM, I want to flag requests with regulatory or audit impact so that compliance-sensitive work is not treated as ordinary enhancement work.
- As a customer-facing stakeholder, I want to explain why regulatory reporting continuity matters.
- As an Engineering Lead, I want to know when a request has audit or reporting implications.

**Acceptance criteria:**
- Requests include regulatory or audit impact score
- Dashboard can filter regulatory-impact requests
- Detail panel explains regulatory risk where relevant
- Prioritization model weighs regulatory impact heavily

### Epic 7: Modernization Without Disruption
**Purpose:** Show how the product supports modernization while protecting existing workflows.

**User stories:**
- As a PM, I want to identify requests that support modernization so that roadmap planning aligns with customer transformation needs.
- As an Architecture partner, I want modernization-linked requests visible so that technical strategy can be aligned with customer needs.
- As a customer stakeholder, I want modernization planning to reduce disruption risk.

**Acceptance criteria:**
- Requests include modernization value score
- Dashboard can filter modernization-linked requests
- Product narrative emphasizes modernization without disruption
- Sample requests include migration assessment, dependency visibility, and legacy workflow continuity

### Epic 8: Interview and Recruiter Storytelling
**Purpose:** Make the project easy to explain in an interview.

**User stories:**
- As a candidate, I want a 30-second explanation so that I can introduce the project quickly.
- As a candidate, I want resume bullets so that I can reference the artifact professionally.
- As a recruiter, I want to understand why the project is relevant to the role.

**Acceptance criteria:**
- interview-talking-points.md includes 30-second explanation
- interview-talking-points.md includes 60-second explanation
- interview-talking-points.md includes resume bullets
- README explains what the project demonstrates

## 6. MVP Scope
- Static UI dashboard
- 8 fictional customer requests
- Request scoring model
- Priority labels P0/P1/P2/P3
- Filters
- Detail panel
- Product backlog outline
- Interview talking points
- Public portfolio disclaimer

## 7. Out of Scope
- Backend
- Authentication
- Database
- Real customer data
- Real Broadcom data
- Proprietary product roadmap
- AI-generated roadmap decisions without human review
- Production deployment requirements
- Enterprise integrations

## 8. Sample Backlog Table
| Epic | User Story | Priority | Reason | Status |
|---|---|---|---|---|
| Customer Request Intake | Define intake schema for customer type, driver, risk, and notes | P0 | Needed to normalize triage input | Complete |
| Customer Request Intake | Add recurring-support-issue indicator | P1 | Surfaces hidden product debt | Planned |
| Triage Scoring Model | Document 1–5 scoring criteria and definitions | P0 | Enables consistent prioritization | Complete |
| Triage Scoring Model | Add weighted formula with manual PM override | P1 | Balances rigor and PM judgment | In Progress |
| Prioritization Dashboard UI | Build summary cards for risk and priority | P0 | Enables 60-second stakeholder comprehension | Complete |
| Prioritization Dashboard UI | Add table filters for P0/P1, regulatory, renewal, modernization | P1 | Improves tradeoff discussions | Complete |
| Request Detail & PM Recommendation | Implement request detail panel with rationale | P0 | Makes decisions auditable and explainable | Complete |
| Request Detail & PM Recommendation | Add PM response templates by scenario | P2 | Speeds customer-facing communication | Planned |
| Adoption & Retention View | Show high renewal-risk and P0/P1 counts | P1 | Connects prioritization to retention | Complete |
| Regulatory & Audit Impact | Flag and filter compliance-sensitive items | P0 | Reduces compliance exposure | Complete |
| Modernization Without Disruption | Tag migration/compatibility requests | P1 | Aligns modernization with continuity | In Progress |
| Interview Storytelling | Publish 30/60-second explanation + resume bullets | P1 | Improves recruiter readability | Complete |

## 9. Prioritization Method
Priorities are based on weighted and discussable inputs:
- Renewal / retention risk
- Regulatory or audit impact
- Customer severity
- Revenue impact
- Engineering effort
- Modernization value
- Support burden reduction
- Adoption potential
- Strategic fit
- Number of customers affected

## 10. Success Metrics
- Requests consistently scored
- P0/P1 items clearly visible
- Regulatory-impact requests identifiable
- Renewal-risk requests identifiable
- PM recommendations documented
- Dashboard understandable within 60 seconds
- Recruiter can understand the product judgment without a live walkthrough

## 11. Risks and Mitigations
- **Risk:** Overcomplicating the prototype  
  **Mitigation:** Keep static data and simple UI
- **Risk:** Appearing to claim proprietary knowledge  
  **Mitigation:** Use fictional demo data and clear disclaimer
- **Risk:** Looking too technical and not product-focused  
  **Mitigation:** Emphasize PM decisions, customer value, and tradeoffs
- **Risk:** Mainframe context too shallow  
  **Mitigation:** Focus on enterprise reporting, source/library management, modernization, retention, and regulated customer needs

## 12. Interview Narrative
“I built this prototype to show how I think through product management for mature enterprise software. The goal was not to build a complex app. The goal was to demonstrate customer request triage, roadmap tradeoffs, renewal risk, regulatory impact, engineering effort, and modernization without disruption. The data is fictional, but the product thinking reflects the type of judgment needed when customers depend on mature systems for critical business workflows.”
