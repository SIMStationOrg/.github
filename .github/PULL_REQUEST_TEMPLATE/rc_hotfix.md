# RC / Hotfix Pull Request

## Context
<!-- Release context or production incident context -->
- Ticket(s): SIMSOFT-XXXX
- Summary:
- Business/operational urgency:

## Changes
<!-- Key changes included in this RC/hotfix -->
- 

## Validation
<!-- Tests and checks executed -->
- [ ] Required CI checks pass
- [ ] Relevant automated tests pass
- [ ] Manual checks completed (if applicable)
- [ ] SonarQube complexity warnings addressed for new/refactored code
- [ ] Targeted production-risk checks completed

## Release safety and rollout
- Release notes/changelog:
- Risk level: Low / Medium / High
- Rollback plan:
- Monitoring/health checks to verify post-deploy:

## Required approvals and branch flow
- [ ] PR is no longer Draft
- [ ] Required approvals are present
- [ ] Lead approval for production release is recorded
- [ ] Required review threads are resolved or explicitly agreed

### RC flow confirmation
- [ ] RC branch was created from latest development
- [ ] RC merges into main only after automated and manual validation

### Hotfix flow confirmation
- [ ] Hotfix branch was created from main
- [ ] Fix merged back into main
- [ ] Hotfix back-merged into development

## Incident follow-up (hotfix only)
- Root cause:
- Corrective follow-up task(s):

## Resource

- [PR Guidelines](https://didactic-adventure-r3z3zv6.pages.github.io/#/docs/delivery/pr-guidelines)
- [Review Checklist](https://didactic-adventure-r3z3zv6.pages.github.io/#/docs/delivery/review-checklist)
- [Release and deployment](https://didactic-adventure-r3z3zv6.pages.github.io/#/docs/delivery/release-deployment)