# Portal Scan — 2026-10-15 — Prernaa Agarwal

**Candidate profile applied:**
- Roles: Product Manager, Product Owner, AI Product Manager
- Location policy: Remote preferred — Bangalore / Dubai hubs, countries: India, UAE, Singapore, Germany, Malaysia, Thailand, Luxembourg, Denmark, Spain, Netherlands
- Target comp: ~45 LPA (INR) minimum

**Scope of the scan**

Direct ATS APIs (Greenhouse / Ashby / Lever) are blocked by the sandbox network policy from this session, so this scan used targeted WebSearch queries across the same portals (Greenhouse, Ashby, Lever, Y Combinator, Workable, FoundIt, Jobstreet, Bayt, GulfTalent) plus aggregators (DailyRemote, Internshala, Jobgether), covering 10 countries. 43 postings passed the title + negative-keyword filter; all are now in `data/pipeline.md`.

The scanner did NOT verify liveness. Some older postings may be closed — verify each listing before applying.

---

## Top 15 — ranked by fit

### Tier 1 — Strong fit (AI PM + target location)

1. **Insider One — Senior AI Product Manager, B2B SaaS Martech** · Europe (remote) · `fit 7`
   https://jobs.lever.co/insiderone/a2c2944d-a53b-4c40-9a51-1a8ca69db18a
   AI PM in Martech, pan-EU remote (Amsterdam / Berlin / Munich / etc.). Direct hit on AI PM archetype.

2. **InMobi — Senior Product Manager, AI/ML** · Bangalore · `fit 6`
   https://boards.greenhouse.io/inmobi/jobs/5005066
   Bangalore-based AI/ML PM at an established AdTech unicorn. Perfect location, home turf.

3. **Jobgether (partner) — Senior Product Manager (Telephony/VoIP/IVR, GenAI/LLM)** · India remote · `fit 6`
   https://jobs.lever.co/jobgether/bef14e8e-9edd-4965-ad0d-4a59e0f60044
   Voice-AI PM remote India. GenAI + LLMs + voice infra. Partner-mediated application.

4. **HighLevel — Senior Product Manager, AI Growth** · India remote/hybrid · `fit 6`
   https://www.marketingmonk.so/jobboard/jobs/sr-product-manager-ai-growth-at-highlevel-kolzkh
   AI Growth PM, remote India. Mid-sized SaaS, growth-centric.

5. **Yassir — AI Product Manager** · Dubai / Abu Dhabi / Remote India · `fit 6`
   https://jobs.lever.co/Yassir/3ac148b1-6b81-4020-9914-68ff5ebd6c2e
   One of the rare roles that explicitly allows Dubai, Abu Dhabi, AND remote India — matches two priority locations.

6. **n8n — AI Product Manager** · Berlin / Remote NL · DE · ES · `fit 6`
   https://jobs.ashbyhq.com/n8n/42e72645-d99a-4545-97b7-53ba3a699893
   Workflow automation platform. Remote within her 3 EU target countries. AI PM title.

7. **Hopper — Senior Product Manager, Commerce AI & Platform** · Spain 100% remote · `fit 6`
   https://jobs.ashbyhq.com/hopper/4b2553ae-85d8-41e3-a43b-4fd0ecfc82d3
   Senior AI/Platform PM, fully remote within Spain. Big travel brand.

8. **Gigster — Product Manager, Applied AI (Worldwide)** · Remote worldwide · `fit 6`
   https://job-boards.greenhouse.io/gigster/jobs/5559602004
   Rare truly-worldwide AI PM. Would fit from Bangalore directly.

### Tier 2 — Good fit (senior PM + target location, AI adjacent)

9. **Couchbase — Senior Product Manager, Search / Indexing / Vector / Hybrid Search** · Bangalore hybrid · `fit 5`
   https://job-boards.greenhouse.io/couchbaseinc/jobs/4701380006

10. **Karat — Principal Product Manager (India)** · Bangalore remote-India · `fit 5`
    https://job-boards.greenhouse.io/karat/jobs/8589269002

11. **VectorShift — Product Manager, Platform (India)** · India remote · `fit 5`
    https://www.ycombinator.com/companies/vectorshift/jobs/j3yK75d-product-manager-platform-india
    YC-backed AI agents platform. Caveat: listed pay $20–40k, below her 45 LPA floor.

12. **Salt (via welovesalt) — AI Product Manager** · Dubai, UAE · `fit 5`
    https://welovesalt.com/jobs/ai-product-manager-711475

13. **Remote.com — Product Manager, Billing Platform (AI-tooling required)** · Germany remote · `fit 5`
    https://job-boards.greenhouse.io/remotecom/jobs/7822621003

14. **Grafana Labs — Staff Product Manager, OpenTelemetry** · Germany remote · `fit 5`
    https://job-boards.greenhouse.io/grafanalabs/jobs/6161254004

15. **Grafana Labs — Product Manager, AI** · Germany remote · `fit 5`
    https://job-boards.greenhouse.io/grafanalabs/jobs/5796211004

---

## Distribution

| Location bucket | Count |
|---|---|
| On-site primary (Bengaluru) | 12 |
| Remote India | 7 |
| Remote Germany | 5 |
| Hybrid Bengaluru | 4 |
| Remote EU (any) | 3 |
| Remote Netherlands | 3 |
| Remote Denmark | 3 |
| Remote worldwide | 2 |
| Remote Spain | 1 |
| Remote Singapore | 1 |
| Unspecified location | 2 |

Full list of 43 postings is in `data/pipeline.md`.

---

## Suggested next step

Run `/career-ops pipeline` to evaluate the top 15 one by one (A-F scoring + liveness check + Blocks). Prernaa should NOT apply blindly — each report will produce a 0-5 fit score, and the system is tuned to recommend AGAINST applying to anything below 4.0.

## Caveats / things to double-check

- Several Jobgether postings are the same role duplicated across EU countries — expect dedup when evaluating.
- Databricks "New Grad (2026)" was auto-filtered down in ranking but kept in the pipeline for completeness; it's an APM track, not a senior role.
- Prosper AI (Barcelona) is on-site, which conflicts with "Remote preferred" — kept because Spain is a priority country.
- Comp field in `config/profile.yml` reads `target_range: "<45lpa"` and `minimum: "45LPA"` — these contradict. Treated 45 LPA as the floor. Confirm when back.
- Portfolio `narrative.proof_points` in profile.yml still has example placeholders (Jane Smith's "Project Alpha"). Will need her real proof points before CV generation.
