# Mini-Blockchain – Assignment 1

## Assignment
- PoW mining (difficulty ≥ 3, hashes start with `000…`)
- Transactions as objects (≥ 5 total across blocks)
- Validate `true` → tamper Block #1 → `false`
- README with run steps + screenshots

## What I did
- Implemented Block/Blockchain in Node.js (SHA-256).
- `mineBlock(difficulty)` prints leading-zero hash + `nonce` attempts.
- Stored ≥5 transactions as objects inside `transactions[]`.
- Printed chain JSON; verified `isChainValid()`; manually tampered Block #1.

## What I got (results)
- Mined blocks show `000…` hashes and `nonce=...`.
- `Is chain valid? true` → after tamper: `false`.

##screenshots
The output screenshots were stored in the assets blockchain_assignment_1 file

## Run
```bash
node blockchain.js          # default difficulty = 3

