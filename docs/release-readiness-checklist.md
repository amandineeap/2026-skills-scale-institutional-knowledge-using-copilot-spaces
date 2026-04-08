# Release Readiness Checklist

This checklist is used by the Release Manager and QA Lead to confirm that a release is ready for deployment. Complete all items before calling a go/no-go decision.

---

## 1. Pre-Release Quality Gates and Sign-Offs

- [ ] All features included in the release scope have been implemented and code-reviewed
- [ ] Unit and integration tests pass with no blocking failures
- [ ] Regression test suite has been executed and results reviewed
- [ ] User acceptance testing (UAT) completed and signed off by stakeholders
- [ ] All P0 and P1 defects resolved; known issues documented and accepted
- [ ] Test summary report prepared and shared with the Project Manager
- [ ] QA Lead sign-off obtained confirming quality gates are met
- [ ] Release Manager confirms go/no-go decision with Project Manager and QA Lead

---

## 2. Release Communication Timeline

- [ ] Release date and scope confirmed with Project Manager and Product Manager
- [ ] Release notes drafted and reviewed (features, bug fixes, known issues)
- [ ] Internal stakeholders notified of upcoming release (at least 3 business days in advance)
- [ ] External communications (customer-facing) reviewed and approved (if applicable)
- [ ] Support and operations teams briefed on release content and expected impact
- [ ] Release notes published to the appropriate channel (docs, changelog, portal)
- [ ] Post-release communication plan prepared (success announcement or incident response)

---

## 3. Deployment Coordination Steps

- [ ] Deployment runbook reviewed and updated for this release
- [ ] Deployment environment confirmed and pre-deployment checks passed
- [ ] Feature flags or configuration changes documented and staged
- [ ] Database migrations or infrastructure changes reviewed and tested
- [ ] Deployment window scheduled and communicated to the team
- [ ] On-call or incident response team identified and briefed
- [ ] Deployment executed following the runbook
- [ ] Deployment log captured and stored in the project record

---

## 4. Post-Release Validation and Support

- [ ] Smoke tests executed in production immediately after deployment
- [ ] Key metrics and dashboards monitored for anomalies (error rates, latency, usage)
- [ ] Support team monitoring for incoming bug reports or user feedback
- [ ] Any post-release defects logged and triaged with priority assignments
- [ ] Rollback decision criteria defined and rollback executed if needed
- [ ] Post-release status communicated to stakeholders (success or incident summary)
- [ ] Release retrospective scheduled (for significant releases)
- [ ] Release record updated with deployment outcome and any lessons learned
