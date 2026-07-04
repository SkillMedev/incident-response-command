# Incident Response Command

**For engineers who own production: run incidents calmly and defend reliability on-call.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Reach for this when you own a service on-call and want incidents to be routine, not chaos. It carries you through the whole lifecycle — instrument and de-noise your signals, call severity fast, work the runbook, keep customers honestly informed, hand the shift off cleanly, write the blameless postmortem, and turn SLO error budgets into automatic team decisions. The outcome: faster, calmer responses, less alert fatigue, and reliability that holds up instead of eroding. Built for engineers and SREs who carry the pager.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/incident-response-command](https://skillme.dev/pack/incident-response-command) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/incident-response-command`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[SEV Triage](skills/sev-triage/SKILL.md)** — Classify incident severity (SEV1-4) using impact, scope, and urgency signals.
- **[Runbook Writer](skills/runbook-writer/SKILL.md)** — Writes an operational runbook for a service covering symptoms, diagnostic checks, mitigations, and escalation paths.
- **[Status Page Update](skills/status-page-update/SKILL.md)** — Writes clear, honest customer-facing incident status updates at each lifecycle stage: investigating, identified, monitoring, and resolved.
- **[On-Call Handoff](skills/oncall-handoff/SKILL.md)** — Produces a crisp on-call shift handoff note covering open incidents, watch items, recent changes, and context the incoming engineer needs.
- **[Alert Tuning](skills/alert-tuning/SKILL.md)** — Reduces alert noise by making alerts actionable, symptom-based, and tied to SLOs.
- **[Error Budget Policy](skills/error-budget-policy/SKILL.md)** — Defines and applies an SLO error-budget policy that gates feature work versus reliability work based on remaining budget.
- **[Observability Stack](skills/observability-stack/SKILL.md)** — Instruments applications with structured logs, metrics, and distributed traces.
- **[Postmortem Writer](skills/postmortem-writer/SKILL.md)** — Writes blameless postmortems with timeline, contributing factors, action items, and learning.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
