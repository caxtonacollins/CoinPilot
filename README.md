# CoinPilot

**AI-Powered Financial Autopilot on Stellar**

![Logo]([https://ipfs.io/ipfs/bafkreie66ht6qors2fwlwihbbobx6umvdppyyxg4rb4fseto5u4fjvknqu](https://purple-accessible-swift-921.mypinata.cloud/ipfs/bafybeicmklya2ltxtvjgopqi6syteuj4b52yhd3zlybzxpdfuaudhf6shm))

CoinPilot is a smart stablecoin wallet built on Stellar that enables users to automate payments, savings, and currency conversions using programmable rules and AI.

---

## Features

### MVP

* 🔐 Stellar wallet (create/import)
* 💸 Send & receive XLM and USDC
* 🔁 Built-in token swaps (Stellar DEX)
* ⚙️ Smart automation rules
* 🤖 AI-powered rule creation (basic)
* 📊 Simple financial dashboard

---

## Vision

CoinPilot aims to become a fully autonomous financial assistant by enabling:

* AI-driven financial decisions
* Multi-currency support (NGN, USD, GBP)
* Business payments & APIs
* On-chain reputation & credit scoring
* Seamless fiat ↔ crypto integration

---

## Tech Stack

* **Frontend:** Next.js (TypeScript)
* **Backend:** Rust (Actix / Axum)
* **Blockchain:** Stellar + Soroban
* **Database:** PostgreSQL
* **Cache/Queue:** Redis

---

## Project Structure

```
coinpilot/
│
├── apps/
│   ├── web/                # Next.js frontend
│   └── api/                # Rust backend
│
├── packages/
│   ├── sdk/                # Stellar interaction SDK
│   ├── rules-engine/       # Automation logic
│   └── ai-module/          # Prompt → rules parser
│
├── contracts/
│   └── soroban/            # Smart contracts
│
├── infra/
│   ├── docker/
│   └── scripts/
│
└── docs/
```

---

## ⚙️ Getting Started

### Prerequisites

* Node.js (v18+)
* Rust
* Docker
* Stellar CLI

---

### Installation

```bash
git clone https://github.com/yourusername/coinpilot.git
cd coinpilot

# frontend
cd apps/web && npm install

# backend
cd ../api && cargo build
```

---

### Run Locally

```bash
# start backend
cargo run

# start frontend
npm run dev
```

---

## 🧪 MVP Roadmap

* [ ] Wallet integration
* [ ] Token transfers
* [ ] Swap functionality
* [ ] Rules engine (cron + triggers)
* [ ] AI → rule parser
* [ ] Dashboard UI

---

## 🤝 Contributing

Contributions are welcome. Please open issues and submit PRs.

---

## 📄 License

MIT License
