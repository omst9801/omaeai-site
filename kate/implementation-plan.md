# Kate V1 implementation — low-risk sequence

1. **Inventory, don't overwrite:** identify existing Retell agents, telephone numbers, voices, prompts, tool configurations, recorded timing and billing. Protect personal JARVIS and any commercial demos already working. Do not copy credentials or customer data into GitHub.
2. **Configuration mapping:** compare Retell's documented prompt-based vs conversation-flow agent options; choose a single coherent caller-facing Kate persona. Map `kate-core-prompt.md` and per-tenant data to verified current Retell fields. Avoid guessing undocumented API fields.
3. **Private sandbox:** create a new clearly named OmaeAI development agent under the owner-approved account, with least-privilege secrets from a secure store, minimal spend controls and no published phone route.
4. **Tuning:** choose one credible female voice; tune response speed, interruption behavior, pronunciation, acknowledgment style and silence handling. Avoid costly repeated voice auditions.
5. **Business demo:** supply owner-approved fictional business profile or obtain authorisation to use a real demonstration business. Industry research may suggest workflows but must not insert unapproved company policies.
6. **One phone acceptance test:** execute `test-scenarios.md`; collect user feedback and metrics. Only modify what demonstrably fails.
7. **After successful pilot:** implement Train Kate portal, business isolation, automation, Cal.com and other opted-in calendar tools, forwarding, billing and customer support agents. Keep feature claims on OmaeAI.com aligned with tested capabilities.

## Retell documentation references
- https://docs.retellai.com/
- https://docs.retellai.com/deploy/chat-widget

## Launch boundaries
Current website is a preview; no live automated signup, provisioning, payments or international calling is implied. Live changes require approval and rollback plan.
