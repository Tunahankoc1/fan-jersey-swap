# Fan Jersey Swap

Trade and swap World Cup 2026 fan jerseys on Solana — prices driven by live match odds and results.

🌐 **Live Demo:** [fan-jersey-swap.vercel.app](https://fan-jersey-swap.vercel.app)

---

## What It Does

### 1. Fetches Live Data
- **TxLINE API** — live pre-match odds (used as jersey base price)
- **WorldCup26 API** — live match results and scores

### 2. Dynamic Jersey Pricing
Prices update automatically based on match outcomes:

| Event | Price Effect |
|-------|-------------|
| Favorite lost | 📉 Price drops |
| Underdog won | 📈 Price rises + UPSET bonus |
| Live odds available | ⚡ Real-time price update |

### 3. Displays
- Real jersey images for all **48 teams**
- **HOT / WIN / OUT** badges
- Rarity tiers: **LEGENDARY / EPIC / RARE / COMMON**
- Live odds bar per jersey

### 4. Solana Transactions
All transactions are real Solana Devnet transactions:

| Action | Description |
|--------|-------------|
| **Mint Jersey** | Mints the jersey on Solana |
| **List for Swap** | Lists jersey on the swap market |
| **Swap Now** | Executes a jersey swap transaction |

### 5. Live Matches Tab
- All World Cup 2026 matches from WorldCup26 API
- Score, date, group info
- Filter: **All / Upcoming / Finished**

---

## Tech Stack

- **Frontend:** HTML + JavaScript (single file, no build step)
- **Blockchain:** Solana Devnet (Phantom wallet)
- **APIs:** TxLINE (odds), WorldCup26 (results)
- **Assets:** 48 real team jersey images (.webp)
- **Deployment:** Vercel

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/Tunahankoc1/fan-jersey-swap
cd fan-jersey-swap

# Open in browser
open index.html
# or visit the live demo
```

**Requirements:**
- Phantom wallet browser extension (Devnet mode)
- Small amount of SOL for transaction fees

---

## Built For

[Superteam World Cup Hackathon](https://superteam.fun/earn/hackathon/world-cup) — Fan Experiences Track
