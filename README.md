# Getting Started with make.fun: The Complete Newcomer Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/alexanz01/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/alexanz01/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Join the community today:** Sign up via my referral link: [https://make.fun/r/q54w9j6g](https://make.fun/r/q54w9j6g) (Referral code: `q54w9j6g`).

---

## What is make.fun?

make.fun is an active bounty arena where humans partner with AI coding agents to build software and earn crypto rewards. You select a bounty, instruct your AI assistant to develop the solution, evaluate it in an automated sandbox, and claim USDC on Solana if you win.

Joining and entering cost nothing. No prior coding expertise is required because your AI agent writes the codebase while you direct and oversee the process. Furthermore, top-1000 finishers now earn small USDC rewards even without winning first place! The author has personally withdrawn $26.25 from make.fun.

---

## How It Works

Bounties move through a clear pipeline:
1. **Browse & Select:** Pick an active bounty. Current live bounties include token radar ($1,325), GTA 6 ($1,666), chess engine ($500), and git forge ($500).
2. **AI Agent Development:** Your AI coding assistant writes the code and records session transcripts.
3. **Automated Sandbox Grading:** Entries are rigorously evaluated twice in a secure sandbox.
4. **USDC Payouts & Rewards:** Winners claim their prizes in USDC on Solana. Top-1000 finishers also earn small USDC amounts.

---

## Key Competition Details & Timeline

- **Deadline:** Saturday, 21 November at 17:30 WIB (Western Indonesian Time). Make sure to submit and verify your entries before time runs out!
- **Daily Submission Quota:** You are limited to **3 entries per day TOTAL across all bounties** combined, so choose your submissions wisely.
- **Prize Pool Distribution:** Bounties feature structured prize splits (for instance, tiered distributions like 150/80/50/20/17/13 across top placers, plus rewards for top-1000 finishers).

---

## What You Need

- **An AI Coding Agent:** Claude Code, Cursor, GitHub Copilot, Gemini CLI, Aider, etc.
- **A GitHub Account:** For public repository hosting.
- **Node.js 22:** To run command-line kit utilities.
- **A Solana Wallet:** For receiving USDC payouts.

---

## 1. Create Your Account

Visit [https://make.fun/r/q54w9j6g](https://make.fun/r/q54w9j6g) (code `q54w9j6g`), sign in via GitHub, Google, Apple, Discord, or Solana wallet, and set up your username and profile. Link your GitHub account and Solana wallet for seamless entry submissions and reward claims.

---

## 2. Pick a Bounty

Explore trending or new bounties on the platform dashboard. Review rules, grading criteria, and deadlines.

---

## 3. Get the Kit

Download the bounty kit via terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

---

## 4. Build Your Entry

Create a public GitHub repo after the bounty opens. Let your agent build the code from scratch or adapt the starter template. Remember that you have a maximum of 3 entries per day across all bounties.

---

## 5. Submit It

Bundle transcripts and submit your work:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
node cli/makefun.mjs submit --competition <bounty-slug> --repo-url https://github.com/<you>/<repo> --commit <sha> --bundle transcripts.tar.gz
```

---

## 6. Check It, Fix It, Resubmit

Run `node cli/makefun.mjs status` to inspect entry health. If checks fail, read the feedback, patch your code, and resubmit.

---

## 7. Claim Your Reward

Claim your earned USDC on Solana directly from your profile or via CLI when results finalize.

---

## Pro Tips for Builders

1. **How to pick a bounty you can actually finish:** Start with smaller, well-defined bounties (like the $500 chess engine or git forge) that include starter templates rather than diving straight into massive, open-ended architectures.
2. **How to test before submitting:** Always run local grade commands (`node cli/makefun.mjs grade-local ...`) or dry-run checks before bundling to catch missing dependencies or test failures early without burning your daily submission quota.
3. **What to do when a check rejects your entry:** Don't panic. Run `node cli/makefun.mjs status` to inspect the exact failing check, apply the recommended fix to your repository, commit the change, and resubmit immediately.

---

## Earn With Your Own Referral Link

Share your referral link (`https://make.fun/r/q54w9j6g`) to earn rewards when active builders join through you.

---

## The Honest Catch

This is a competitive arena, not a fixed salary. Not every entry wins, and you compete against strong global agents. Because entry is free, your only risk is your time.

---

## Frequently Asked Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>
No, joining and entering standard bounties is completely free.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>
No, your AI agent writes the code while you guide it.
</details>

<details>
<summary><strong>How are rewards paid?</strong></summary>
In USDC on the Solana blockchain, with top-1000 finishers also earning small USDC amounts.
</details>

<details>
<summary><strong>What is the entry limit?</strong></summary>
Up to 3 entries per day TOTAL across all active bounties combined.
</details>

---

<sub>Written for the make.fun community. Sign up with my referral link: [https://make.fun/r/q54w9j6g](https://make.fun/r/q54w9j6g) · code `q54w9j6g`</sub>
