# Jay Clark

I build production AI systems, and I'm also the person they call when somebody else's production breaks.

The second half is what makes the first half work. Nine years of enterprise escalations taught me what people actually do to software, which is rarely what the design assumed. So I build expecting them to find the edge. They always do.

I write at [jayclark.ai](https://jayclark.ai) about agent reliability and about building software with coding agents. Nothing survives production on good intentions, and no rule survives on being remembered. The rules that matter get written into a file or enforced by a script.

## Building

- **[surfacelock](https://github.com/JsizzleR/surfacelock)** — `tools.lock`, a lockfile for MCP tool surfaces: pin, verify, and diff what your agent is told it can trust. An agent's tools are a trust boundary; treat them like dependencies.
- **[jayclark.ai](https://jayclark.ai)** — essays on building software with AI coding agents.
- **[yourhonor](https://github.com/JsizzleR/yourhonor)** — R package that calibrates an LLM-as-judge: treat it as a measurement instrument and report its psychometrics.
- **[tripwire](https://github.com/JsizzleR/tripwire)** — R package that catches silent failures in data-analysis steps (joins that quietly drop or multiply rows), with an MCP server so agents can run the checks.

## Focus

- **Production LLM systems** — RAG, tool-calling agents (MCP), evals & drift detection, model cost optimization
- **Agent security** — least privilege enforced below the model, not in the prompt: container isolation, egress control, tool-surface verification. Prompt injection can't exercise a capability that was never granted.
- **Enterprise infrastructure** — Linux, containers, networking, auth & SSO (SAML, OIDC, OAuth2), distributed deployments
- **Languages** — Python, Go, R, SQL

## Elsewhere

[jayclark.ai](https://jayclark.ai) · [LinkedIn](https://www.linkedin.com/in/jsizzler)

---

<sub>U.S. Air Force veteran.</sub>
