# Security Policy

NIAHCIA is under active early development and has not reached production readiness.

## Supported versions

No production release is currently supported.

## Reporting vulnerabilities

Please do **not** publish exploitable security issues in public GitHub issues.

Until a dedicated security contact/process is published, use GitHub's private vulnerability reporting feature where available for the affected repository.

Security reports should include:

- affected repository/component
- affected version/commit
- reproduction steps
- expected impact
- exploit prerequisites
- suggested mitigation if known

## High-priority security areas

Especially important classes include:

- PoW/consensus validation bugs
- chain reorganization/fork-choice flaws
- EVM execution inconsistencies
- signature or canonical-hash ambiguity
- worker identity/Sybil bypasses
- verification bypasses
- escrow/payment theft
- service-node integrity failures
- capability or wallet-spending escalation
- remote code execution
- secret/private-key exposure

## Responsible disclosure

Please allow maintainers reasonable time to investigate and release fixes before public disclosure.

## Prototype warning

Prototype/testnet software may intentionally omit production defenses such as mature slashing, privacy, hardened sandboxing, or economic attack resistance. Such omissions should still be documented clearly.
