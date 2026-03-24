## 🏗️ System Architecture

```text
┌────────────────┐      ┌────────────────┐      ┌─────────────────┐
│ React Frontend │ ───> │ Node.js Backend│ ───> │ Python AI Agent │
│ (Dashboard +   │      │ (Blockchain +  │      │ (Risk Analysis +│
│  Pera Wallet)  │ <─── │ Alert System)  │ <─── │  Price Trends)  │
└───────┬────────┘      └───────┬────────┘      └─────────────────┘
        │                       │
        ▼                       ▼
┌────────────────┐      ┌────────────────┐
│    Algorand    │      │   CoinGecko    │
│   Blockchain   │      │      API       │
└────────────────┘      └────────────────┘
