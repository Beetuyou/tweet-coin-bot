# Tweet Coin Bot

Web-hosted tool (Flask) that takes a tweet URL or text and finds linked crypto coins + contract addresses (CA) across DexScreener and socials.

**Zero-config deployable to Vercel.**

## What it does

- Extracts Solana CAs, EVM CAs, and `$TICKER`s from the tweet text.
- Looks up those CAs/tickers on DexScreener for live data (price, liquidity, MC, socials).
- Searches by the Twitter/X handle from the tweet URL to find tokens that list that account in their socials.
- Shows source of match (direct CA, ticker, twitter handle match, etc.).
- Optional placeholder for xAI Grok API analysis (pass key in the form; never stored).

## Deploy to Vercel

Import this repo on Vercel. Framework will auto-detect as Flask.

## Usage

Paste a tweet URL or text and click Find Linked Coins.

Always DYOR.
