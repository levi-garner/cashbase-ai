# CashBase.ai

**Your financial base of operations.**

---

## The Problem

Every personal finance app gets it wrong. They obsess over categorizing every $4.50 coffee transaction, building pie charts, and syncing 400 transactions a month.

Nobody's problem is "I don't know I spent $12 at Chipotle."

The problem is: **Do I have enough money, and is it in the right place?**

---

## The Solution

One screen. Glance and go.

```
┌─────────────────────────────┐
│  Cash Available    $8,200   │
├─────────────────────────────┤
│  Coming In                  │
│  Paycheck Feb 28   +$4,500  │
├─────────────────────────────┤
│  Going Out                  │
│  Chase Sapphire    -$2,400  │  Feb 25
│  Rent              -$1,800  │  Mar 1
│  Car Insurance       -$180  │  Mar 5
├─────────────────────────────┤
│  After All Bills    $8,320  │
│  ✅ You're good.            │
│                             │
│  💡 Move $2,400 to Chase   │
│     checking before Feb 23  │
└─────────────────────────────┘
```

That's it. That's the whole app.

---

## How It Works

1. **Connect your bank accounts** (Plaid — balances only, no transaction sync)
2. **Add your bills** — credit cards, rent, insurance, whatever. You know your bills.
3. **Add your income** — paycheck dates and amounts
4. **AI tells you what to do** — "Move $X from A → B before Friday"

No transaction categorization. No spending analysis. No subscription detection. You enter your bills (2 minutes), connect your banks, and you're done.

---

## What CashBase Is NOT

- ❌ Transaction categorization
- ❌ Budgeting spreadsheets
- ❌ Spending pie charts
- ❌ "You spent more on dining" alerts
- ❌ Subscription tracker
- ❌ Rocket Money / Mint / YNAB

We don't care what you spent money on. We care that your money is in the right place at the right time.

---

## Mission

Kill the complexity in personal finance. People don't need another app that tracks every dollar — they need one screen that tells them they're good or tells them what to move.

## Vision

A world where nobody pays a late fee, overdraft fee, or interest charge because their money was in the wrong account at the wrong time.

---

## Tech Stack

- **Mobile App:** React Native (iOS + Android from one codebase)
- **Backend:** Node.js / Express (lightweight API)
- **Database:** PostgreSQL (accounts, bills, income)
- **Bank Sync:** Plaid Balance API only (cheapest tier — just balances, no transactions)
- **AI:** OpenAI / Claude for cash flow recommendations
- **Auth:** Clerk or Supabase Auth
- **Hosting:** Vercel (API) + Supabase (DB) or AWS

## Build Estimate

| Phase | What | Time |
|-------|------|------|
| **Week 1** | Core app shell, auth, bill/income entry, dashboard UI | 5 days |
| **Week 2** | Plaid integration (balance only), account linking | 3-4 days |
| **Week 3** | AI recommendation engine, notifications, polish | 4-5 days |
| **Week 4** | TestFlight / beta, refinements | 3-4 days |

**MVP in ~3-4 weeks** if focused. This is a simple app — the magic is in the simplicity, not the complexity.

---

## Status

🚧 **Concept phase** — building for personal use first, then opening up.

---

## License

MIT
