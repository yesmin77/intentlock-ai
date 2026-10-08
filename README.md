# INTENTLOCK AI

### AI Trading Agent • Policy Enforcement • Safer Trading

INTENTLOCK AI is an AI-powered trading safety and policy-enforcement agent for 24/7 tokenized markets.

## What It Does

INTENTLOCK separates AI trade proposals from trade authorization.

The AI can propose a trade, but INTENTLOCK independently checks whether the proposal follows the user's predefined trading policies before allowing paper execution.

## How It Works

User Intent
→ AI Trading Desk
→ Trade Proof Engine
→ Policy Checks
→ BLOCKED / VERIFIED
→ Human Confirmation
→ Paper Execution
→ Activity Log

## Core Features

- AI Trading Desk
- Intent Lock
- Risk Lock
- Capital Lock
- Liquidity Lock
- Market Condition Lock
- Earnings Blackout Lock
- Ex-Dividend Lock
- Trade Proof Engine
- Human confirmation before execution
- Paper trading execution
- Activity Log
- Simulated 24/7 market data

## Risk Model

Paper Equity: $1,000

Maximum Risk: 0.5%

Stop Loss: 3%

Risk Formula:

Risk % = Trade Amount × 3 ÷ 1000

Example:

$150 trade → Capital Check FAIL → BLOCKED

$80 trade → Risk = 0.24% → VERIFIED

After confirmation:

$80 → EXECUTED — PAPER

Paper Cash: $1,000 → $920

## Safety

INTENTLOCK does not execute real trades.

It determines whether an AI-proposed trade complies with predefined user policies.

Blocked trades cannot be confirmed or executed.

## Supported Demo Assets

- rNVDA
- rTSLA
- rAAPL
- rMSFT
- rQQQ
- rSPY

Market data in the current demo is simulated.

## Demo Flow

1. User defines trading intent
2. AI Trading Desk generates a trade proposal
3. Trade Proof Engine evaluates the proposal
4. Invalid proposal is BLOCKED
5. Valid proposal becomes VERIFIED
6. User confirms the trade
7. Trade executes in PAPER mode
8. Activity Log records the execution

## Current Status

Working prototype with AI-assisted trade proposals, deterministic policy enforcement, paper execution, and activity logging.

No real-money trading is performed.

## Live Demo

https://intent-lock-ai--yesmin006.replit.app/

## Project Goal

INTENTLOCK AI aims to make agentic trading safer by ensuring AI-generated trade proposals remain within user-defined policies before execution is allowed.
