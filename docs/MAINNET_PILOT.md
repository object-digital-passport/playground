# Controlled Mainnet pilot

Status: policy draft; no spending authorization. Mainnet is for economic and UX validation only after local and Amoy tests, security review and a named approval. Never call production contracts for experimental writes.

## Preflight

- Record owner, scope, start/end, exact experimental deployment, reviewed commit/ABI, chain ID 137, code hashes, allowed operations and dedicated wallets.
- Approve a hard total budget and per-transaction/day/participant ceilings in POL, including deployment and failed transactions; record fiat estimate separately. Keep sponsor wallet limited; no production treasury approvals.
- Verify test coverage, relayer/paymaster availability, wallet/network compatibility, privacy notice and consent. Use synthetic or expressly approved non-sensitive data. Never require participants to purchase crypto without a separate opt-in.
- Confirm experimental labeling and production rejection. Define incident contact and a stop condition. Do not run automatically from CI or GitHub Pages.

## Run and evaluate

Compare self-pay (opt-in), local sponsorship and open sponsorship only if implemented. Measure onboarding completion, confirmation time, successful and failed gas, support requests, total budget consumed and remaining balances. Stop funding on anomalies, exhausted budget or unexpected destinations; existing immutable records remain. Export aggregate results and report limitations to Research.
