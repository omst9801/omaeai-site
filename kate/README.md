# Kate V1 — conversational receptionist prototype

Status: **development specification only**. No Retell live agent, API credential, phone number, call, payment or deployment has been created.

## Design contract
- Preserve `OMAEAI_PRODUCT_BASELINE.md`. Kate is the inbound receptionist for OmaeAI; not a separate AI agency or outbound sales bot.
- One continuous caller experience across reception, general billing, scheduling, service questions, and human escalation. Internally, use appropriately permissioned tools rather than pretending a model can access business systems unaided.
- Never impersonate a human. Natural and attentive does not mean concealing that Kate is AI.
- Do not invent opening hours, prices, appointments, policies, refunds, account balances, or booking confirmations.
- Customer business rules come from an explicitly approved Business Profile, never from speculative industry research.
- Never use real caller or customer data for demonstrations without permission.

## Files
1. `kate-core-prompt.md` — reusable voice-agent behavior specification, independent of any one business.
2. `business-profile.schema.json` — per-tenant fields for the planned Train Kate portal.
3. `test-scenarios.md` — end-to-end voice acceptance criteria; one meaningful milestone test.
4. `implementation-plan.md` — Retell adapter and secure setup sequence.

## Not in V1
Real-time multilingual switching, live payment or account lookups, public website voice widget, automatic phone purchases, customer provisioning, live Cal.com credentials, customer support autonomy, or international live calling are not implied by this first development package.

## Next integration
After reviewing existing Retell agent IDs and settings in the authorised OmaeAI workspace, create a **separate** private test agent using a minimally privileged environment-specific API key stored outside the repository. Do not overwrite existing JARVIS/Retell agents. Use an owner-approved isolated demo business profile. Then perform one real inbound-call evaluation before iterating.
