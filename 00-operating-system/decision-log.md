# Decision log

Newest first.

---

### 2026-03-09 — India deprioritized

- **Status:** accepted
- **Owners:** Manav
- **Context:** Vaibhav explored India launch: market dominated by banks' insurance products, low standalone participation, licensing/permissions are biggest blockers. Hinduja family has a health insurance license and is looking to offload. *(WhatsApp, 2026-03-07–08)*
- **Decision:** Not building for India currently. Market dynamics dramatically different from US. Would require being physically in India. *(Email: "Re: AI-Native Health Plan", 2026-03-09, Manav)*
- **Alternatives:** Longer-term maybe a different story.
- **Follow-ups:**
- **Links:**

---

### 2026-03-09 — Don't build triage engine — be the orchestration layer

- **Status:** accepted
- **Owners:** Vaibhav, Manav
- **Context:** Building a production-grade clinical triage engine from scratch is $100M+, multi-year, requires clinical founder, regulatory navigation, massive data collection. Competitive landscape includes companies with hundreds of millions in funding doing exactly this.
- **Decision:** Be the platform that orchestrates: existing clinical APIs (e.g. Infermedica) for structured triage + commercial LLMs for conversational interface + hard-coded safety rules + integration layer connecting to our provider network, benefits/coverage data, claims system. *(Email: "Open questions", 2026-03-09, Vaibhav)*
- **Alternatives:** Build proprietary triage model from scratch.
- **Follow-ups:** Manav: "aligned on this." *(Email: "Open questions", 2026-03-09, Manav)*. Regulatory positioning: "care navigation" not "diagnosis." Need to go deeper on data sources and agent orchestration. *(Email: "Open questions", 2026-03-09, Manav)*
- **Links:**

---

### 2026-03-09 — Narrow launch surface, vertical depth

- **Status:** accepted
- **Owners:** Vaibhav, Manav
- **Context:** Question of narrow (triage → find doctor → schedule) vs. broad (benefits nav, med ordering, etc.).
- **Decision:** Narrow at launch, but narrowness is vertical (depth of integration), not horizontal (breadth of features). Three things at launch: (1) AI triage + care guidance, (2) provider quality + cost matching, (3) transactional completion (book appointment, confirm coverage, show out-of-pocket). *(Email: "Open questions", 2026-03-09, Vaibhav)*
- **Alternatives:** Broad launch with benefits nav, pharmacy, chronic care. These are Phase 2–3 expansions.
- **Follow-ups:** Manav: "makes sense but I think we probably need to go one layer deeper to understand where we pull data from." *(Email: "Open questions", 2026-03-09, Manav)*
- **Links:**

---

### 2026-04-02 — Captive / health insurance company acquisition as market entry path

- **Status:** accepted
- **Owners:** Vaibhav, Manav
- **Context:** Long tail of 30–50 small independent captive health plan operators, founder-led, 10–40 employer groups each. Many approaching succession with no clear buyer. Typical target: 20 employer groups, ~6K covered lives, ~$45M managed premium, ~$1.8M management fee revenue, valued at $3–4M (6–8x EBITDA). *(Email: "Open questions", 2026-03-09, Vaibhav)*
- **Decision:** Acquire captive plan operators or a health insurance company, layer AI on top, build toward full insurer. Phase 1: captive manager + TPA (years 1–3). Phase 2: start bearing stop-loss risk. Phase 3: insurance license.
- **Alternatives:** Zero-to-one insurance (rejected — see below). Selling through existing insurers (super slow, was a meaningful part of Memora; *(WhatsApp, 2026-03-05, Manav)*).
- **Follow-ups:** Initially Manav was "aligned on everything except the concept of buying 5 assets in 18 months...that seems like a disaster. These things are not easy to buy." *(Email: "Open questions", 2026-03-09, Manav)*. Manav agreed on the acquisition path. *(Call, 2026-04-02)*
- **Links:**

---

### 2026-03-05 — Zero-to-one insurance is too hard as starting point

- **Status:** accepted
- **Owners:** Manav
- **Context:** Two paths: (1) individual market — most people decide on brand, not cost; (2) employer — must convince brokers, employers won't sign up unless brand name. Manav talked to ~10 former Oscar senior people (head of commercial small group, head of network, head of ICHRA, CEO/founder, etc.) — "all told me it's not worth it." Harbor Health's CEO formerly founded an insurance product and recommends not doing it again. *(WhatsApp, 2026-03-05, Manav)*
- **Decision:** Don't start with zero-to-one insurance. Build distribution first, then expand into insurance.
- **Alternatives:** Acquiring captive plans (promising and novel). Acquiring a TPA. *(WhatsApp, 2026-03-05, Manav)*
- **Follow-ups:** Vaibhav agreed captive research is promising. *(WhatsApp, 2026-03-05, Vaibhav)*
- **Links:**

---

### 2026-03-02 — Work division: open questions to tackle

- **Status:** accepted
- **Owners:** Manav, Vaibhav
- **Context:** Manav outlined 8 open questions after call. *(Email: "Open questions / plan to tackle", 2026-03-02, Manav)*
- **Decision:** Manav prioritizes Q1 (consumer app vs. insurance stack timing), Q4 (market segmentation), Q6 (commercial small group vs. self-funded). Vaibhav prioritizes Q2 (app scope), Q3 (triage engine build vs. buy), Q5 (market map). Output: detailed perspectives with supporting data by March 14.
- **Alternatives:**
- **Follow-ups:** Vaibhav delivered Q2, Q3, Q5 on 2026-03-09. Manav responded same day.
- **Links:**

---

### 2026-01-19 — Collaboration kickoff: spec + GTM + coworking

- **Status:** accepted
- **Owners:** Manav, Vaibhav
- **Context:** After in-person brainstorming. *(Email: Chat thread, 2026-01-19, Manav)*
- **Decision:** Vaibhav to create a short spec for V1 based on new architecture diagram. Both independently think through ideal GTM/acquisition strategy. Set up Slack workspace. Find time to sync live weekly.
- **Alternatives:**
- **Follow-ups:** Slack workspace created. *(Email: Chat thread, 2026-01-19, Manav)*
- **Links:**

---

Entry template:

```
### YYYY-MM-DD — Title

- **Status:** proposed | accepted | superseded
- **Owners:**
- **Context:**
- **Decision:**
- **Alternatives:**
- **Follow-ups:**
- **Links:**
```

---
