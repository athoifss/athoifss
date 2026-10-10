I build the backend pieces that are hard to get right.

**What I work on**

- **Access control.** Relationship-based (Zanzibar-style) permission systems, AWS-IAM-style
  policy languages, and the engines that evaluate them. Policies compiled into relation
  tuples, permission checks that stay fast as the rules grow, and traces that explain
  every decision.
- **Durable workflows.** Billing and metering built as Temporal workflows: quotas, usage
  aggregation, overage pricing and invoicing that retry safely instead of corrupting state.
- **Incremental computation.** Keeping derived state up to date by applying changes rather
  than recomputing it, with Rust where the hot path needs it.
- **Multi-tenant backends.** Org, project and resource scopes; modular services with clear
  contracts; migrations that don't break production.
- **Agent-driven development.** Machine-readable specs, invariants and routing contracts
  that let AI coding agents ship production code instead of guesses.

**Stack:** TypeScript, Node.js, PostgreSQL, Fastify, NestJS, Next.js, Temporal, ClickHouse,
Rust (napi-rs).

**Public work**

- [Stripe-Payment-Intent](https://github.com/athoifss/Stripe-Payment-Intent): complex
  payment flows with Stripe Payment Intents, React and Node.js.
