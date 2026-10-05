# GoDaddy Domain n8n community node

GoDaddy helps businesses register domains and manage DNS, renewals, and domain settings

Generated from OpenAPI  with template 1.1.0. Generated files are platform-managed and will be overwritten during regeneration.

## Authentication

This integration does not require credentials.

## Supported operations

- `DELETE /v2/customers/{customerId}/domains/{domain}/actions/{type}` - Cancel Recent Domain Action
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/{domain}/actions` - List Recent Domain Actions
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/{domain}/actions/{type}` - Get Recent Domain Action
  - Retry Contract: none
  - Pagination Contract: none
- `PATCH /v2/customers/{customerId}/domains/{domain}/contacts` - Update Domain Contacts
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/available` - Check Domain Availability
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/available` - Check Availability in Bulk
  - Retry Contract: none
  - Pagination Contract: none
- `DELETE /v2/customers/{customerId}/domains/{domain}/changeOfRegistrant` - Cancel Registrant Change
  - Retry Contract: none
  - Pagination Contract: none
- `DELETE /v2/customers/{customerId}/domains/forwards/{fqdn}` - Delete Domain Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/forwards/{fqdn}` - Get Domain Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/forwards/{fqdn}` - Create Domain Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v2/customers/{customerId}/domains/forwards/{fqdn}` - Update Domain Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/{domain}` - Get Domain
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/agreements` - Get Purchase Agreements
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/{domain}` - Get Domain
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/{domain}/changeOfRegistrant` - Get Registrant Change
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/{domain}/privacy/forwarding` - Get Privacy Email Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/register/schema/{tld}` - Get Registration Schema
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/domains/maintenances` - List Maintenance Windows
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/domains/maintenances/{maintenanceId}` - Get Maintenance Details
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/domains/usage/{yyyymm}` - Get Monthly API Usage
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains` - List Domains
  - Retry Contract: none
  - Pagination Contract: none
- `PATCH /v2/customers/{customerId}/domains/{domain}/privacy/forwarding` - Update Privacy Email Forwarding
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/redeem` - Redeem Domain
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/renew` - Renew Domain
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transfer` - Start Domain Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferInAccept` - Accept Incoming Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferInCancel` - Cancel Incoming Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferInRestart` - Restart Incoming Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferInRetry` - Retry Incoming Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferOut` - Start .uk Transfer Out
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferOutAccept` - Accept Outgoing Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/{domain}/transferOutReject` - Reject Outgoing Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/register` - Register Domain
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/register/validate` - Validate Registration
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/purchase` - Register Domain
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/{domain}/privacy/purchase` - Purchase Domain Privacy
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v2/customers/{customerId}/domains/{domain}/nameServers` - Replace Name Servers
  - Retry Contract: none
  - Pagination Contract: none
- `PATCH /v1/domains/{domain}/records` - Add DNS Records
  - Retry Contract: none
  - Pagination Contract: none
- `DELETE /v1/domains/{domain}/records/{type}/{name}` - Delete DNS Records
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/{domain}/records/{type}/{name}` - Get DNS Records
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v1/domains/{domain}/records` - Replace DNS Records
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v1/domains/{domain}/records/{type}` - Replace DNS Records by Type
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v1/domains/{domain}/records/{type}/{name}` - Update DNS Records
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/{domain}/renew` - Renew Domain
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/purchase/schema/{tld}` - Get Registration Schema
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/suggest` - Suggest Domain Names
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/{domain}/transfer` - Start Domain Transfer
  - Retry Contract: none
  - Pagination Contract: none
- `PATCH /v1/domains/{domain}` - Update Domain
  - Retry Contract: none
  - Pagination Contract: none
- `PATCH /v1/domains/{domain}/contacts` - Update Domain Contacts
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/purchase/validate` - Validate Registration
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/{domain}/verifyRegistrantEmail` - Resend Registrant Verification
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/notifications` - Get Next Domain Notification
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/notifications/optIn` - List Notification Opt-ins
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v2/customers/{customerId}/domains/notifications/schemas/{type}` - Get Notification Schema
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v2/customers/{customerId}/domains/notifications/{notificationId}/acknowledge` - Acknowledge Notification
  - Retry Contract: none
  - Pagination Contract: none
- `PUT /v2/customers/{customerId}/domains/notifications/optIn` - Opt in to Notifications
  - Retry Contract: none
  - Pagination Contract: none
- `POST /v1/domains/contacts/validate` - Validate Domain Contacts
  - Retry Contract: none
  - Pagination Contract: none
- `DELETE /v1/domains/{domain}` - Cancel Domain
  - Retry Contract: none
  - Pagination Contract: none
- `DELETE /v1/domains/{domain}/privacy` - Cancel Domain Privacy
  - Retry Contract: none
  - Pagination Contract: none
- `GET /v1/domains/tlds` - List TLDs
  - Retry Contract: none
  - Pagination Contract: none

## Usage

1. Install this community-node package in n8n.
2. Add the **GoDaddy Domain** node to a workflow.
3. Select a resource and operation, configure its parameters, and execute the workflow.

## Example workflow

Connect **Manual Trigger** -> **GoDaddy Domain** -> a destination node, select an operation, then run the workflow and inspect the returned items.

## Development

```sh
npm install
npm run build
npm run lint
npm run dev
```

`npm run dev` starts a local n8n development instance. Find the integration by its **GoDaddy Domain** display name.
