# Flow Logic – Service Catalog Lite

## Laptop Request Flow
- Trigger: RITM created
- Approval: Manager
- Fulfillment: Hardware catalog task
- Notification: Requester

## VPN Access Request Flow
- Conditional Manager approval
- Mandatory Security group approval
- Task created for Network Security team

## Application Access Request Flow
- Manager approval
- For Each selected application:
  - Create one catalog task per application
- RITM closed after tasks
