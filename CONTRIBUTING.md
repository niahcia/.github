# Contributing to NIAHCIA

Thank you for helping build NIAHCIA.

## Before opening a change

For implementation work:

1. Check the relevant repository roadmap and open issues.
2. Confirm whether the change affects protocol behavior.
3. If it changes protocol semantics, object formats, wire behavior, consensus, verification, or economics, update or propose the relevant specification/NIP first.
4. Keep implementation changes narrowly scoped where practical.

## Repository responsibilities

- `niahcia` — blockchain/node implementation
- `niahcia-protocol` — protocol specs and NIPs
- `niahcia-miner` — CPU mining
- `niahcia-compute` — AI compute workers
- `niahcia-explorer` — chain/AI explorer
- `niahcia-web` — official web application
- `niahcia.github.io` — static project site

## Pull requests

A good pull request should include:

- what changed
- why it changed
- how it was tested
- protocol/security impact
- compatibility impact
- screenshots or logs when UI/runtime behavior changes

## Protocol changes

Protocol-affecting changes should not be hidden inside implementation pull requests.

Use the NIAHCIA Improvement Proposal process in `niahcia-protocol/nips/` when a proposal materially changes:

- consensus
- canonical object formats
- serialization/hashing
- P2P messages
- agent semantics
- verification
- economics
- capability/security policy

## Security

Do not open public issues for sensitive security vulnerabilities. See `SECURITY.md`.

## Engineering principles

- avoid mandatory central dependencies
- separate consensus from AI execution
- keep CPU mining and AI compute distinct
- make state and commitments reproducible
- prefer measurable evidence over trusted claims
- keep protocol behavior versioned
- design for independent implementations
