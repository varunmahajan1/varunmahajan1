<a href="https://github.com/varunmahajan1?achievement=pull-shark&tab=achievements"><img src="https://github.githubassets.com/assets/pull-shark-default-498c279a747d.png" alt="GitHub achievement: Pull Shark" width="64" height="64" align="right"></a>

# [Varun Mahajan](https://varunmahajan.in)

I design the machine and build it.

Founder. I build production AI systems, then extract the primitives that actually broke.

**Now:** [Rewalto](https://rewalto.com) — brand execution intelligence. Independent measurement of what customers actually encounter across search, AI answers, marketplaces, and support.

**Shipped**

- [Niyra](https://niyra.ai) — personal AI across WhatsApp, Telegram, Discord, web, and inbound voice. Built under [Avuvo](https://avuvo.com).
- HOM-i — AI home-loan assistant, text/voice/video, 30+ Indian languages.
- QwikSkills — $1.5M ARR, 75K+ learners, $500K raised (2020–2024).

[Niyra's memory, measured in public](https://varunmahajan.in/writing/niyra-memory-measured-in-public) — LongMemEval 98.2% recall@10.

Gurugram · London · [vm@varunmahajan.in](mailto:vm@varunmahajan.in) · [LinkedIn](https://www.linkedin.com/in/varunm1)

---

## Primitives from production

Incident-derived libraries. Each one exists because something failed in production.

| Package | Why it exists |
|---|---|
| [llm-meter](https://github.com/varunmahajan1/llm-meter) | Token cost tracking with cache-token accounting. Metered bill was an order of magnitude below the invoice. |
| [llm-failover](https://github.com/varunmahajan1/llm-failover) | Provider-portable failover with circuit breakers, including the cross-provider `tool_call_id` break. |
| [agent-runtime](https://github.com/varunmahajan1/agent-runtime) | Stalled-agent watchdog, per-agent tool RBAC, human approval gates. |
| [promptshield](https://github.com/varunmahajan1/promptshield) | Prompt-injection defense. Zero deps, pattern-based. |
| [ssrfguard](https://github.com/varunmahajan1/ssrfguard) | SSRF-safe fetching that defeats DNS rebinding. |
| [agent-stream](https://github.com/varunmahajan1/agent-stream) | Typed SSE for multi-agent orchestration. Streams never end silent. |
| [timeanchor](https://github.com/varunmahajan1/timeanchor) | Deterministic time grounding. Agents should not think today is Tuesday. |
| [channelfmt](https://github.com/varunmahajan1/channelfmt) | Markdown to WhatsApp/Telegram-native formatting. |

---

## Upstream

[anthropic-sdk-go](https://github.com/anthropics/anthropic-sdk-go)

- [#430](https://github.com/anthropics/anthropic-sdk-go/pull/430) — Bedrock SSO bearer sent as API key ([#414](https://github.com/anthropics/anthropic-sdk-go/issues/414))
- [#431](https://github.com/anthropics/anthropic-sdk-go/pull/431) — bash Close wait hang / `setsid` ([#390](https://github.com/anthropics/anthropic-sdk-go/issues/390))
- [#432](https://github.com/anthropics/anthropic-sdk-go/pull/432) — Unescaped path params in generated client URLs ([#422](https://github.com/anthropics/anthropic-sdk-go/issues/422))
