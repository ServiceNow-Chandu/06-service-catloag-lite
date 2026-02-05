# Architecture – Service Catalog Lite

## Scope
Scoped application built using ServiceNow Studio.

## Design Overview
User submits catalog request → Flow triggered on RITM →
Approvals enforced → Tasks created → Request closed.

## Key Design Principles
- Reusable flow logic
- Clear separation of approvals and fulfillment
- Parallel task execution where applicable
- Minimal customization of OOB tables
