# Project Handoff & Role Coordination Checklist

Purpose: Ensure clear ownership and reduce handoff friction across cross-functional roles during planning, execution, and release.

Before Planning / Kickoff
- [ ] Confirm named Project Manager and Product Manager
- [ ] Identify personas required (Developers, QA, UX, Security, Data, Support)
- [ ] Assign primary owners for acceptance criteria, success metrics, security, and instrumentation
- [ ] Share Project One-pager with all identified personas

During Planning
- [ ] Define acceptance criteria and assign an owner
- [ ] Agree on success metrics and instrumentation requirements (Data Analyst owner)
- [ ] Schedule UX research and design milestones (UX Designer owner)
- [ ] Perform initial security assessment for high-risk items (Security Lead owner)
- [ ] Validate test plan and QA sign-off criteria (QA owner)

Before Merge / Release
- [ ] Code passes CI and security scans
- [ ] Instrumentation events implemented and validated
- [ ] UX sign-off completed for UI changes
- [ ] Support has runbook or triage notes for customer-facing changes
- [ ] Rollback plan and monitoring/alerts defined (PM / DevOps/Release owner)

Post-release
- [ ] Verify metrics and smoke tests in production (Data Analyst + QA)
- [ ] Triage early issues (Support + Developers)
- [ ] Capture learnings and action items in a retrospective

Communication & Escalation
- [ ] Ensure weekly sync cadence includes critical owners
- [ ] Document escalation path for incidents (Team -> PM -> Product Lead -> Sponsor)
- [ ] Maintain a single source of truth for project status (project README or release doc)

Notes:
- Use this checklist as a template for all projects. Tailor items to project size and risk.
- Add checklist items to the project board or release doc to make ownership visible.
