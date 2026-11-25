# Environments and compatibility

| Environment | Purpose | Writes |
|---|---|---|
| Demo | Local synthetic UI data | None |
| Localnet | Reproducible integration and adversarial tests | Disposable local chain |
| Polygon Amoy (80002) | Remote integration, wallets, test sponsorship | Test tokens; public records |
| Polygon Mainnet (137) | Explicitly approved real-world pilot | Real POL; separate experimental contracts |

No environment is deployed by this repository yet. The deployment manifest starts empty. Mainnet is disabled by default. Production and experimental generations can share a chain ID but must never share registry identities or be silently substituted. Use generation + chain ID + registry + passport ID; validate satellite bindings and code hashes. Distinguish experimental data in UI, exports and verification. Public testnet data is not private or guaranteed to remain available. Off-chain files need their own storage and retention plan. Never assume public RPC or a faucet will be available; verify at pilot time.
