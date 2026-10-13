## Hi, I'm Tom 👋

I build **local-first AI tools**, mostly around voice AI, evaluating AI agents, and keeping agents safe when they use real tools.

The thread running through these projects: **prompt → context engineering → evaluation harness → governance.** Build the agent, measure it honestly, then constrain what it can do.

### Projects

| Project | What it does | Highlights |
|---|---|---|
| [**voice-agent-evals**](https://github.com/tomjose-bv/voice-agent-evals) | A local customer-service voice agent plus an evaluation harness: 25 scenarios, simulated callers, and metrics for task completion, escalation and hallucination | Compares prompt-only, context-engineered and governed-graph agents on the same scenarios: pass rate 16% → 28% → 44%, escalation recall 25% → 100% (local 3B model, held-out validated) |
| [**agent-guard**](https://github.com/tomjose-bv/agent-guard) | A governance proxy between AI agents and their tools (MCP): YAML policies, PII redaction, human approval, tamper-evident audit log | About 2–4 ms measured overhead per tool call |
| [**live-captions**](https://github.com/tomjose-bv/live-captions) | Offline real-time captions for anything playing on a Windows PC, with a speech-to-text benchmark | Moonshine base: 3.8% WER at 18× real time on a laptop CPU |
| [**claude-usage-widget**](https://github.com/tomjose-bv/claude-usage-widget) | A tiny always-on-top Windows widget showing remaining Claude plan usage, with history and burn-rate estimates | Zero dependencies, one-command install |

### How I build

- **Measure, don't guess.** Every number in these READMEs comes from a real run, with the machine and date, or is marked TBD.
- **Local and private by default.** No cloud APIs needed, and nothing leaves your machine unless you choose.
- **Responsible AI is a feature.** Consent notices, AI disclosure, escalation to humans, PII redaction and audit trails are built in.

**Interests:** voice AI · agent evaluation · context engineering · AI governance & safety · MCP
