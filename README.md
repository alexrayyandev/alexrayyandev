# Alex Rayyan

Independent Smart Contract & Systems Security Researcher specializing in Solana (Rust / Anchor) program verification, invariant-based security audits, and Token-2022 protocol integrations.

---

## Research Focus

- **Solana Runtime & Anchor Security**: Cross-Program Invocation (CPI) verification, Program Derived Address (PDA) seed and bump validation, account discriminators, and re-initialization defenses.
- **Token-2022 Extensions**: Security guarantees and exploit surfaces across Transfer Hooks, Permanent Delegates, Transfer Fees, CPI Guards, and Default Account State configurations.
- **Formal Invariants & Defensive Engineering**: Formal property modeling, deterministic state transitions, and production-grade remediation patch authoring.

---

## Primary Public Repositories

- [solana-security-advisories](https://github.com/alexrayyandev/solana-security-advisories): In-depth security advisories, vulnerability root cause breakdowns, and drop-in remediation patches for 12 critical Anchor program patterns.
- [superteam-earn-research](https://github.com/alexrayyandev/superteam-earn-research): Systems architecture proposals, high-throughput routing algorithms (MultiHopper), and validator consensus economics.

---

## Public Security Advisories (Selected)

| Advisory ID | Target Subsystem / Pattern | Vulnerability Vector | Severity | Status |
|---|---|---|---|---|
| AR-SOL-2601 | Token-2022 Transfer Hook | Whitelist Validation & Authority Spoofing | CRITICAL | Disclosed & Patched |
| AR-SOL-2602 | Account State / Vault | Unchecked Reinitialization & Lamport Draining | CRITICAL | Disclosed & Patched |
| AR-SOL-2603 | CPI Guard Extension | Delegated Transfer CPI Guard Bypass | HIGH | Disclosed & Patched |
| AR-SOL-2604 | Cross-Program Lever | Missing Instruction Verification & Authority Confusion | HIGH | Disclosed & Patched |
| AR-SOL-2605 | Token Escrow | Arbitrary Token Balance Invariant Violation | CRITICAL | Disclosed & Patched |
| AR-SOL-2606 | Crowdfunding Vault | Pre-Deadline Premature Withdrawal Invariant Breach | HIGH | Disclosed & Patched |
| AR-SOL-2607 | Merkle Airdrop | Leaf Replay & Double-Claim Invariant Breach | HIGH | Disclosed & Patched |
| AR-SOL-2608 | Token Mint Authority | PDA Bump Mismatch & Arbitrary Minting | CRITICAL | Disclosed & Patched |
| AR-SOL-2609 | Permanent Delegate | Unauthorized Token Seizure via Extension Misuse | HIGH | Disclosed & Patched |
| AR-SOL-2610 | AMM / Token Swap | Constant-Product K Invariant Slip & Truncation | CRITICAL | Disclosed & Patched |
| AR-SOL-2611 | Transfer Fee Extension | Fee Calculation Rounding & Withholding Account Drain | CRITICAL | Disclosed & Patched |
| AR-SOL-2612 | Transfer Hook Switch | Mutable Program ID Hijacking in Extension Config | CRITICAL | Disclosed & Patched |

*Full advisories, test cases, and patches are documented in the [solana-security-advisories](https://github.com/alexrayyandev/solana-security-advisories) repository.*

---

## Technical Stack & Tooling

- **Languages**: Rust (edition 2021), C/C++ (eBPF), TypeScript, Python
- **Ecosystem Tooling**: Solana CLI, Anchor Framework, Trident Fuzzer, Solana Program Test, Foundry (Forge / Cast)
- **Methodology**: Invariant modeling, deterministic execution tracing, differential testing, manual bytecode analysis
- **Environment**: Linux x86_64

---

## Verified Grant & Bug Bounty Payout Wallets

Public verification addresses for protocol bug bounties, research grants, and disclosures:

- **Solana (USDC / SOL)**: `39YTqgacjKt1iz22SrvX4G3Ds8TUUjd9hWPPSJpdd2jZ`
- **Base / EVM (USDC / ETH)**: `0xf71e0734cb53162e8c9baaf5f49841a51c945899`

---

## Responsible Disclosure & Contact

- **Encrypted Contact**: `bansoslab2026@tutamail.com`
- **GitHub**: [github.com/alexrayyandev](https://github.com/alexrayyandev)
