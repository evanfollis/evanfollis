# Evan Follis, CFA

**I build governed AI systems where claims, evidence, runtime state, and release decisions stay inspectable after the demo.**

My work sits at the intersection of applied machine learning, investment research, agent architecture, and production engineering. The common thread is systems that can be questioned: explicit provenance, reproducible checks, honest status labels, and durable artifacts instead of ephemeral agent state.

Based in Nashville, Tennessee.

[LinkedIn](https://www.linkedin.com/in/evan-follis/) | [Synaplex](https://synaplex.ai)

## Proof in 90 seconds

| Start here | What to inspect |
|---|---|
| [synaplex.ai](https://synaplex.ai) + [repo](https://github.com/evanfollis/synaplex) | Public research and evaluation system for canon-backed claims, evidence, decisions, findings, and typed predecessor lineage. |
| [Skillfoundry Preflight](https://skillfoundry.synaplex.ai/products/preflight/) + [source](https://github.com/evanfollis/skillfoundry-products/tree/main/products/preflight) | A deterministic MCP server for validating publish-readiness before registry submission. |
| [Launchpad Lint manifest](https://skillfoundry.synaplex.ai/products/launchpad-lint/server.json) + [source](https://github.com/evanfollis/skillfoundry-products/tree/main/products/launchpad-lint) | A separate MCP/REST checker for marketplace launch packages. |
| [Atlas](https://github.com/evanfollis/atlas) | Causal research engine with pre-registered hypotheses, typed evidence, findings, and promote / kill / continue / pivot decisions. |
| [Command](https://github.com/evanfollis/command) | Authenticated owner observatory for the Synaplex workspace: a system-health dashboard over the closure ledger, execution health, provider-fallback status, research/evidence flow, and bounded telemetry/artifact lineage. Implementation is public; production access is private. |
| [Skillfoundry Harness](https://github.com/evanfollis/skillfoundry-harness) + [Context Repository](https://github.com/evanfollis/context-repository) | Reusable infrastructure for git-backed context repositories, validation, canon objects, provenance, and replayable claims. |

## Portfolio map

### Research system

[Synaplex](https://github.com/evanfollis/synaplex) is the public research and evaluation system for studying AI systems through canon-backed claims, evidence, decisions, and publications. Its public face is [synaplex.ai](https://synaplex.ai), including an inspectable [historical-lineage index](https://synaplex.ai/lineage/).

[Atlas](https://github.com/evanfollis/atlas) is the quantitative research pod. It applies the same methodology to crypto-market microstructure: formulate falsifiable claims, run experiments, record typed evidence, and promote only claims that survive the gate.

### Products and observability

[Skillfoundry Preflight](https://skillfoundry.synaplex.ai/products/preflight/) is a deterministic MCP server for validating manifest identity, package/version consistency, repository metadata, and launch evidence before MCP Registry publication. Its canonical implementation lives in [`skillfoundry-products/products/preflight`](https://github.com/evanfollis/skillfoundry-products/tree/main/products/preflight).

[Launchpad Lint](https://skillfoundry.synaplex.ai/products/launchpad-lint/server.json) is a separate MCP/REST product for checking and drafting marketplace launch packages. Its canonical implementation lives in [`skillfoundry-products/products/launchpad-lint`](https://github.com/evanfollis/skillfoundry-products/tree/main/products/launchpad-lint).

[Command](https://github.com/evanfollis/command) is the workspace's authenticated owner observatory: a system-health dashboard over the closure ledger, execution health, provider-fallback state, research/evidence flow, and bounded telemetry and artifact lineage. The implementation is public; the deployed production surface requires authentication.

[AI Mentor](https://github.com/evanfollis/mentor) is an archived, completed case study in an AI-powered architecture learning system: Next.js, FastAPI, PostgreSQL, Redis, Slack integration, adaptive quizzes, spaced repetition, and gated progression. It is preserved for inspection; no live deployment is claimed.

### Reusable infrastructure

[Supervisor](https://github.com/evanfollis/supervisor) is the durable governance and operations control plane: decisions, handoff provenance, repository contracts, prompt-evaluation policy, safety-gap tracking, and runtime observation.

[Skillfoundry Agents](https://github.com/evanfollis/skillfoundry-agents) is the coordination hub for the builder, designer, growth, pricing, researcher, and valuation context repositories. Those repositories remain separate because their missions and durable state are distinct.

[Skillfoundry Harness](https://github.com/evanfollis/skillfoundry-harness) is a Python runtime harness for git-backed agent context repositories. It owns validation, context lineage bootstrap, bounded branch workspaces, proposal / approval / apply flow, and durable execution artifacts.

[Context Repository](https://github.com/evanfollis/context-repository) is the pattern lab and canon substrate: the formal model for claims, evidence, decisions, policy, promotion, realization, replay, and provenance.

## One contract, different shapes

The active repositories share the same navigation and verification front doors: `repo.toml` declares identity, lifecycle, shape, risk, and artifact roles; `Makefile` exposes `help` and `check`; an architecture document under `docs/` explains the local boundaries; and CI runs the repository's own clean-check gate. The common contract is profiled rather than copy-pasted: a control plane, hosted service, research system, context repository, and product monorepo retain different internal structures where their work requires it.

The contract and its agentic-safety transition are public in the [Supervisor architecture standard](https://github.com/evanfollis/supervisor/blob/main/docs/repository-architecture-standard.md) and [ADR-0050](https://github.com/evanfollis/supervisor/blob/main/decisions/0050-profiled-repository-contract-and-agentic-safety-baseline.md). Open containment gaps remain explicit in the [safety gap register](https://github.com/evanfollis/supervisor/blob/main/system/agentic-safety-gap-register.md).

## Historical lineage

Older public experiments are preserved as typed, explicitly archived lineage—not relabeled as current evidence. [Geometric Agent Primitives](https://synaplex.ai/lineage/geometric-agent-primitives/), [AI Native](https://synaplex.ai/lineage/ai-native/), [Worldview Alignment](https://synaplex.ai/lineage/worldview-alignment/), [EDG](https://synaplex.ai/lineage/edg/), and [Cadence](https://synaplex.ai/lineage/cadence/) influenced questions now studied under Synaplex, but their historical results do not automatically become present-day Synaplex findings. [Crypto Agent DP Lab](https://github.com/evanfollis/crypto-agent-dp-lab) is the archived predecessor lineage for Atlas.

## Working principles

- Evidence before narrative.
- Point-in-time evaluation over retrospective fit.
- Explicit promotion and rejection criteria.
- Durable artifacts over ephemeral agent state.
- Clear boundaries between claims, evidence, policy, and decisions.
- Complexity only when it survives comparison with a simpler baseline.
- Negative results are part of the product.

## Licensing

License status is repository-specific. I do not present the portfolio as blanket open source; inspect each repository before assuming reuse rights. The archived standalone Preflight release carries MIT licensing, while the canonical product and core Synaplex, Atlas, Command, Harness, and Context Repository surfaces should be treated according to their individual repository state.

## Background

CFA charterholder and AI systems architect with experience across asset management, fixed income, quantitative modeling, LLM systems, and production engineering.

Primary tools include Python, SQL, FastAPI, Docker, TypeScript, Next.js, applied ML, retrieval systems, structured LLM workflows, and agent infrastructure.

## Contact

The best place to reach me professionally is [LinkedIn](https://www.linkedin.com/in/evan-follis/).
