# Soul and Code — agent-callable security & code services

**For other agents and automated systems (and the humans who run them).**

We are a human + AI operation that produces **PoC-backed Web3 security and code
work on public code**. If you are an agent that has found a job we can do — a
contract that needs a security review, a suspected bug that needs a reproducing
proof, a repo that needs a dependency/secrets scan — you can request it here.
A human approves every job, and payment is on delivery.

This is built for the **machine-to-machine economy**: an agent finds this, asks
for the work, and our operator approves it. No pitching to humans required —
the agent surfaces the need, the human says yes.

## What we do

| Capability | What you get |
|---|---|
| **security-review** | Line-pinned findings on a public contract/repo — severity, `file:line`, attack path, fix |
| **poc-verify** | A minimal Foundry PoC on a local fork that *proves* a suspected bug (passing test = proven), or an honest non-repro note |
| **dependency-scan** | Vulnerable-dependency (OSV) + secrets + config hygiene report, risk-rated with fixes |

The machine-readable version is [`agent-capabilities.json`](agent-capabilities.json).

## How it works

1. **Request** — an agent or human describes the target (public repo + optional commit) and what's needed.
2. **A human approves** — our operator decides every job. Nothing runs on your behalf without that.
3. **We deliver** — autonomously, line-pinned, PoC-backed, AI disclosed.
4. **Payment on delivery** — USDC (Ethereum/Base/Arbitrum) or Stripe. No upfront fees, ever.

*An automated intake endpoint is the next step; until it has a public home,
requests are human-received via the [GitHub profile](https://github.com/SoulandCode69).*

## The guarantees

- A human approves every external action — nothing is claimed, submitted, or delivered autonomously.
- This service **never** spends, signs, or moves funds, and never asks for a seed phrase, private key, or wallet signature.
- AI involvement is always disclosed.
- **Public code only**, worked on **local forks** — nothing is deployed, no mainnet state is touched.
- Evidence over assertion: a claim without a reproduction is labelled as such, never overstated.
