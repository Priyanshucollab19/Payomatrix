# ResolveFlow — Merchant Case Desk

**Student:** Priyanshu  
**Project type:** Front-end academic prototype for merchant payment support and case resolution.

## Project overview
ResolveFlow is a browser-based workspace for reviewing sample payment activity, tracking merchant support cases, understanding payout deductions and following a repeatable case-escalation workflow.

## Modules
- Overview dashboard for payment activity and case priorities
- Searchable transaction register with status and payment-method filters
- Case tracker with create, filter, resolve and reopen workflows
- Payout reconciliation with an editable net-payout calculator
- CSV exports for sample transactions and payout breakdown
- Resolution playbook covering UPI exceptions, card refunds and payout mismatches
- Priyanshu's escalation path: classify, verify, assign and update

## Run locally
1. Extract the ZIP.
2. Open this folder in VS Code.
3. Open `index.html` using Live Server, or open it directly in a browser.
4. No build tools or package installation are required.

## Prototype limitations
All transaction, merchant and settlement values are fictional. The project does not connect to a real payment gateway, bank, UPI network, card network, webhook or CRM. Case updates are stored only in browser memory and reset on refresh. It is not suitable for processing real payments or handling real customer information.

## Development note
This version is a student-customized extension of a supplied merchant-support prototype. The interface identity, sample merchant dataset, terminology, workflow content and supporting documentation have been revised for Priyanshu. The underlying starter structure should be acknowledged in any submission where source attribution is required. Priyanshu should be prepared to explain the code, demonstrate each module and describe the changes made.

## Suggested future scope
- Persist cases with a backend database
- Add role-based login for support agents and supervisors
- Maintain an audit history for case status changes
- Connect to sandbox payment APIs and verified webhook events
- Add automated reconciliation and exception alerts
