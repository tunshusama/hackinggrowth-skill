---
name: hacking-growth-playbook
description: Apply the Hacking Growth methodology to diagnose growth bottlenecks, design and prioritize experiments, and run a weekly growth process with measurable outcomes. Use when users ask for growth strategy, growth loops, AARRR funnel optimization, activation/retention improvements, experiment backlogs, or growth team operating cadence.
---

# Hacking Growth Playbook

Run this workflow to turn vague growth goals into a concrete experiment system.

## 0) Route by product archetype

Classify the product first, then apply matching playbooks from `references/archetypes-and-cases.md`.

Use one primary archetype:
- `marketplace`: two-sided supply-demand matching
- `social-content`: user-generated content and network effects
- `plg-saas`: self-serve product-led growth software
- `ecommerce`: catalog, cart, checkout, repeat purchase
- `developer-tool`: API/SDK/docs-led adoption

If mixed model, choose the current bottleneck archetype only.

## 1) Frame the mission

Collect:
- Product type and current stage (0-1, PMF search, scale)
- Primary business goal (users, revenue, retention, referral)
- Time window and constraints (team, budget, data access)
- Current core metrics (traffic, signup, activation, retention, conversion, ARPU)

Define:
- One primary outcome metric for this cycle
- One to three guardrail metrics to avoid local optimization

## 2) Find the bottleneck

Map the user journey in funnel form:
- Acquisition -> Activation -> Retention -> Revenue -> Referral

Estimate where the largest drop or friction lives.

Pick one bottleneck only. Avoid spreading effort across many stages in the same cycle.

## 3) Build hypotheses

Generate hypotheses in this format:
- If we change `[lever]` for `[segment]`, then `[primary metric]` will improve because `[behavior mechanism]`.

Use these lever families:
- Acquisition: channel-message match, landing conversion, intent fit
- Activation: time-to-value, onboarding friction, first win completion
- Retention: habit triggers, recurring value delivery, lifecycle nudges
- Revenue: packaging, pricing, paywall timing, expansion prompts
- Referral: sharing moments, incentive design, invitation UX

## 4) Prioritize with ICE

Score each idea on:
- Impact (1-10)
- Confidence (1-10)
- Ease (1-10)

Compute ICE = (Impact + Confidence + Ease) / 3.

Select:
- 1 high-confidence/high-impact test
- 1 fast validation test
- Optional 1 exploratory test if capacity allows

## 5) Design experiment cards

For each selected test, define:
- Hypothesis
- Primary metric and expected lift
- Guardrail metrics
- Target segment
- Experiment type (A/B, quasi-experiment, cohort holdout, before-after)
- Exposure rule and sample logic
- Start and stop criteria
- Owner and decision date

Reject experiments without a clear decision rule.

## 6) Run weekly growth cadence

Execute in a weekly loop:
- Monday: finalize designs and instrumentation checks
- Midweek: launch and monitor data quality
- End week: read results, decide ship/iterate/kill, capture lessons

Keep a single backlog with statuses:
- `idea` -> `designed` -> `running` -> `won` / `lost` / `inconclusive` -> `scaled`

## 7) Produce outputs

Return outputs in this order:
1. Bottleneck diagnosis (one paragraph)
2. Prioritized backlog table (top 5-10 tests)
3. Detailed cards for top 1-3 experiments
4. Weekly operating plan (owners + checkpoints)
5. Risks and instrumentation gaps

Use `references/templates.md` for exact templates.
Use `references/archetypes-and-cases.md` to inject archetype-specific tactics and book-style examples.

## Decision heuristics

- Fix activation and retention before scaling acquisition when churn is high.
- Prefer behavior change over cosmetic UI changes.
- Prefer faster test cycles when uncertainty is high.
- Scale only repeatable wins; archive one-off wins as context, not playbook.
