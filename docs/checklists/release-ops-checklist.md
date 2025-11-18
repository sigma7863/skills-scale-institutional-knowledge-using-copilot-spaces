# Release Operations Checklist

## Purpose
This checklist supports DevOps/Infrastructure Engineers and release coordinators in preparing for and executing production releases. It complements the guidance in `docs/octoacme-release-and-deployment.md` with operational focus.

---

## Pre-Release Preparation

### Environment Provisioning
- [ ] Verify staging environment matches production configuration
- [ ] Confirm all required services and dependencies are available
- [ ] Validate environment variables and secrets are configured
- [ ] Check resource capacity (CPU, memory, storage, bandwidth)

### Pipeline Health
- [ ] Review CI/CD pipeline status and recent build history
- [ ] Confirm all automated tests are passing
- [ ] Validate security scans and vulnerability checks
- [ ] Check for any pending infrastructure changes or patches

### Rollback Readiness
- [ ] Document rollback procedure and steps
- [ ] Verify rollback can be executed within acceptable timeframe
- [ ] Confirm database migration rollback strategy (if applicable)
- [ ] Tag or snapshot current production state for quick recovery

### Observability & Monitoring
- [ ] Verify monitoring dashboards are up to date
- [ ] Confirm alerting rules are configured and tested
- [ ] Set up release-specific metrics or dashboards
- [ ] Ensure logging is capturing relevant events

---

## Staging Validation

### Smoke Tests
- [ ] Run smoke tests in staging environment
- [ ] Validate critical user flows and API endpoints
- [ ] Check integration points with external services
- [ ] Verify performance and latency are acceptable

### Stakeholder Coordination
- [ ] Notify Customer Support Lead of upcoming release
- [ ] Share release notes with support and stakeholders
- [ ] Confirm deployment window with Project Manager
- [ ] Communicate expected downtime (if any) to users

---

## Deployment Execution

### Production Deployment
- [ ] Execute deployment using approved pipeline or process
- [ ] Monitor deployment progress and logs in real-time
- [ ] Verify deployment completes without errors
- [ ] Confirm new version is running in production

### Post-Deploy Verification
- [ ] Run post-deploy smoke tests on production
- [ ] Validate critical functionality is working
- [ ] Check monitoring dashboards for anomalies
- [ ] Review error rates and system health metrics
- [ ] Confirm no unexpected alerts or incidents

---

## Post-Release Activities

### Communication
- [ ] Announce successful release to stakeholders
- [ ] Update release status in project tracking tools
- [ ] Notify Customer Support Lead that release is complete
- [ ] Document any issues or learnings for retrospective

### Incident Preparedness
- [ ] Add or update entry in incident runbook if needed
- [ ] Confirm on-call rotation is aware of new release
- [ ] Document known issues or workarounds
- [ ] Prepare rollback plan in case of critical issues

### Monitoring & Follow-up
- [ ] Monitor system for 24-48 hours post-release
- [ ] Track key metrics (error rates, performance, user feedback)
- [ ] Schedule post-release review with team
- [ ] Update this checklist based on lessons learned

---

## Emergency Rollback (if needed)
- [ ] Trigger incident response and notify on-call team
- [ ] Execute documented rollback procedure
- [ ] Communicate rollback to stakeholders and support
- [ ] Investigate root cause and document findings
- [ ] Update rollback procedures based on experience
