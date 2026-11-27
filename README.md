# Awatere

Two projects in progress, both circling one question: **what is a machine allowed to do with money?**

I'm interested in the unglamorous middle of tech — the parts that decide whether a number can be checked rather
than whether it sounds good. Payments infrastructure, distributed systems, and lately the protocols that let
software act on its own without being trusted blindly.

## In progress

### [PayStage](https://paystage.xyz) — the check that runs before an agent pays

An independent, read-only preflight for x402 payments. Before an AI agent signs anything, it asks a local policy
engine and gets back `pay`, `review` or `do_not_pay` — with the rule that fired. Caps, velocity windows, allow-lists,
and a receipt for every decision, so an agent cannot quietly spend past a limit it was never given.

Open source, no custody, no keys held. Built on Base.

### [VouchGuard](https://vouchguard.app) — the same limits, in a form a person can hold

A spending mandate on an Apple Wallet pass: per-purchase cap, a per-24h ceiling, an expiry, and a revoke. The person
paying can see what a teammate is allowed to spend without opening a dashboard, and a counterparty can scan it and
read the same state.

A record of authority — deliberately not a payment card, not a wallet, and it holds no money. Open source and
rebrandable under MIT, because a small business should be able to adopt the pattern without adopting a vendor.

## How I work

Plainly, in small pieces, with the measurement next to the claim. "Unverified" is a complete sentence. If something
is not working yet, the page about it says so.

---

*Both projects are work in progress. Reach me through either site, or open an issue here.*
