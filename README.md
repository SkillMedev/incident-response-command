# Incident Response Command

**For engineers who own production: run incidents calmly and defend reliability on-call.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you own a service on-call and want incidents to be routine, not chaos. It carries you through the whole lifecycle - instrument and de-noise your signals, call severity fast, work the runbook, keep customers honestly informed on the status page and run the external crisis comms (first statement inside the hour, speculation never), hand the shift off with a completeness checklist, write the blameless postmortem on the 48-hour clock with the five-whys-stops-at-process rule, and turn SLO error budgets into automatic team decisions. Templates and severity thresholds included at every step. Built for engineers and SREs who carry the pager.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/incident-response-command](https://skillme.dev/pack/incident-response-command) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/incident-response-command`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[SEV Triage](skills/sev-triage/SKILL.md)** — Classifies incident severity (SEV1-4) using impact, scope, and urgency signals and decides who to page.
- **[Runbook Writer](skills/runbook-writer/SKILL.md)** — Writes an operational runbook for a service covering symptoms, diagnostic checks, mitigations, and escalation paths.
- **[Status Page Update](skills/status-page-update/SKILL.md)** — Writes customer-facing incident status updates for each lifecycle stage - investigating, identified, monitoring, resolved - with cadence rules and plain-language templates.
- **[Crisis Comms External](skills/crisis-comms-external/SKILL.md)** — Drafts and sequences external communications during an incident or crisis - a first statement within the hour, acknowledge-what-you-know-without-speculating discipline, a single-spokesperson rule, channel sequencing from status page to email to social, and a legal-review escalation boundary, with severity-tiered statement templates.
- **[On-Call Handoff](skills/oncall-handoff/SKILL.md)** — Produces a complete on-call shift handoff note - shift summary, open incidents, watch items with paging thresholds, silenced alerts, in-flight changes, and escalation contacts - checked against a completeness checklist.
- **[Alert Tuning](skills/alert-tuning/SKILL.md)** — Reduces alert noise by making alerts actionable, symptom-based, and tied to SLOs.
- **[Error Budget Policy](skills/error-budget-policy/SKILL.md)** — Defines and applies an SLO error-budget policy that gates feature work versus reliability work based on remaining budget.
- **[Observability Stack](skills/observability-stack/SKILL.md)** — Instruments systems with the three pillars - structured logs, RED/USE metrics, and distributed traces - correlated by one trace ID, with cardinality budgets and symptom-based alerts.
- **[Postmortem Writer](skills/postmortem-writer/SKILL.md)** — Writes blameless incident postmortems with a log-reconstructed timeline, multi-causal contributing factors, and owned, dated action items.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
