# Examples

Real-world PM and career examples showing common low-value AI behavior and pragmatic alternatives.

## 1. Intent-First Discovery

### User request
"Help me message a recruiter."

### Weak output
"Write a long message about your passion and full career story."

### Better output
- Target actor: recruiter screening for role fit under time pressure.
- Incentive: fast signal that candidate matches must-have filters.
- Constraint: recruiter attention is 10 to 20 seconds.

Message draft:
"Hi [Name], I shipped [feature/result] at [company], improving [metric] by [X%]. Open to [role type] in [location]. If useful, I can share a one-page impact summary."

Verification:
Track recruiter response rate in 7 days.

## 2. Friction Reduction and MVP

### User request
"Create a PRD for this small feature."

### Weak output
A 12-page PRD with market landscape, SWOT, and roadmap dependencies.

### Better output
Produce a one-page decision brief:
- user problem;
- scope in and out;
- 3 acceptance scenarios;
- event tracking;
- open risks.

Verification:
Engineering can estimate without a follow-up clarification meeting.

## 3. Signal-to-Noise Ratio

### User request
"Improve this stakeholder update."

### Weak output
"We are excited to share that we made significant progress and aligned stakeholders."

### Better output
"Search latency: 620ms -> 340ms (p95) after index rollout. Next risk: cache invalidation in EU shard. Owner: Alex. Decision needed by Friday: enable 25% traffic shift."

Verification:
Stakeholder replies contain explicit approve, reject, or requested change.

## 4. Evidence-Based Outcomes

### User request
"Help prioritize initiatives."

### Weak output
Sorted list with labels: high, medium, low.

### Better output
Use an evidence table:
- initiative;
- expected behavior change;
- leading metric;
- confidence;
- cost;
- decision deadline.

Verification:
After 2 weeks, compare predicted vs observed movement on leading metric and re-rank.

## Anti-Patterns Summary

| Principle | Anti-pattern | Pragmatic correction |
|---|---|---|
| Intent-First Discovery | Propose before understanding actors | Start with incentive and attention audit |
| Friction Reduction and MVP | Overproduce docs by default | Ship smallest artifact that enables a decision |
| Signal-to-Noise Ratio | Narrative-heavy status writing | Replace with hard signals and explicit ask |
| Evidence-Based Outcomes | Treat writing quality as success | Tie every output to observable behavior change |
