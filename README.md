# Solo Dev Agents

A lightweight multi-agent toolkit for AI-assisted solo software development.

Designed for Codex, Claude Code, solo founders, and independent developers building SaaS, web, mobile, and backend products.

For the design philosophy and intended operating model, see [`GOALS.md`](GOALS.md).

## Agents

- **Lead** — orchestrates substantial work and keeps scope under control.
- **Frontend Expert** — handles web/mobile UI, frontend architecture, performance, and accessibility.
- **Backend Expert** — handles APIs, databases, auth, jobs, integrations, reliability, and server-side concerns.
- **QA** — adversarial testing and regression detection.
- **Growth** — positioning, acquisition, activation, conversion, monetization, and retention.
- **Release Reviewer** — independent pre-production review.

## Philosophy

- Truth-first assistance.
- Human authority: agents advise and execute; the human remains the decision-maker.
- Use specialists only when they add value.
- Keep prompts and context small.
- Prefer existing project patterns.
- Avoid speculative architecture.
- Reduce manual QA.
- Treat growth as a first-class product function.
- Require an independent review before production releases.

## Typical routing

```text
Small fix
→ Frontend Expert or Backend Expert

Substantial feature
→ Lead
   ├── Frontend Expert
   ├── Backend Expert
   └── QA

Growth / pricing / onboarding / acquisition
→ Growth

Production release
→ Release Reviewer
```

Do not invoke every agent for every task.

## Suggested project structure

```text
your-project/
├── AGENTS.md
├── CLAUDE.md
├── PRODUCT.md
└── ...
```

## Codex

Use `AGENTS.md` as the primary project instruction source.

## Claude Code

Use `CLAUDE.md` as a thin compatibility layer pointing to the same shared rules.

## License

MIT
