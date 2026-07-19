# Evan Follis, CFA

**I build governed AI systems where claims, evidence, runtime state, and release decisions stay inspectable after the demo.**

My work sits at the intersection of applied machine learning, investment research, agent architecture, and production engineering. The common thread is systems that can be questioned: explicit provenance, reproducible checks, honest status labels, and durable artifacts instead of ephemeral agent state.

Based in Nashville, Tennessee.

[LinkedIn](https://www.linkedin.com/in/evan-follis/) | [Synaplex](https://synaplex.ai)

## Proof in 90 seconds

| Start here | What to inspect |
|---|---|
| [synaplex.ai](https://synaplex.ai) + [repo](https://github.com/evanfollis/synaplex) | Public face of the Synaplex research platform and methodology-as-product. |
| [Skillfoundry Preflight live product](https://skillfoundry.synaplex.ai/products/preflight/) + [server manifest](https://skillfoundry.synaplex.ai/products/launchpad-lint/server.json) + [repo](https://github.com/evanfollis/skillfoundry-products/tree/main/products/launchpad-lint) | A deployed MCP/REST readiness checker for marketplace launch packages. |
| [Atlas](https://github.com/evanfollis/atlas) | Causal research engine with pre-registered hypotheses, typed evidence, findings, and promote / kill / continue / pivot decisions. |
| [Command](https://github.com/evanfollis/command) | Private owner observatory for the Synaplex workspace: a system-health dashboard over the closure ledger, execution health, provider-fallback status, research/evidence flow, and full telemetry lineage. Implementation is published; production deployment is gated. |
| [Skillfoundry Harness](https://github.com/evanfollis/skillfoundry-harness) + [Context Repository](https://github.com/evanfollis/context-repository) | Reusable infrastructure for git-backed context repositories, validation, canon objects, provenance, and replayable claims. |

## Three lanes

### Synaplex research platform

[Synaplex](https://github.com/evanfollis/synaplex) is the system: a public research and evaluation surface for studying AI systems through canon-backed claims, evidence, decisions, and publications. Its public face is [synaplex.ai](https://synaplex.ai); its private owner observatory is [Command](https://github.com/evanfollis/command).

[Atlas](https://github.com/evanfollis/atlas) is the quantitative research pod. It applies the same methodology to crypto-market microstructure: formulate falsifiable claims, run experiments, record typed evidence, and promote only claims that survive the gate.

### Working systems and case studies

[Skillfoundry Preflight / Launchpad Lint](https://skillfoundry.synaplex.ai/products/preflight/) is a live product for auditing MCP launch readiness and drafting marketplace-ready packages. The canonical implementation lives in [`skillfoundry-products/products/launchpad-lint`](https://github.com/evanfollis/skillfoundry-products/tree/main/products/launchpad-lint), with public health and manifest endpoints exposed under the Skillfoundry route.

[Command](https://github.com/evanfollis/command) is the workspace's private owner observatory: a system-health dashboard over the closure ledger, execution health, provider-fallback state, research/evidence flow, and full telemetry lineage. The implementation is published in the repo; production deployment is still gated, so the repo is the inspectable artifact.

[AI Mentor](https://github.com/evanfollis/mentor) is a completed case study in an AI-powered architecture learning system: Next.js, FastAPI, PostgreSQL, Redis, Slack integration, adaptive quizzes, spaced repetition, and gated progression. I am not presenting it as currently deployed because I did not verify a live endpoint.

### Reusable infrastructure

[Skillfoundry Harness](https://github.com/evanfollis/skillfoundry-harness) is a Python runtime harness for git-backed agent context repositories. It owns validation, context lineage bootstrap, bounded branch workspaces, proposal / approval / apply flow, and durable execution artifacts.

[Context Repository](https://github.com/evanfollis/context-repository) is the pattern lab and canon substrate: the formal model for claims, evidence, decisions, policy, promotion, realization, replay, and provenance.

## Working principles

- Evidence before narrative.
- Point-in-time evaluation over retrospective fit.
- Explicit promotion and rejection criteria.
- Durable artifacts over ephemeral agent state.
- Clear boundaries between claims, evidence, policy, and decisions.
- Complexity only when it survives comparison with a simpler baseline.
- Negative results are part of the product.

## Licensing

License status is repository-specific. I do not present the portfolio as blanket open source; inspect each repository before assuming reuse rights. The public Preflight repo carries MIT licensing, while core Synaplex, Atlas, Command, Harness, and Context Repository surfaces should be treated according to their individual repository state.

## Background

CFA charterholder and AI systems architect with experience across asset management, fixed income, quantitative modeling, LLM systems, and production engineering.

Primary tools include Python, SQL, FastAPI, Docker, TypeScript, Next.js, applied ML, retrieval systems, structured LLM workflows, and agent infrastructure.

## Contact

The best place to reach me professionally is [LinkedIn](https://www.linkedin.com/in/evan-follis/).
