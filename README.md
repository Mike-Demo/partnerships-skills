# Skills for Partnership teams

> Partner ecosystem operations, from channel program design to creator payouts.

A collection of agent skills covering the full **partnerships** surface: channel and alliance strategy, co-selling policy, affiliate program mechanics, referral incentives, and influencer deals.

Built for **partner managers, BD leads, affiliate managers, and ecosystem heads** who own partner revenue.

Every skill produces a **decision-ready artifact**: a scorecard, a policy, a rate card, a signed-off spec, not a generic checklist.

## Related Collections

Other skills repositories I built for my colleagues at **Nativa Labs**:

- [`advertising-skills`](https://github.com/mbfinotti/advertising-skills): Ad platform mastery: _for performance marketers, paid media managers, growth leads_
- [`revops-skills`](https://github.com/mbfinotti/revops-skills): Revenue operations: _for RevOps managers, sales ops, marketing ops, CRM admins_
- [`sales-skills`](https://github.com/mbfinotti/sales-skills): Sales execution: _for SDRs, AEs, sales managers, heads of sales_

## Install

Install every skill in this repo, not just one. Skills here are atomic by design and reference each other freely: picking a single skill leaves its sibling skills uninstalled, so cross-references and routed handoffs go nowhere.

**skills.sh (universal)**: works with any Agent Skills-compatible tool:

```bash
npx skills add mbfinotti/partnerships-skills
```

**Claude.ai**:

1. add as a plugin marketplace: open **Settings -> Capabilities -> Plugins**
2. click **Add -> Add marketplace -> Add from a repository**
3. enter `mbfinotti/partnerships-skills`
4. then **Sync**

**Claude Code**: install the plugin:

```bash
/plugin marketplace add mbfinotti/partnerships-skills
/plugin install partnerships-skills@partnerships-skills
```

**Codex (OpenAI)**: install via the Codex CLI:

```bash
codex plugin add github:mbfinotti/partnerships-skills
```

**Cursor**: copy into Cursor's skills directory:

```bash
git clone https://github.com/mbfinotti/partnerships-skills.git ~/.cursor/skills/partnerships-skills
```

Cursor auto-discovers skills from `.agents/skills/` and `.cursor/skills/`.

**Gemini CLI**: install as a Gemini extension:

```bash
gemini extensions install https://github.com/mbfinotti/partnerships-skills
```

Update with `gemini extensions update partnerships-skills`.

## Skills

This collection covers the full partnerships surface.

### Start here

[`partnerships-kickoff`](./skills/partnerships-kickoff): Routes a partnerships task to exactly one sibling skill and bootstraps the shared project context file so the next session starts warm.

### Meta

- [`partnerships-career`](./skills/partnerships-career): Plans a partnerships career from the candidate side: which of the four sub-disciplines to target, breaking in, interview prep, offer evaluation.
- [`partnerships-hiring`](./skills/partnerships-hiring): Plans partnerships hiring from the employer side: job posting and scorecard, interview loop, sourcing, compensation stance.

### Ecosystem strategy

- [`partner-ecosystem`](./skills/partner-ecosystem): Maps every partner type, account overlap, coverage gap, and conflict zone into a weighted scorecard and prioritization 2x2.
- [`alliance-prioritization`](./skills/alliance-prioritization): Ranks named candidate alliances by expected value, effort, and risk into a shortlist and a go/no-go recommendation memo.
- [`partner-economics`](./skills/partner-economics): Models one partner's P&L - margin, cost-to-serve, partner CAC, ramp, payback - to decide sign, scale, renegotiate, or exit.
- [`partner-ecosystem-expansion`](./skills/partner-ecosystem-expansion): Sequences which partner categories to launch next into a staged roadmap with readiness gates, capacity limits, and kill criteria.
- [`partner-marketplace-strategy`](./skills/partner-marketplace-strategy): Ranks candidate cloud, app store, and retail marketplaces by expected ROI, and sets the delist trigger for each.
- [`joint-gtm-planning`](./skills/joint-gtm-planning): Plans one joint go-to-market motion with a named partner: value proposition, campaign shape, budget, lead-sharing agreement.

### Channel program

- [`partner-channel-program`](./skills/partner-channel-program): Designs a partner program from scratch: readiness gate, partner value proposition, motions, tiers, benefits, economics envelope.
- [`partner-tiering`](./skills/partner-tiering): Designs the tier ladder inside an existing program: qualification criteria, benefit bundles, promotion and demotion rules, base migration.
- [`partner-enablement`](./skills/partner-enablement): Sequences the training, content, and certification roadmap that carries a partner to their first closed deal.
- [`co-selling-strategy`](./skills/co-selling-strategy): Defines how direct and partner sellers share deals: registration policy, deal credit splits, rules of engagement, comp neutrality.
- [`partner-channel-conflict`](./skills/partner-channel-conflict): Writes the channel conflict rules for contested deals: account segmentation, carve-outs, tie-breaks, escalation and adjudication ladders.
- [`partner-performance`](./skills/partner-performance): Builds the per-partner scorecard, QBR structure, and underperformance ladder from first trigger through de-tier or exit.

### Affiliate program

- [`affiliate-program-terms`](./skills/affiliate-program-terms): Drafts the clause-complete affiliate agreement: prohibited tactics, enforcement ladder, clawback mechanics, jurisdiction overlays.
- [`affiliate-commission-structure`](./skills/affiliate-commission-structure): Sets the commission rate model, tiers, recurring duration and caps, cookie window, and clawback terms from unit economics.
- [`affiliate-recruitment-outreach`](./skills/affiliate-recruitment-outreach): Drafts the recruitment pitch and follow-up sequence that brings content sites, newsletters, and communities into a program.
- [`affiliate-onboarding-sequence`](./skills/affiliate-onboarding-sequence): Designs the touch plan and asset kit that carry a newly approved affiliate from approval to first tracked conversion.
- [`affiliate-performance-dashboard`](./skills/affiliate-performance-dashboard): Specifies the affiliate dashboard: metric formulas, views per audience, refresh cadence, and alert thresholds.
- [`affiliate-payout-audit`](./skills/affiliate-payout-audit): Audits a commission payout run before disbursement and returns findings by severity with recommended holds.
- [`affiliate-fraud-detection`](./skills/affiliate-fraud-detection): Builds the rule set that flags cookie stuffing, fake leads, and self-referral rings, plus the investigation and escalation path.
- [`affiliate-disclosure-compliance`](./skills/affiliate-disclosure-compliance): Reviews a specific post, script, or live URL against FTC, UK, and EU disclosure rules and returns a pass/fail verdict with fixes.

### Referral

- [`referral-incentive-design`](./skills/referral-incentive-design): Sets who gets rewarded, reward type, amount against LTV and margin, payout trigger, and whether to build a tiered ladder.
- [`referral-abuse-guardrails`](./skills/referral-abuse-guardrails): Specifies the caps, velocity limits, hold windows, verification gates, and enforcement ladder that stop referral gaming.

### Influencer & creator

- [`influencer-discovery-brief`](./skills/influencer-discovery-brief): Defines weighted sourcing criteria and knockout screens, then produces a ranked creator shortlist with evidence per score.
- [`influencer-outreach`](./skills/influencer-outreach): Drafts the personalized first-touch pitch to one vetted creator, on the channel they list, with a bounded follow-up cadence.
- [`influencer-negotiation-playbook`](./skills/influencer-negotiation-playbook): Prepares term-by-term opening positions, a concession ladder, and walk-away thresholds for rates, usage rights, and exclusivity.
- [`influencer-campaign-brief`](./skills/influencer-campaign-brief): Writes the creative brief for a signed creator: deliverable specs, key messages, guardrails, disclosure, bounded review rounds.
- [`influencer-measurement-framework`](./skills/influencer-measurement-framework): Designs the pre-launch measurement plan: KPIs per objective, attribution method behind each, reporting cadence, declared blind spots.

## Security audit triage — 2026-10-21

Parent: [Mike-Demo/partnerships-skills#1](https://github.com/Mike-Demo/partnerships-skills/issues/1).
Issue creation is unavailable in this session; the two titles and bodies below are ready to file in this repository. This is a documentation-only triage backlog, not a remediation. The supplied audit used static inspection only; no audited code was executed and no deployed endpoint was probed.

### Priority

1. **Low — eval-id path traversal writes.** The only confirmed finding is reachable when an operator runs the harness against contributor-controlled, committed eval data. It is not an unauthenticated network entry point. Writes use the operator's permissions, but trial output and grading JSON have constrained filenames and content; this is not a demonstrated arbitrary-content write or code-execution finding. Load-time ID validation and write-path containment are a small, localized fix. Trial and objective/subjective grading writes share the same unchecked-ID root cause and belong in one remediation issue.

The four leads remain unconfirmed and unranked: their missing runtime or provenance facts must be established before assigning severity or placing them in the confirmed remediation queue.

### Ready-to-file issue 1

**Title:** `[security][low] Constrain eval IDs and harness output paths`

**Body:**

Parent audit: https://github.com/Mike-Demo/partnerships-skills/issues/1

Fingerprint: `harness-eval-id-path-traversal-writes`

**Priority and reachability:** First and only confirmed remediation item; low severity. A contributor who can supply committed eval data can influence output paths when an operator runs that skill's harness. Execution and filesystem write permissions come from the operator. The audit does not establish unrestricted filenames, arbitrary attacker-chosen file contents, or code execution.

**Evidence (static inspection):**

- [Eval loading, lines 589–593](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L589-L593) takes `data["evals"]` from the skill's `evals/evals.json` without validating IDs.
- [Trial writes, lines 172–186](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L172-L186) build `outdir / "trials" / f"eval-{ev['id']}" / cond / "output.md"`, create parent directories, and call `write_text`.
- [Objective grading, lines 299–337](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L299-L337) and [subjective grading, lines 346–363](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L346-L363) interpolate the same ID into grading paths. [`_merge`, lines 256–266](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L256-L266) creates directories and writes JSON without a containment check.
- A string ID containing slash and parent-directory segments can resolve outside the intended output directory. The `eval-` prefix does not stop traversal through later path components.

**Root cause and grouping:** IDs are treated as opaque values suitable for path interpolation, without type/character validation or resolved-path containment. Trial and both grading writers are manifestations of this single root cause.

**Smallest fix:** Validate every ID immediately after loading eval data, before model calls or output writes: accept integers (not booleans), or strings matching `^[A-Za-z0-9_-]+$`; reject other values. Before every write in `run_trials` and `_merge`, require the resolved destination to be a descendant of resolved `outdir`, rejecting the run otherwise. Pass `outdir` into `_merge` so it can enforce that boundary, and check before creating parent directories too. Preserve existing filenames and valid-ID behavior.

**Acceptance checklist (for the remediation, not this triage):**

- [ ] Valid integer and safe-string IDs retain existing trial and grading output behavior.
- [ ] Reject traversal, separators, empty strings, booleans, and other invalid ID types before invoking the model or writing outputs.
- [ ] Trial, objective grading, and both subjective grading passes reject destinations resolving outside `outdir`, including existing symlinks escaping the boundary; no outside file or directory is created or modified.

### Ready-to-file issue 2

**Title:** `[security][needs-validation] Audit leads to validate`

**Body:**

Parent audit: https://github.com/Mike-Demo/partnerships-skills/issues/1

These are leads, not confirmed vulnerabilities. No severity is assigned. Validate only in an authorized, isolated environment with synthetic data; do not use production credentials or probe deployed endpoints. Missing-fact quotations below preserve the parent issue verbatim, including its truncated ellipses; omitted text is not inferred.

- [ ] **Eval harness subprocess permissions and inherited environment**
  - Fingerprint: `harness-claude-subprocess-inherits-env-no-tool-allowlist`
  - Claimed root cause/evidence: [CLI setup and `claude()`, lines 47–78](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L47-L78) inherit the operator environment except `CLAUDECODE`, disable MCP, and load user settings without a source-level tool allowlist. [Trial prompts, lines 161–179](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_skill.py#L161-L179) embed contributor-controlled prompts and direct skill/reference reads.
  - **Exact missing fact:** The installed claude CLI version's default permission and tool behavior in -p mode on the operator's machine, together with the operator's user-level settings loaded via --setting-sources user: specifically, whether a trial subprocess can execute Read, Bash, or Write tool calls without interactive approval. This runtime fact is outside the reposit…
  - Validation record needed: CLI version, redacted effective settings, and isolated approval/tool-call observations for Read, Bash, and Write.

- [ ] **Kickoff context propagation into memory and agent instructions**
  - Fingerprint: `kickoff-context-artifact-trusted-and-propagated`
  - Claimed root cause/evidence: [Context artifact and memory flows, lines 186–202](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/skills/partnerships-kickoff/SKILL.md#L186-L202) make the artifact the source of truth, derive memory from it, and optionally patch project agent instructions. The explicit diff/approval gate addresses git-resident memory commits, not every host write.
  - **Exact missing fact:** Whether the deploying agent host persists memory entries derived from partnerships-context.md and patches the project's agent-instruction file without showing the user a diff and obtaining approval. The skill's own approval gate covers only git-resident memory commits; host behavior for the other writes is not determinable from this repository.
  - Validation record needed: Host/version and observed diff/approval behavior for each persistence destination using a synthetic context artifact.

- [ ] **Manifest-derived names interpolated into an inner shell**
  - Fingerprint: `run-batch-manifest-name-shell-injection`
  - Claimed root cause/evidence: [Name splitting, lines 21–25](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_batch.sh#L21-L25), [inner shell interpolation, lines 37–52](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_batch.sh#L37-L52), and [manifest dispatch, lines 57–63](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/evals/_harness/run_batch.sh#L57-L63) show names entering shell source rather than remaining data. Contributor reachability through the external manifest producer is unknown.
  - **Exact missing fact:** How skill-wip/manifest.json keys are produced in the operator's skill-wip checkout (absent from this repo): whether a contributor can land a repo or skill directory whose name contains a slash-free dollar-paren or backtick payload and have that exact string entered as a manifest key that run_batch.sh dispatches.
  - Validation record needed: External manifest-generation code, naming restrictions, and contributor-to-dispatched-key provenance. Do not run the live commit-and-push script to investigate.

- [ ] **Third-party fetched content lacks a skill-level instruction boundary**
  - Fingerprint: `untrusted-fetched-content-no-instruction-boundary`
  - Claimed root cause/evidence: [Disclosure review, line 48](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/skills/affiliate-disclosure-compliance/SKILL.md#L48) and [creator-post review, line 49](https://github.com/Mike-Demo/partnerships-skills/blob/d0da5e16b8388111bd36b80fc8641f9231d818f9/skills/influencer-outreach/SKILL.md#L49) direct ingestion of third-party content without an explicit skill-level instruction to disregard embedded directives. Host protections and authority remain unknown.
  - **Exact missing fact:** What instruction-hierarchy protection and tool authority the host agent session provides while following these two skills: specifically, whether content fetched from a reviewed URL or a creator's posts is fenced as data by the host, and what tools (files, connectors, memory, sending) that session could act on if embedded directives were followed. …
  - Validation record needed: Host/version, fetched-content fencing, and effective file, connector, memory, and sending permissions for both skills using controlled fixtures.

For each checkbox, record evidence and disposition (confirmed, rejected, or still needs validation). Only a confirmed result should receive a severity and a separate remediation issue linked to the parent; static absence of a guard alone does not settle these leads.

## License

MIT © 2026 Maya-Beth Finotti
