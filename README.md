# Mini-Blockchain – Assignment 1

## Assignment
- PoW mining (difficulty ≥ 3, hashes start with `000…`)
- Transactions as objects (≥ 5 total)
- Validate true → tamper → false
- README + screenshots

## What I did
- Built Block/Blockchain in Node.js (SHA-256).
- Implemented `mineBlock(difficulty)` (prints nonce/time, `000…`).
- Stored ≥5 transactions as objects inside blocks.
- Validated chain, then manually tampered Block #1.

## What I got
- Mined blocks with `000…` hashes and nonce counts.
- `Is chain valid? true` → after tamper: `false`.

## Run
```bash
node blockchain.js        # default difficulty = 3
