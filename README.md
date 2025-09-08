# Assignment 1 – Extended Mini Blockchain

This project extends the mini-blockchain with:
- Proof-of-Work (difficulty ≥ 3)
- Nonce attempts printed
- Transactions stored as objects in arrays (≥ 5 total)
- Valid/invalid chain demo with tampering

## How to Run
```bash
node blockchain.js       # default difficulty = 3
node blockchain.js 4     # harder difficulty


## Output
- Shows each mined block with a hash starting with 000…
- Shows number of attempts (nonce)
- Is chain valid? true before tampering
- Is chain valid after tamper? false

## Screenshots
(Add your console screenshots here, e.g., mining.png, validation.png)

## Reflection
Hashing guarantees immutability: each block’s hash is based on its contents plus the previous block’s hash. Even a tiny data change produces a totally different hash, breaking the chain. Proof-of-Work forces miners to spend real effort finding a hash that meets the difficulty requirement (leading zeros). This makes tampering computationally expensive: an attacker would have to re-mine the edited block and all following ones. Building this assignment clarified how simple concepts—hashing, linking, nonces—combine into a secure blockchain.
