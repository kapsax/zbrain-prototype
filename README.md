# ZBrain — Navigation Redesign Prototype

Interactive UX prototype for the ZBrain admin console and space workspace redesign.

**Live:** https://kapsax.github.io/zbrain-prototype/

Single self-contained HTML file — no build step, no dependencies.

## What it covers
- Context switcher between the Admin Console and spaces
- Admin Observatory (agent health, governance events) with filtered Agent, Usage and Audit logs
- Space Observatory and the Governance log group, scoped and role-aware
- Create / edit space wizard
- Computed policy per solution, with policy-scoped overrides and the request → approval flow

All data is synthetic. Use the **Simulate user** control to switch between Admin, Builder and Viewer,
and **UX notes** to see the rationale behind each decision.
