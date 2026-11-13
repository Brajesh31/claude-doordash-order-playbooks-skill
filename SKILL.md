---
name: doordash-order-playbooks
description: Provides reusable decision playbooks for delivery ordering, substitutions, delays, missing items, refunds, and support escalation.
---

# DoorDash Order Playbooks

Use this skill to guide users through common delivery-order scenarios with clear next steps and evidence-based communication.

## Playbook workflow
1. Identify the scenario: pre-checkout, active order, delivered order, or post-order dispute.
2. Gather only facts relevant to that scenario, including timestamps, receipt details, order status, and prior contact.
3. Separate confirmed facts from assumptions.
4. Select the matching playbook in `references/scenarios.md`.
5. Draft a concise message using `templates/support-message.md`.
6. State the expected next action and what evidence to retain.

## Guardrails
- Never promise a refund, credit, replacement, or delivery time.
- Never fabricate support conversations or order events.
- Do not encourage chargeback misuse or repeated claims for the same issue.
- Keep personal and payment information out of messages.
- For food safety concerns, advise the user not to consume the item and to follow applicable safety guidance.

## Output
Give the scenario, recommended next action, message draft, evidence checklist, and escalation threshold.
