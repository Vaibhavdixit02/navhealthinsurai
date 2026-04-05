# Thesis

**Last updated:** 2026-04-02

## Problem

Healthcare costs growing unsustainably ($4.8T in 2023 → projected $7.7T by 2032, 1/5th of US economy). Three root causes:
*(V1 Memo, p.1–2)*

1. **Disconnected front door.** Consumer entry points (Google, ChatGPT — ~8% and ~10% of queries are health-related) have no context on coverage or history. Provider/payor tools have context but terrible UX.
2. **Payor-provider misalignment.** Zero-sum dynamics compound into claims adjudication cycles, prior auth, sub-optimal network construction.
3. **Broken steerage.** 99% of healthcare encounters are suboptimal in matching consumers to the right provider by complexity, cultural competency, distance, and quality. *(V1 Memo, p.1–2, citing Appendix 1)*

## Insight

AI removes the clinician-scarcity constraint — the information layer of healthcare (triage, monitoring, guidance, medication management) becomes effectively infinite at near-zero marginal cost. The natural pricing model shifts to subscription/PMPM. That's insurance.
*(Email: "Open questions / plan to tackle", 2026-03-09, Vaibhav — citing the a16z "Infinite Healthcare" piece)*

"Our insurance product is the bundled healthcare AI services driving better proactive care and also working actually as insurance (paying out on care)."
*(WhatsApp, 2026-03-04, Vaibhav)*

"Baking proactive care and AI-driven health services directly into the core insurance premium. It shifts the product from a purely financial backstop to an actual health subscription."
*(WhatsApp, 2026-03-07, Vaibhav)*

## Solution

An AI-native health insurance company where the product is a bundled AI healthcare service. The member gets one thing that handles everything — it triages their symptoms, finds the right doctor, books appointments, manages prescriptions, catches problems before they escalate — AND it pays the bill. They never think "I have insurance plus a navigation app."
*(Email: "Open questions / plan to tackle", 2026-03-09, Vaibhav)*

Not a triage company that adds insurance later. An insurance company whose core capability is the best AI healthcare service.
*(Email: "Open questions / plan to tackle", 2026-03-09, Vaibhav)*

The "nav layer" = digital navigation + provider navigation.
*(WhatsApp, 2026-03-04, Vaibhav)*

V1 platform has three components:
1. Consumer-facing AI concierge navigation app (front door)
2. Benefits and care optimization engine (leveraging health queries, claims, medical records)
3. Enterprise analytics system for plans, providers, employers
*(V1 Memo, p.3–4)*

## Why now

1. **Consumerization of healthcare** — greater optionality, fragmentation, amplified need for single-interface navigation. *(V1 Memo, p.15)*
2. **AI enablement** — ~80% of clinical decision-making can now be done effectively by AI (vs ~20% five years ago). *(V1 Memo, p.15)*
3. **ICHRA and employer self-insurance trend** — employers seeking alternatives, small/mid-size employers exploring self-insured options. *(V1 Memo, p.15)*
4. **ACA subsidies expired** — 4.8M more uninsured, employers seeking alternatives. *(Email: "Open questions", 2026-03-09, Vaibhav)*
5. **Stop-loss market hardening** — claims >$2M up 1,251% since 2014. *(Email: "Open questions", 2026-03-09, Vaibhav)*
6. **Price transparency data** — since 2022, visibility into every insurer's provider rates for network design. *(Email: "Open questions", 2026-03-09, Vaibhav)*

## Risks

- Zero-to-one insurance is "brutal" — "shaving years off your lifespan for incremental and slow progress." ~10 former Oscar senior people (head of commercial small group, head of network, head of ICHRA, CEO/founder, etc.) all said it's not worth it. *(WhatsApp, 2026-03-05, Manav)*
- Enrollment feedback cycles are very slow; individual market is brand-driven, employer market requires convincing brokers. *(WhatsApp, 2026-03-05, Manav)*
- "Things that academically make sense but in practice don't / miss nuance specific to the industry." Need to pressure-test deep research assumptions. *(Email: "Re: AI-Native Health Plan", 2026-03-09, Manav)*
- Employer attrition after ownership change (10–20% expected). *(Email: "Open questions", 2026-03-09, Vaibhav)*
- TPA data access as bottleneck for AI deployment. *(Email: "Open questions", 2026-03-09, Vaibhav)*
- Integration complexity across different captive structures. *(Email: "Open questions", 2026-03-09, Vaibhav)*
