# Building a Trading Bot in Public

A weekly series where I build an algorithmic trading bot from scratch — on
**Alpaca paper trading** — and show all of it: the code, the backtests, the
bugs, and the live (paper) results.

I've been writing software for 30 years. This is a software-engineering project
that happens to trade, built in the open. Each episode ships a real piece of the
bot, and that week's code lands here.

> **Educational only. Nothing here is financial advice.** All trading shown is
> paper (simulated) trading on Alpaca's free API.

## Roadmap

1. Why build in public
2. Connect to a live market
3. A strategy is just an if-statement
4. It lost money. Good.
5. Why your backtest is lying
6. Position sizing
7. Going live (paper money)
8. It did something dumb at 3am
9. Reading the bot's mind (dashboards)
10. One month, full transparency
11. What I'd do differently
12. Season 1 finale

Code drops here as each episode airs.

## Setup

Requires a free [Alpaca](https://alpaca.markets/) paper-trading account.

```bash
python -m venv .venv && source .venv/bin/activate
cp .env.example .env   # add your Alpaca PAPER keys
```

Never commit real keys — `.env` is gitignored.
