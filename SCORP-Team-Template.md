# SCORP Team Template

- [Team engineering with SCORP](https://theserverlessedge.com/team-engineering-with-scorp/)
- [How to make well-architected reviews work for your organisation (Part 1)](https://theserverlessedge.com/how-to-make-well-architected-work-for-organisations-introducing-the-scorp-review-cycle-part-1)
- [How to make well-architected reviews work for your organisation (Part 2)](https://www.theserverlessedge.com/making-well-architected-work-for-organisations-the-security-cost-opex-reliability-performance-scorp-process-cycle-part-2/)


This is a starter template to get your SCORP process up and running. You should tailor each section to user specific needs and context.

## Well Architected Reviews
Link to Well Architected Reviews for this team's workloads

| Workload | Date | Lens Applied | Summary | Status | Link |
|----------|------|--------------|---------|--------|------|
|          |      |              |         |        |      |

## Monitoring / Dashboards
Link to Team specific dashboard and observability tools.

- [Dashboard](#)
- [Dashboard](#)

## Business Metrics
Key Business Metrics for your team's context – North Star Metrics, Health, Usage, Adoption, Satisfaction, Ecosystem, Outcome, etc. Call out commentary on Trends, anomalies, etc.

| Month     | Metric | Metric | Metric | Notes |
|-----------|--------|--------|--------|-------|
| October   |        |        |        |       |
| September |        |        |        |       |
| August    |        |        |        |       |

## Security
The security pillar focuses on protecting information and systems. Key topics include confidentiality and integrity of data, managing user permissions, and establishing controls to detect security events.

### Threat Models

| Workload | Link to Threat Model | Open Threats | Last Updated/Reviewed |
|----------|----------------------|--------------|-----------------------|
|          |                      |              |                       |

### Security Tooling Reports
Findings from your security tooling for this team and their workloads (Snyk, Checkmarx, Veracode, AWS Inspector, Security Hub, etc).

| Month     | Workload | Findings | Notes |
|-----------|----------|----------|-------|
| October   |          |          |       |
| September |          |          |       |
| August    |          |          |       |
| …         |          |          |       |

## Cost
Findings from your cost tooling for this team and their workloads (Quicksight, Cost Explorer, Cost Intelligence Dashboard, etc).

| Month     | Avg. Invocations | API-GW ($) | Lambda ($) | Dynamo ($) | Total ($) | Cost per 1000 transaction ($) | Notes |
|-----------|------------------|------------|------------|------------|-----------|------------------------------|-------|
| October   |                  |            |            |            |           |                              |       |
| September |                  |            |            |            |           |                              |       |
| August    |                  |            |            |            |           |                              |       |
| …         |                  |            |            |            |           |                              |       |

## Operational Excellence
The operational excellence pillar focuses on running and monitoring systems, and continually improving processes and procedures. Key topics include automating changes, responding to events, and defining standards to manage daily operations.

- Links to Runbooks
- Link to dashboards

### Production Issues
| Month     | P1 | P2 | P3 | Notes |
|-----------|----|----|----|-------|
| October   |    |    |    |       |
| September |    |    |    |       |
| August    |    |    |    |       |
| …         |    |    |    |       |

### Deployment Frequency (Production)
| Month     | Deploys | Trend Summary | Notes |
|-----------|---------|---------------|-------|
| October   |         |               |       |
| September |         |               |       |
| August    |         |               |       |
| …         |         |               |       |

### Lead/Cycle Times
| Month     | Story Start -> In Prod | Code Committed -> In Prod | Notes |
|-----------|------------------------|---------------------------|-------|
| October   |                        |                           |       |
| September |                        |                           |       |
| August    |                        |                           |       |
| …         |                        |                           |       |

### Change Failure Rate
| Month     | Workload | Number of Prod Deploys | Number of Incidents | Fail Rate | Learnings |
|-----------|----------|------------------------|----------------------|-----------|-----------|
| October   |          |                        |                      |           |           |
| September |          |                        |                      |           |           |
| August    |          |                        |                      |           |           |
| …         |          |                        |                      |           |           |

### Test Coverage
#### Unit Tests
- List framework tooling
- Optional: Include test results, and notes on trends, etc.

#### Integrations & E2E Tests
- List framework tooling
- Optional: Include test results, and notes on trends, etc.

### Critical Business Transactions
Could also be user flows, business rules, etc.

| Month     | # of Key Transactions Identified | # Covered by Functional (Automated) Tests | # Observable on Dashboards | # with Active Alarms | # Covered by Performance Tests |
|-----------|----------------------------------|------------------------------------------|----------------------------|----------------------|---------------------------------|
| October   |                                  |                                          |                            |                      |                                 |
| September |                                  |                                          |                            |                      |                                 |
| August    |                                  |                                          |                            |                      |                                 |
| …         |                                  |                                          |                            |                      |                                 |

### Exploratory/Chaos Testing Sessions
| Initiative | When was it done? | Test Charter | Notes |
|------------|-------------------|--------------|-------|
|            |                   |              |       |
|            |                   |              |       |

## Reliability
The reliability pillar focuses on workloads performing their intended functions and how to recover quickly from failure to meet demands. Key topics include distributed system design, recovery planning, and adapting to changing requirements.

- [Links to Playbooks](#)
- [Link to Incident Response Process](#)

### Incidents
| Incident # | Date | Description | TTR (Time to Recover) | (Blameless) Root Cause Analysis | Learnings |
|------------|------|-------------|-----------------------|---------------------------------|-----------|
|            |      |             |                       |                                 |           |
|            |      |             |                       |                                 |           |

### Errors Per Workload
| Month     | Workload |
|-----------|----------|
| October   |          |
| September |          |
| August    |          |
| …         |          |

## Performance
Details on the performance of your workloads.

- [Link to Performance Reports / Dashboard](#)

| Month     | Workload | Frontend | API GW | Lambda | DynamoDB | EventBridge | Comments |
|-----------|----------|----------|--------|--------|----------|-------------|----------|
| October   |          |          |        |        |          |             |          |
| September |          |          |        |        |          |             |          |
| August    |          |          |        |        |          |             |          |
| …         |          |          |        |        |          |             |          |

## Sustainability
The sustainability pillar focuses on minimizing the environmental impacts of running cloud workloads. Key topics include a shared responsibility model for sustainability, understanding impact, and maximizing utilization to minimize required resources and reduce downstream impacts.

| Month     | Workload | Carbon Score |
|-----------|----------|--------------|
| October   |          |              |
| September |          |              |
| August    |          |              |
| …         |          |              |

[https://aws.amazon.com/aws-cost-management/aws-customer-carbon-footprint-tool/](https://aws.amazon.com/aws-cost-management/aws-customer-carbon-footprint-tool/)
