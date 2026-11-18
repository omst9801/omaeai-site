# OmaeAI product baseline and guardrails — design draft (2026-11-17)

## Identity and customer experience
- OmaeAI.com remains the master product-design blueprint. Improve it incrementally; do not replace the Kate receptionist business model with an agency model or unrelated product.
- Kate is the primary inbound AI receptionist. One conversational experience, without traditional press-1 departmental menus. She can help with approved reception, billing FAQs, service questions, scheduling, lead capture, and human handoff.
- Natural conversation is a product differentiator: interruption tolerance, concise humanlike turns, one question at a time, transparent AI identity, and real-world voice-call validation.
- Website languages English, Spanish, French are for browsing and are independent from each customer's selected telephone language(s).

## Approved monthly pricing design direction (not live checkout)
| Tier | Monthly | Included AI minutes (proposed, verify economics) | Call language slots |
| --- | ---: | ---: | --- |
| Kate Starter | $149 | 200 | 1 chosen language |
| Kate Business | $299 | 600 | 1 chosen language |
| Kate Pro | $599 | 1,200 | Up to 3 chosen languages |

- Retell advertises 55 supported languages across 63 locale variants; website selections are a catalogue preview, NOT a claim any three-language combination works with every voice or model.
- Pro should prefer natural language recognition and fallback over keypad trees. The actual provider/model combination needs testing.
- Country availability, carrier routes and phone-number eligibility must be verified. International live telephone calling has not launched.
- Month-to-month subscription direction approved. Annual discounts, overage charges, commitments, margin, and detailed billing terms remain to be finalized. Do not enable checkout until verified.

## Customer self-service lifecycle
1. Sign up and choose a plan; secure per-business customer account.
2. Smart Business Discovery: research industry patterns using external sources but require approval for business-specific facts, pricing, policies and instructions.
3. Train Kate: approved business website, documents, greetings, billing/service knowledge, hours, escalation rules, language selection.
4. Connect a new eligible number, existing-number forwarding, supported SIP, or provider-authorized porting. Preserve existing public numbers.
5. Validate knowledge, voice, phone route, and permitted integrations. Obtain activation approval before taking calls.
6. Kate Inbox, audit logs, call summaries, and ongoing support with human escalation and customer-data isolation.
7. Cancellation: end service at applicable billing boundary, preserve number-port opportunities, release eligible numbers safely and verify cleanup.

## Product roadmap boundaries
- Kate Connect is a separate paid outbound add-on for authorized reminders, notifications and follow-ups; no unsolicited cold calls in its initial scope. Preliminary $99/200, $249/600, $499/1,200 minutes still require cost and tier-structure review.
- Alex remains a Coming Soon future outbound sales persona, not a live capability.
- Optional Cal.com and other calendars/CRM systems are integrations, not mandatory prerequisites. No single scheduling vendor lock-in.
- Autonomous support agents may diagnose and repair approved low-risk issues; payments, number ownership, sensitive data, destructive actions and carrier changes require appropriate controls.
- Preserve GitHub-hosted site and Namecheap domain configuration. Add an isolated always-on secure backend when ready, reusing verified Retell/JARVIS components without putting personal JARVIS or production assets at risk.
- All new website features must distinguish planned/demo from live. No live customer action, payment, phone number purchase or deployment until separately verified.
- One meaningful end-to-end acceptance test per milestone; rollback-capable changes and reviewed promotion to production.

## Design-to-delivery workflow
Propose idea -> check against this website/product baseline -> draft website copy/UX -> owner review -> implement backend -> validate quality/security/cost -> approve publication/activation. Product claims must match what is actually built.
