# Strategy → build

**Last updated:** 2026-04-02

| Strategy priority | Outcome | Links | Owner | Status |
|-------------------|---------|-------|-------|--------|
| AI triage + care guidance | Conversational, contextual to member history and plan | | | Not started |
| Provider quality + cost matching | Data-driven recommendations by outcomes and cost for specific condition — not just in-network | | | Not started |
| Transactional completion | Book appointment, confirm coverage, show out-of-pocket before member walks in | | | Not started |
| Orchestration layer | Existing clinical APIs (e.g. Infermedica) + commercial LLMs + hard-coded safety rules + integration with our provider network, benefits/coverage, claims | | | Not started |
| Employer analytics dashboard | Track healthcare utilization, predict spend, recommend benefits | | | Not started |

Sources: *(Email: "Open questions", 2026-03-09, Vaibhav; V1 Memo, p.3–7)*

## Dependencies

| Dependency | Type | Status |
|------------|------|--------|
| Provider directory + pricing data integration | Data | Not started |
| Claims / medical records access (via TPA or employer) | Data | Not started — identified as key bottleneck *(Email: "Open questions", 2026-03-09, Vaibhav)* |
| Clinical decision-making QA data (e.g. OpenEvidence, UpToDate) | Data | Not started *(V1 Memo, p.7)* |
| Epidemiological data (e.g. CDC outbreak maps) | Data | Not started *(V1 Memo, p.7)* |
| Deeper spec on agents and data sources | Design | Manav flagged need to "go one layer deeper" *(Email: "Open questions", 2026-03-09, Manav)* |
