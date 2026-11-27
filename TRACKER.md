# CCAR-P Study Tracker

**Exam:** Claude Certified Architect – Professional, Dec 31, 2026 (early morning), booked via Pearson VUE
**Planned:** 42.5 hrs over 5 weeks (~8.5 hrs/week)
**Legend:** 📱 phone-friendly · 💻 needs the Mac

To mark a task done, change `[ ]` to `[x]`. Add a short note after the task if useful.

---

## Week 1 · Nov 25 – Dec 1 · Setup and design

- [x] 📱 Register on Partner Academy with IBM email; confirm partner tier and exam price · 0.5h · due Nov 27 · Logistics · [Cert FAQ](https://anthropic-partners.skilljar.com/page/faq-certifications) — *price confirmed $0*
- [x] 📱 Check IBM internal page for the free-until-year-end offer · 0.25h · due Nov 27 · Logistics
- [x] 📱 Book Pearson exam slot · 0.25h · due Nov 28 · Logistics · [Pearson VUE – Anthropic](https://www.pearsonvue.com/anthropic) — *booked Dec 31, early morning; system test passed on IBM Mac*
- [ ] 📱 Read the new CCAR-P exam guide end to end; list unfamiliar topics · 2h · due Nov 30 · All · [Partner Academy → CCAR-P page](https://anthropic-partners.skilljar.com)
- [ ] 💻 Write 1-page project brief: users, success metrics, budget per book, data limits · 1.5h · due Nov 30 · Solution Design; Stakeholder
- [ ] 💻 Sketch architecture + 2–3 ADRs (orchestrator, review subagents, findings store) · 1.5h · due Dec 1 · Solution Design
- [ ] 💻 New repo; Agent SDK hello-world agent running · 1.5h · due Dec 1 · Integration · [Claude docs](https://docs.claude.com)

## Week 2 · Dec 2 – 8 · Core build

- [ ] 📱 Academy course: Building with the Claude API · 2h · due Dec 8 · Integration; Models · [Anthropic Academy](https://academy.claude.com)
- [ ] 💻 Continuity review subagent returning structured JSON findings with cited passages · 3h · due Dec 7 · Integration; Models · [Claude docs (tool use)](https://docs.claude.com)
- [ ] 💻 MCP server that serves chapters and the series bible · 2h · due Dec 7 · Integration · [Claude docs (MCP)](https://docs.claude.com)
- [ ] 💻 Model routing (Haiku summaries, Sonnet reviews) + prompt caching for the bible · 1.5h · due Dec 8 · Models & Context · [Claude docs (prompt caching)](https://docs.claude.com)
- [ ] 💻 Retries, rate limits, timeouts, fallback model · 1h · due Dec 8 · Integration · [Claude docs (rate limits)](https://docs.claude.com)

## Week 3 · Dec 9 – 15 · Evaluation

- [ ] 📱 Read Anthropic docs on evals and testing; Intro to MCP refresher · 1.5h · due Dec 15 · Evaluation · [Claude docs](https://docs.claude.com) · [Anthropic Academy](https://academy.claude.com)
- [ ] 💻 Plant 15–20 known errors in a sample chapter (test set) · 1h · due Dec 13 · Evaluation
- [ ] 💻 Eval script: precision/recall + LLM judge for finding quality · 2.5h · due Dec 14 · Evaluation · [Claude docs (evals)](https://docs.claude.com)
- [ ] 💻 Track cost and latency per chapter · 1h · due Dec 14 · Evaluation · [Claude docs (pricing)](https://docs.claude.com)
- [ ] 💻 One tuning round; re-run evals; note before/after · 1.5h · due Dec 15 · Evaluation

## Week 4 · Dec 16 – 22 · Governance and lifecycle

- [ ] 📱 Read docs on guardrails, data handling, human-in-the-loop patterns · 1.5h · due Dec 22 · Governance · [Claude docs (guardrails)](https://docs.claude.com)
- [ ] 💻 Schema validation; reject findings without a cited passage · 1h · due Dec 20 · Governance
- [ ] 💻 Human approval step before any fix is applied · 1h · due Dec 20 · Governance
- [ ] 💻 Audit log of every model call (prompt version, model, tokens) · 1h · due Dec 21 · Governance; Lifecycle
- [ ] 📱 Write risk register, runbook and 1-page stakeholder update · 2h · due Dec 21 · Stakeholder & Lifecycle
- [ ] 💻 Prompt versioning + CLAUDE.md, commands and hooks for the repo · 1h · due Dec 21 · Dev Productivity · [Claude Code docs](https://docs.claude.com)
- [ ] 💻 Practice test #1; list weak domains · 2h · due Dec 22 · All · [Educative CCAR-P (3rd party)](https://www.educative.io/courses/claude-certified-architect-professional-exam)

## Week 5 · Dec 23 – 31 · Review and exam

- [ ] 📱 Review weak domains in short sessions · 3h · due Dec 27 · Weak domains · [Claude docs](https://docs.claude.com)
- [ ] 📱 1-page cheat sheet mapping each domain to your project · 1h · due Dec 27 · All
- [ ] 💻 Practice test #2 · 2h · due Dec 27 · All · [Whizlabs CCAR-P (3rd party)](https://www.whizlabs.com/claude-certified-architect-professional/)
- [ ] 💻 Exam logistics: ID ready, re-run system test, VPN off, quit Slack/Teams, room check · 0.5h · due Dec 30 · Logistics · [Pearson VUE – Anthropic](https://www.pearsonvue.com/anthropic)
- [ ] 💻 **Take the CCAR-P exam** · 2h · Dec 31 · Exam

---

## Roadmap (after the exam)

Not in scope before Dec 31. Revisit in January.

- [ ] **Phase 2: Marketing agent.** A subagent that drafts blurbs, taglines, newsletter copy and ad variations from chapter summaries, with an eval that compares versions.

---

## Exam domains (CCAR-P)

| Domain | Weight |
|---|---|
| Integration | 19% |
| Solution Design and Architecture | 17% |
| Evaluation, Testing and Optimization | 16% |
| Governance, Safety and Risk Management | 14% |
| Stakeholder Communication and Lifecycle Management | 14% |
| Claude Models, Prompting and Context Engineering | 13% |
| Developer Productivity and Operational Enablement | 7% |

Format: 63 scored items, 120 minutes, pass at 720 / 1000. Content updated Dec 7, 2026; study from the new exam guide.

## Notes and unfamiliar topics

<!-- Add topics flagged while reading the exam guide here. -->
