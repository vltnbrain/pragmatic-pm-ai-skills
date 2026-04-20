# Examples

Practical PM/career scenarios with side-by-side patterns.

Format per case:
- Bad: generic, high-friction, low-signal answer.
- Pragmatic: incentive-aware, low-friction, measurable answer.

## Recruiting and Career (4 cases)

### 1. Cold message to recruiter

**User request:** "Help me write to a recruiter."

**Bad**
"I am passionate, proactive, and excited to contribute to your amazing company."

**Pragmatic**
"Hi [Name], I shipped [feature] at [company], improving [metric] by [X%]. Open to [role] in [location]. Happy to share a one-page impact summary."

**Verification**
Measure recruiter response rate in 7 days.

### 2. LinkedIn headline optimization

**User request:** "Improve my headline."

**Bad**
"Product Leader | Innovation Enthusiast | Building the future"

**Pragmatic**
"Senior Product Manager | B2B SaaS | Reduced onboarding drop-off 31% | ex-[brand]"

**Verification**
Compare profile views and inbound recruiter messages before/after for 14 days.

### 3. Resume bullet rewrite

**User request:** "Make this bullet stronger."

**Bad**
"Responsible for cross-functional collaboration and stakeholder alignment."

**Pragmatic**
"Led launch across Product, Eng, and Sales; delivered in 6 weeks and grew activation from 42% to 57%."

**Verification**
Track interview conversion rate per 20 applications.

### 4. Networking follow-up

**User request:** "Write a follow-up after meeting a VP."

**Bad**
"Great meeting you, let's stay in touch."

**Pragmatic**
"Great meeting today. You mentioned churn in SMB tier. I attached a 1-page teardown with 3 testable retention levers. If useful, I can send experiment design details."

**Verification**
Track reply rate and next-step meetings booked.

## Product Discovery and Prioritization (4 cases)

### 5. Prioritize feature requests

**User request:** "Prioritize these ideas."

**Bad**
"High / Medium / Low" with no criteria.

**Pragmatic**
Rank by expected behavior change, confidence, implementation cost, and decision deadline.

**Verification**
After 2 weeks, compare predicted impact vs observed leading metric movement.

### 6. Validate a customer problem

**User request:** "How do I validate this problem fast?"

**Bad**
"Run broad user research and build personas first."

**Pragmatic**
Run 5 targeted interviews with a strict script: current workaround, pain frequency, and willingness to switch.

**Verification**
Count how many users report weekly pain + active workaround.

### 7. Write hypothesis for experiment

**User request:** "Create a hypothesis."

**Bad**
"Users will like this feature and engagement will improve."

**Pragmatic**
"For Persona A, changing onboarding step B will increase day-7 activation from 38% to 45% within 21 days."

**Verification**
A/B metric delta and confidence interval at end of run.

### 8. Decide build vs no-build

**User request:** "Should we build this?"

**Bad**
Long narrative with market trends and no decision rule.

**Pragmatic**
Decision memo with explicit gate: build only if expected ARR lift > cost threshold and engineering opportunity cost is acceptable.

**Verification**
Decision made in one review meeting without follow-up deck.

## PRD and Delivery (4 cases)

### 9. PRD for small feature

**User request:** "Create a PRD."

**Bad**
10+ pages covering strategy history and optional edge cases.

**Pragmatic**
1-page PRD: problem, scope in/out, 3 acceptance scenarios, events/metrics, open risks.

**Verification**
Engineering estimates without clarification meeting.

### 10. Acceptance criteria quality

**User request:** "Improve acceptance criteria."

**Bad**
"Feature should be intuitive and user-friendly."

**Pragmatic**
"Given user is logged in and has role X, when they click Y, then system must return Z in under 2 seconds."

**Verification**
QA can execute tests without asking PM for interpretation.

### 11. Scope negotiation with engineering

**User request:** "Help align scope with Eng."

**Bad**
"Let's align and collaborate on the roadmap."

**Pragmatic**
Propose two scope options with trade-offs: must-have for metric target vs deferred items with impact estimate.

**Verification**
Scope decision in same meeting, no unresolved blockers.

### 12. Launch readiness

**User request:** "Prepare launch checklist."

**Bad**
Generic checklist copied from blog post.

**Pragmatic**
Checklist tied to this launch: tracking events verified, rollback owner assigned, support macro prepared, success metric dashboard live.

**Verification**
No P0 surprise in first 72 hours; monitoring complete.

## Stakeholder Communication (4 cases)

### 13. Weekly stakeholder update

**User request:** "Write update for leadership."

**Bad**
"Made significant progress and aligned teams."

**Pragmatic**
"Activation: 41% -> 46% WoW after onboarding fix. Risk: billing webhook delays in EU. Decision needed by Friday: enable 50% rollout."

**Verification**
Leadership replies with explicit approve/reject/question, not "thanks".

### 14. Escalation note

**User request:** "Escalate this blocker."

**Bad**
"We have some dependency concerns and need support."

**Pragmatic**
"Release at risk by 5 business days due to API quota cap. Need infra approval for +40% quota by Wed 15:00 to keep launch date."

**Verification**
Escalated owner assigned and SLA confirmed.

### 15. Exec meeting prep

**User request:** "Prepare for exec review."

**Bad**
50-slide deck with repeated context.

**Pragmatic**
One-page decision brief: objective, options, recommendation, cost, risk, irreversible consequences.

**Verification**
Meeting ends with decision and named owner.

### 16. Cross-team alignment message

**User request:** "Align Sales and Product on timeline."

**Bad**
"Let's collaborate closely to ensure success."

**Pragmatic**
"Beta date moved from May 10 to May 24 due to auth dependency. Sales enablement draft by May 17. Customer-facing GA date unchanged."

**Verification**
No conflicting external dates in GTM channels.

## Mini Scorecard Template

Use this compact scorecard weekly:

| Metric | Before | After | Delta | Window |
|---|---:|---:|---:|---|
| Recruiter response rate | 12% | 21% | +9 pp | 7 days |
| Stakeholder approval speed | 4.2 days | 2.1 days | -50% | 30 days |
| PRD clarification rate | 0.78 | 0.33 | -0.45 | 4 sprints |

Definitions are in [`BENCHMARK.md`](./BENCHMARK.md).
