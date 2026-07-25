# LibreLibrary

A shared ledger to save books, data, and facts forever.

## Problem

People in power erase and change history. The Taliban burns records. In the Philippines, the Marcos family alters facts about their past rule to look good. Groups hide the acts of black soldiers at Pearl Harbor. Christial colonizers rewrite Nordic religion and tradition.

Paper rots when floods or fires hit. Schools and libraries lose their past. Bosses read fake work records. Historians read changed text. We must stop bad actors from hiding the truth. History must not be lst or rewritten.

## How It Works

A library, school, or person opens the app.
They add a text, image, or data file.
The app makes a unique math code (a hash) from the file.
The app saves this code and the file name on the chain.
Later, an employer or historian reads the file.
They drop the file into our app.
The app checks the code on the chain.
If the codes match, the file is real. If someone changed one word or the work comes from a suspicious source, the app flags the file as untrustworthy.

## How It Uses Stellar

We use Soroban smart contracts to store file codes. We do not store large files on the chain; we store the proof.

A school can save thousands of proofs. The network shares the ledger across the world. A local flood cannot wash it away. A bad leader cannot force the network to delete the truth. This solid record deters frodulance in its tracks.

## Track

Social Impact

## Tech Stack

* Framework: Next.js
* Stellar SDK: @stellar/stellar-sdk v12.1.0
* Network: testnet
* Tools: soroban-cli

## Setup & Run

Run these steps to start the app.

```bash
git clone https://github.com/MuragLeo/librelibrary
cd librelibrary
npm install

# environment variables needed:
#   NEXT_PUBLIC_SOROBAN_RPC=...
#   ...
npm run dev

```
## Network Details
- Network: [testnet / mainnet]
- RPC URL: [endpoint]
- Contract IDs: [if any]
- Asset issuers: [if any]

## Team

* Leo Goyena — @MuragGoya

## License

[MIT / Apache-2.0 / ...]
