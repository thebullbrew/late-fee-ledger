![The Late-Fee Ledger](assets/preview.png)

![The Late-Fee Ledger](assets/banner.jpg)

# The Late-Fee Ledger

**Live:** https://thebullbrew.github.io/late-fee-ledger/

## What it does

A landlord's rent ledger that does the late-fee math your lease already promised. Set your late-fee terms once (flat fee, per-diem after grace, monthly % on the late balance, optional state-mandated cap), then log rent charges and payments — and every late fee computes itself against your grace period, with a running balance that never forgets.

- **Automatic late fees** — flat fee the day after grace ends, per-diem accruing daily until a charge is fully settled, monthly % on the delinquent balance, per-charge caps for states that limit fees
- **FIFO payment application** — payments kill the oldest charge first, the way courts tend to apply partial rent, so per-diem stops bleeding on the longest-running debt
- **The ledger view** — every charge: period, due date, what was paid and when, days late, fee assessed, remaining balance; red rows are still accruing
- **Landlord stats** — rent collected, fees assessed, on-time payment rate, average days late, open charges
- **One-tap charge generation** — a year's monthly charges in one click, plus one-off charges (garage, pet rent, utilities)
- **Receipts & records** — copy-per-payment receipts, copyable landlord summary, CSV export for tax season or court day
- **Lease clause builder** — your terms turned into enforceable late-payment lease language you can copy into the next lease
- **Multiple units** — one saved ledger per unit/tenant, all in your browser

## The method behind it

Most landlords leave late fees uncollected because the bookkeeping is tedious: "was it 5 days past grace or 12?" The ledger removes the excuses — the fee is already in the lease, and now the math is automatic. The uncomfortable truth it teaches: **days late measures settlement, not arrival.** A partial payment doesn't stop the clock; dribs and drabs of rent get expensive because every day past grace is per-diem. That alone will change how you talk to tenants about "I'll have half Friday."

## How to run

It's a single self-contained page — no build step, no server, no accounts.

- Open `docs/index.html` directly in any browser (`file://` works), or
- Host it anywhere static — it ships as a PWA with offline support.

All data stays in your browser's localStorage. Nothing is sent anywhere.
