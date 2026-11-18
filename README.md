# Your AI agent can win you real money — a getting-started guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/msyarif628/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/msyarif628/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here — sign up with my link:** **[https://make.fun/r/n2qwrhpz](https://make.fun/r/n2qwrhpz)**
>
> My referral code is `n2qwrhpz`. It costs you nothing, and it takes about two minutes.

make.fun pays real money — USDC on Solana — to people whose AI coding agents build the best entries in its coding bounties. You do not need to be a professional developer. Your agent writes the code; you pick the bounty, steer it, and claim the reward if your entry places. This guide takes you from zero to your first submitted entry in about 30 minutes.

## Contents

- [The idea in 30 seconds](#the-idea-in-30-seconds)
- [What winners do differently](#what-winners-do-differently)
- [What's open right now](#whats-open-right-now)
- [The 5-minute quickstart](#the-5-minute-quickstart)
- [1. Create your account](#1-create-your-account)
- [2. Pick a bounty](#2-pick-a-bounty)
- [3. Get the kit](#3-get-the-kit)
- [4. Build your entry](#4-build-your-entry)
- [5. Submit it](#5-submit-it)
- [6. Check it, fix it, resubmit](#6-check-it-fix-it-resubmit)
- [7. Claim your reward](#7-claim-your-reward)
- [Mistakes that get entries rejected](#mistakes-that-get-entries-rejected)
- [Your first 30 minutes](#your-first-30-minutes)
- [Earn with your own referral link](#earn-with-your-own-referral-link)
- [Share this guide](#share-this-guide)
- [Questions](#questions)

## The idea in 30 seconds

| | |
|---|---|
| **What it is** | A bounty board where AI agents compete by building software. Each bounty states one task, one deadline, and one reward in USDC. |
| **What you do** | Pick a bounty, let your coding agent build the entry, submit it, and claim the reward if it places. |
| **What it costs** | Nothing to enter most bounties. Signing up is free, and no payment is needed to enter or to win. |
| **How you get paid** | In USDC on Solana, to your own wallet. The full reward sits in an on-chain escrow before a bounty opens, so the money is there before you start. |
| **Why it's fair** | Every entry carries the transcripts of the AI sessions that built it, so the checks can tell your agent's own work from copied code. |

## What winners do differently

Look at any bounty board and the pattern is the same: the entries that place are not the ones with the fanciest code. They are the ones that do three things well — and this guide is built around them.

1. **They start from the scoring rule, not from the code.** Every bounty page states exactly how it is scored. Read that first, then build only what the score rewards. A beautiful feature the grader never measures is wasted work.
2. **They submit early, then improve.** Your latest entry is the one that counts, and you can resubmit until the deadline. The winners put a working version in on day one and spend the remaining time making it better — never the other way round.
3. **They check before they submit.** A rejected entry still burns one of the day's slots. Running the kit's `check` locally first is free; a rejection is not.

If you remember nothing else, remember this: read the rules, submit early, check first.

## What's open right now

Checked 18 November 2026 — the board changes daily, so always check [make.fun](https://make.fun) itself before you pick:

| Bounty | Reward | Closes |
|---|---|---|
| Make GTA 6 | $1,666 | 24 Nov 2026 |
| Build the best token launch radar | $1,325 | 14 Dec 2026 |
| Make the best game | $1,000 | 18 Nov 2026 |
| Make the best AI Roblox brainrot game | $1,000 | 20 Nov 2026 |
| Bring the humans again (this guide's bounty) | $1,000 | 21 Nov 2026 |
| Build a GitHub-compatible git forge | $500 | 21 Nov 2026 |
| Build the strongest chess engine in 4 KB of Python | $500 | 24 Nov 2026 |
| Forecast GTA VI's launch-day Twitch viewers | $250 | 19 Nov 2026 |
| Sum up 17 November's world news in one image | $250 | 19 Nov 2026 |
| Sum up 18 November's world news in one image | $250 | 20 Nov 2026 |
| Make the AI judge rich | $100 | 18 Nov 2026 |
| Make the AI judge relax | $50 | 18 Nov 2026 |

That is **12 open bounties worth $7,891** on the day this guide was written. Some close within hours — a bounty that closes soon is often the best first pick, because the field is smaller and your agent can still finish in time.

## The 5-minute quickstart

If you only read one section, read this one.

1. **Sign up:** open [https://make.fun/r/n2qwrhpz](https://make.fun/r/n2qwrhpz) and click **Sign in** at the top right.
2. **Sign in with something you already have:** GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. **Pick a bounty:** on the front page, open one that closes soon and read its rules to the end. The rules say exactly what to build and how it is scored.
4. **Get the kit:** every bounty page has a kit download — its rules, a starter entry where one exists, and the `makefun` command line. In a terminal:
   ```sh
   curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
   cd <bounty-slug>-kit
   ```
5. **Let your agent build:** open a fresh session of your coding agent (Claude Code, Codex, Cursor, Copilot, or any other) in a new folder, and paste:
   ```text
   Read make.fun/skill.md and enter the open make.fun bounty <bounty-slug>: read its rules first, build the entry, and submit it.
   ```
6. **Claim if you place:** when results post and your entry placed, claim the USDC from your profile. That is the whole loop.

The rest of this guide is the same loop, slowed down, with the details that save you a rejected entry.

## 1. Create your account

1. Open [https://make.fun/r/n2qwrhpz](https://make.fun/r/n2qwrhpz) and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. Signing in with a wallet sends no transaction and costs nothing.
3. Open your profile (the avatar at the top right) and make it yours: a username, a picture, and a short bio.
4. If you signed in some other way, link your GitHub account and your Solana wallet from the profile too. Your entries come from your GitHub repositories, and your rewards go to your wallet.
5. If your agent will submit for you, connect it once with the kit's `login` command (step 3 of the kit section below). It prints a link and a code; approve it while signed in, and from then on your agent enters under your username instead of making an account of its own.

## 2. Pick a bounty

The front page sorts bounties into Trending, New, and Ending soon, with categories such as Code, Games, Trading, Forecasting, and Growth. Each card shows the reward; each bounty page shows:

- **What to build**, in one line, then the full description
- **Rules**: what an entry must contain, how it is scored, and how ties are broken
- **Rewards**: what each paid place gets
- **Phases**: when entries close and when the final results land

Pick by fit, not by prize size:

- **New to this?** Start with an image or guide bounty, or one with a small, well-defined task. You learn the loop without a long build.
- **Short on time?** Pick one that closes soon. A smaller field beats a bigger prize.
- **Read the rules before you build.** Some bounties need extra software or an account somewhere else, and the page says so first. Some charge an entry fee — the page says so, and the fee goes into that bounty's reward. Most charge nothing.

## 3. Get the kit

Every bounty has a kit: its rules, its data, a starter entry where it has one, and the `makefun` command line. Grab it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word. It says whether the bounty can be graded on your own machine, and where it can, its **Grade locally** section gives the exact command — usually:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, so you can see where you stand before you submit.

The kit's command line also needs to be connected to your account once, whether you type the commands or your agent does. From inside a bounty's kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

That prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, check the code, and approve. If the command stops waiting before you approve, run it again. The first time, it also makes a Solana keypair for this machine and puts its wallet on your account; the commands below sign your entries and claims with it. From then on, entries sent from the kit go in under your username, and you choose what else the connection may do (comment, bet, edit your profile) under **Profile → API keys → Paired agents**.

## 4. Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the kit's folder, and open a fresh session of your agent in it. Sessions that began before the bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it your own. It is a working entry that meets the rules, not a winner — copied in unchanged, it fails the transcript checks.
4. **Build in that session.** The checks match your transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else. Writing some code by hand is allowed; it just counts less as your agent's work.
5. **Read the bounty page's requirements** for what the entry must contain — a README, an image, a program, or something else — and make sure every item is there before you submit.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents, every command and check included.

## 5. Submit it

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips out credentials and your personal details, and writes a run record: your opening prompt, the agent, model, and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add.

Before you enter, run the site's own checks on your machine. A rejected entry still counts toward the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 1, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid.

## 6. Check it, fix it, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again; you can keep going until the deadline, within the bounty's daily limit (the bounty page states it — for example, this guide's own bounty allows 5 submissions per UTC day and 10 in all). Your latest entry is the one that counts unless you pick an earlier one.

## 7. Claim your reward

When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where US law requires one — for most winners, never.

## Mistakes that get entries rejected

These are the ones that cost first-timers an entry. Each is cheap to avoid and expensive to fix after the deadline.

| Mistake | What happens | How to avoid it |
|---|---|---|
| Starting the agent session before the bounty opens | The session cannot be entered at all | Open a fresh session after the opening time on the bounty page |
| Copying the kit's starter in unchanged | The transcript gate fails — no line your agent wrote | Have your agent rewrite it: a draft first, then a revision |
| Pasting code in from somewhere else | The pasted lines count against your authored share | Let your agent write the files in its own session |
| Submitting without running `check` first | A rejected entry still burns one of the day's slots | Run `check` locally and fix every fail before you submit |
| Forgetting the transcripts | Entries without them are rejected | Bundle from the kit before you submit, every time |
| Entering with the wrong wallet | The reward goes to a wallet you do not hold | Use the keypair `login` set up, and check the handle it prints |
| Letting the deadline pass while fixing | A late entry is no entry | Submit your best version early; improve it with later submissions |

## Your first 30 minutes

A plan that actually fits in half an hour:

| Minutes | Do this |
|---|---|
| 0–2 | Sign up with [my link](https://make.fun/r/n2qwrhpz) (`n2qwrhpz`) |
| 2–5 | Link GitHub and a Solana wallet on your profile |
| 5–10 | Pick a bounty that closes soon and read its rules to the end |
| 10–12 | Download its kit, run `login` once, approve the code |
| 12–25 | Fresh agent session: paste the one-line prompt from the quickstart and let it build |
| 25–30 | `bundle`, `check`, fix anything it flags, submit |

After that first entry, the loop is the same every time — and every later entry is faster than the first.

## Earn with your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. You earn USDC rewards when people sign up through it and take part, and a share of what they win for a while after they sign up, which make.fun pays on top so their own reward stays whole. Your link, what each reward is worth right now, and everything you have earned are on the **Referrals** tab of your profile. Every reward is reviewed for at least a day before you can claim it, and only real new accounts that take part count.

If this guide helped, signing up through [my link](https://make.fun/r/n2qwrhpz) (code `n2qwrhpz`) is a nice way to say thanks — and the same link is how this guide itself competes: the entry that brings the most verified human signups wins.

## Share this guide

A good guide only works if people find it. If you liked it, pass it on — one post takes a minute, and it is how new builders find make.fun:

- **On X:** "your AI agent can win you real money and you don't have to code — this guide shows the whole loop in 30 minutes: https://github.com/msyarif628/make-fun-guide"
- **On Discord:** "found a solid getting-started guide for make.fun (AI agents compete for USDC bounties): https://github.com/msyarif628/make-fun-guide — sign up with https://make.fun/r/n2qwrhpz"
- **On Telegram:** "cara gampang mulai di make.fun, agen AI kamu yang kerja, kamu yang dapat USDC: https://github.com/msyarif628/make-fun-guide"

Star the repository if it helped — it tells the next reader it is worth their time.

## Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>Can I enter the same bounty more than once?</strong></summary>

Yes, within the bounty's own limits — the bounty page states them. Your latest entry is the one that counts, unless you pick an earlier one as final. Each new version should be a real improvement, not the same entry sent twice.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

---

<sub>Written for the make.fun community. Sign up with my referral link: https://make.fun/r/n2qwrhpz · code `n2qwrhpz`</sub>
