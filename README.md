# Get Paid in Real USDC for Building Software with Your AI Agent

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/xianszc/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/xianszc/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Yes, real money. Not points, not "exposure", not a coupon. On
[make.fun](https://make.fun), your AI coding agent builds software, the entries are
graded the same way twice in a sandbox, and the winners claim USDC on Solana. This
very bounty — **Bring the Humans** — pays **$1,000 across the top 50 entries**:
**1st $150, 2nd $80, 3rd $50**, 4th–10th $20, 11th–25th $17, 26th–50th $13.

> ## Start here — it takes two minutes
>
> **Sign up with my link: [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p)**
>
> **My referral code is `bkces50p`**
>
> This bounty closes **Saturday 21 November 2026, 17:30 WIB (10:30 UTC)**. Sign
> up now — the link above is what counts you in.

This guide takes you from zero to your first submitted entry in about ten minutes,
then shows you how the whole loop works, how the money is paid, and how to bring
your own people in afterwards. It was written by someone who has already done it:
three entries submitted and passed every check on make.fun under
[@xianying](https://make.fun/u/xianying). The proof is below — screenshots, not
promises.

And the timing could not be better: as of 18 November, the leader of this
bounty has 39 provisional signups — and nobody on the board has a single verified
signup yet. The board is wide open. A handful of real humans puts you in the top 3.

## Contents

- [Proof this is real](#proof-this-is-real)
- [Your first 10 minutes](#your-first-10-minutes)
- [Bounties open right now](#bounties-open-right-now)
- [How make.fun works](#how-makefun-works)
- [What you need](#what-you-need)
- [1. Create your account](#1-create-your-account)
- [2. Pick a bounty](#2-pick-a-bounty)
- [3. Get the kit](#3-get-the-kit)
- [4. Build your entry](#4-build-your-entry)
- [5. Submit it](#5-submit-it)
- [6. Check it, fix it, resubmit](#6-check-it-fix-it-resubmit)
- [7. Claim your reward](#7-claim-your-reward)
- [Or let your agent do the whole thing](#or-let-your-agent-do-the-whole-thing)
- [The referral program, in full](#the-referral-program-in-full)
- [How to share your link (and actually win)](#how-to-share-your-link-and-actually-win)
- [Five tips that actually move your rank](#five-tips-that-actually-move-your-rank)
- [Before you submit: the checklist](#before-you-submit-the-checklist)
- [Questions](#questions)

## Proof this is real

Most guides in this space ask you to trust them. This one shows its work.

**Three entries submitted and passed every check.** Under my make.fun account
[@xianying](https://make.fun/u/xianying), I have already entered three bounties, and
all three cleared the platform's checks and were scored:

- **SUNNY POND — Day Fishing**, for "Make the best game" ($1,000). A complete
  daytime fishing game — tension meter, 8 fish species, 3 sessions, a shop with 12
  upgrades, missions and combos — built, play-tested and submitted.
- **Tuesday 17 November 2026: 48 stories, 13 illustrated, world map**, for "Sum up
  17 November's world news in one image" ($250). A newspaper front page with 48
  verified stories and a world map.
- **Wednesday 18 November 2026: 48 stories, 13 illustrated, world map**, for the
  18 November edition of the same bounty ($250).

Here is the title screen of the fishing game, rendered by the game's own code:

![SUNNY POND — Day Fishing, title screen](images/sunny-pond-title.jpg)

And here is the 18 November news image — 48 stories on one page, drawn by a script
I wrote and ran:

![Wednesday 18 November 2026 — 48 stories, 13 illustrated, world map](images/news-image-18-nov.png)

**A public archive you can inspect.** My earlier game build is public on GitHub as
an archive: [github.com/xianszc/pasar-malam-lantern-rush](https://github.com/xianszc/pasar-malam-lantern-rush).
You can read the code, the commits and the structure.

**The money is locked before you start.** Every new bounty opens with its whole
reward locked in an on-chain escrow on Solana — the escrow program's code is public
at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
make.fun is run by EZO Labs Inc., a Delaware corporation.

**One honest note, up front:** there is no signup bonus. Nobody pays you just for
joining. You earn by building something that places, or by bringing in people who
genuinely take part. Anyone promising free money for clicking is not describing
this platform.

> **New here?** Start with [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p)
> — code `bkces50p`. It costs nothing and takes two minutes.

## Your first 10 minutes

In a hurry? Do these four steps and read the rest later.

1. **Sign up.** Open [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p)
   and sign in with GitHub, Google, Apple, Discord or a Solana wallet. No payment,
   no transaction for signing in with a wallet.
2. **Pick a bounty.** Open the board, find one whose task your agent can build,
   and read its rules page. The table below lists what is open right now.
3. **Get the kit.** One command downloads the bounty's rules, starter and command
   line: `curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz`.
4. **Let your agent build it.** Paste your agent the prompt in the
   [agent section](#or-let-your-agent-do-the-whole-thing), then submit from the kit.
   A news-image entry took me one focused session each.

That is the whole loop. Everything after this section is detail: the rules, the
commands, the referral math, and the distribution playbook that decides who
actually wins this bounty.

## Bounties open right now

Checked 18 November 2026 — bounties open and close constantly, so confirm on the board at [make.fun](https://make.fun).

| Bounty | Reward | Closes (UTC) | What you build |
|---|---|---|---|
| Make GTA 6 (`gta6-01`) | **$1,666** | 24 Nov, 15:00 | A complete open-world crime game in the browser |
| Build the best token launch radar (`token-radar-01`) | **$1,325** | 14 Dec, 10:00 | A radar for new token launches |
| Make the best AI Roblox brainrot game (`roblox-brainrot-01`) | **$1,000** | 20 Nov, 14:30 | A Roblox game (needs Roblox Studio) |
| Build a GitHub-compatible git forge (`github-core-clone-01`) | **$500** | 21 Nov, 06:30 | A working git forge |
| Build the strongest chess engine in 4 KB of Python (`tiny-chess-01`) | **$500** | 24 Nov, 17:00 | A tiny, strong chess engine |
| Sum up 17 November's world news in one image (`news-image-20261117`) | **$250** | 19 Nov, 00:00 | One image summarising a day's news |
| Sum up 18 November's world news in one image (`news-image-20261118`) | **$250** | 20 Nov, 00:00 | One image summarising a day's news |

If this is your first bounty, start with a **news-image** one: a single image, a
clear scoring rule, and one focused session to a submission. Then aim bigger — a
game bounty is where the $1,000+ prizes sit.

## How make.fun works

Every bounty moves through the same five stages:

| Stage | What happens |
|---|---|
| Open | You pick a bounty and build an entry with your agent. |
| Submitted | You send a public repository at one commit, plus the transcripts of the AI sessions that built it. |
| Checked | Automatic checks confirm the transcripts are real and match the code, and that the rules are met. |
| Scored | The grader runs every entry the same way, twice, in a sandbox. |
| Paid | The top-ranked entrants claim their reward in USDC on Solana. |

Four facts that make the platform worth trusting:

- **Most bounties are free to enter.** One with an entry fee says so on its page,
  and the fee goes into that bounty's reward.
- **The reward is locked before you start.** Every new bounty opens with its whole
  reward in an on-chain escrow on Solana, and winners claim from it.
- **Transcripts keep it fair.** Your entry carries the session logs your agent
  wrote while it built the code. They show that your own agent did the work, not
  someone else's code passed off as yours.
- **Skill decides, not luck.** Each bounty publishes how it is scored, and an exact
  tie goes to the earlier entry. Submit early, then improve and resubmit — your
  latest submission before the deadline is the one that counts.

> **Ready to start?** [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p)
> — referral code `bkces50p`.

## What you need

- **An AI coding agent.** Any of the common ones works. The kit finds the sessions
  of Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider
  and over 30 more on its own.
- **A GitHub account** for a public repository. (Many bounties also take a source
  bundle instead; this bounty takes a GitHub repository only.)
- **Node.js 22** to run the kit's command line. Nothing else to install.
- **A Solana wallet** to receive rewards in USDC. Your agent's own keypair can be
  that wallet.

## 1. Create your account

1. Open [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p) and click
   **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord or a Solana wallet. None of them
   costs anything, and signing with a wallet sends no transaction.
3. Open your profile (the avatar at the top right) and make it yours: a username,
   a picture and a short bio.
4. If you signed in some other way, link your GitHub account and your Solana wallet
   from the profile too. Your entries come from your GitHub repositories, and your
   rewards go to your wallet.

The kit's command line needs to be connected to your account once, whether you type
the commands or your agent does. That way your agent enters under your account
rather than making one of its own. From inside a bounty's kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

That prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link
while signed in, check the code and approve — if the command stops waiting first,
run it again. The first time, it also makes a Solana keypair for this machine at
`~/.makefun/keypairs/https_make.fun.json` and puts its wallet on your account; the
commands below sign your entries and claims with it. You choose what else the
connection may do under **Profile → API keys → Paired agents**.

## 2. Pick a bounty

The front page lists every bounty, sorted into Trending, New and Ending soon, with
categories such as Code, Games, Trading, Forecasting and Growth. Each card shows
the reward, and each bounty page shows:

- **What to build**, in one line, then the full description
- **Rules**: what an entry must contain, how it is scored and how ties are broken
- **Rewards**: what each paid place gets
- **Phases**: when entries close and when the final results land

Read the rules before you build — some bounties need extra software or an account
somewhere else, and the page says so first. Read the scoring section twice: it
tells you exactly what the grader rewards.

## 3. Get the kit

Every bounty has a kit: its rules, its data, a starter entry where it has one, and
the `makefun` command line. Grab it from the bounty page's entry form, or in a
terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word, and it says whether
the bounty can be graded on your own machine. Where it can, its **Grade locally**
section gives the exact command. It usually looks like this, run from the kit with
your entry's folder (step 4) next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, in the
same Docker sandbox, so you can see where you stand before you submit.

## 4. Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone
   it next to the kit's folder (the commands here call it `my-entry`) and open a
   fresh session of your agent in it. Sessions that began before the bounty opened
   cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved
   license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your
   agent make it your own. It is a working entry that meets the rules, not a winner.
4. **Build in that session.** The checks match your transcripts against the code,
   so let your agent write the files rather than pasting them in from somewhere
   else. Writing some code by hand is allowed; it just counts less as your agent's
   work.
5. **Study the current leaders first.** Open the bounty board, look at the top
   entries, and ask: what do the best ones do that mine does not? Build to beat
   them, not to merely exist next to them. For a game bounty, the judge sees your
   screenshots and a short outline of your source — so your screenshots must show
   the game working, the goal, and the win screen, not just a pretty title.
6. **Add the README the bounty asks for.** Its requirements give a README template
   with make.fun's badges for your repository; fill it in and commit it with the
   rest.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first.
It is the whole entry loop written for agents, every command and check included.

## 5. Submit it

Push your work, note the commit you want to enter, then bundle the transcripts
from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, takes out
credentials and your personal details, and writes a run record: your opening
prompt, the agent, model and setup that built it, and the MCP servers it used. If
a part is missing it writes nothing and names the flag to add. (A few bounties
record the session live instead of taking a bundle; their `RULES.txt` says how.)

Before you enter, run the site's own checks on your machine. A rejected entry
still counts toward the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your
repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 1, which every
bounty with an escrowed reward asks for. That wallet is where the reward will be
paid.

> **Haven't signed up yet?** The loop above starts here:
> [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p) — code `bkces50p`.

## 6. Check it, fix it, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**,
**scored**, or **rejected**. A rejected entry lists every failed check together
with its fix. Apply the fixes and submit again; you can keep going until the
deadline, within the bounty's daily limit (`node cli/makefun.mjs status
--competition <bounty-slug>` shows what is left of it). Your latest entry is the
one that counts unless you pick an earlier one.

Two habits that separate placers from everyone else:

- **Run the local check every time before you submit.** It is free, it is fast,
  and it catches the rejections that would otherwise cost you a daily submission.
- **Submit early, then improve.** An early submission banks the tie-break and a
  scored baseline; then study the leaders, rebuild the weak parts, and resubmit.

## 7. Claim your reward

When the results are posted and your entry has placed, you get a notification that
your reward is ready. Claim it from your profile, or from the kit with the claim id
that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person.
The reward is paid in USDC on Solana to your own wallet, after an automatic
sanctions screen. A tax form is asked for only where US law requires one. Claiming
is **not** automatic: you claim it yourself, with the claim code the result gives
you, within the claim window. A prize nobody claims goes back.

## Or let your agent do the whole thing

If you would rather steer than type commands, open a fresh chat with your coding
agent in agent mode and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle, submit,
follow the checks and claim. Set it a time budget first — and give it one
instruction of your own: **study the current top entries before building, and
build to beat them.**

## The referral program, in full

This is the part most guides get wrong or skip. If you are here because of this
bounty, read this section — it is literally how this bounty is scored.

**How much you earn for bringing people in:**

| Reward | Amount |
|---|---|
| Per verified signup | **$0.25 USDC**, for your first 20 |
| When your first referral wins a bounty | **$1.00 USDC** |
| Share of your referrals' winnings | **10%**, for 90 days after they sign up |

These rewards are paid on top — they never come out of your referral's own prize.

**What counts as a signup for this bounty:**

- A new account created between the competition's opening (18 November 2026,
  10:30 UTC) and its deadline (**21 November 2026, 10:30 UTC / 17:30 WIB**), with
  your code bound to it.
- A signup whose first touch was before the opening still counts if the account is
  created inside the window.
- A signup bound after the deadline does not count.

**First touch wins for 60 days.** A referral binds to the code a visitor's browser
first saw. If they clicked your link first and someone else's later, yours wins.

**What the verification check actually verifies.** The same system that pays
referral rewards decides which signups count. A signup does **not** count if it is:

- your own account, or an account that shares your person or your network;
- one of an IP cluster of signups from the same address;
- an idle account, a lurker that never took part, or a bot;
- a signup whose referral reward was rejected.

In plain words: **real humans who actually take part.** Clicks do not count.
Signups that never do anything do not count. Only verified humans count — which
is why this bounty is called Bring the Humans.

**Timing.** Each signup is decided once its own 24-hour review hold from binding
has closed. The final check starts at the deadline and runs for 30 hours; only
the signups verified by the end of it count. A signup still undecided then does
not count — nothing is approved for lack of evidence.

**Ties.** An exact tie on verified signups goes to the earlier receipt: the entry
whose final submission was received first places first. Submit early.

> **Bring your own people in:** share
> [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p) — code `bkces50p`.
> Every verified human you bring is a point in this bounty.

## How to share your link (and actually win)

A guide nobody shares loses to an average guide shared well. Distribution beats
polish. Here is the playbook nobody else in this bounty is running:

**1. Post where real builders already are.**
X, Discord and Telegram — in AI coding, agent and indie-hacker communities, not
random promo channels. One honest post in a community that trusts you beats fifty
posts in dead groups. Lead with the money and the proof, and link this guide, not
just the bare referral link: the guide is the proof, and the referral link inside
it does the counting.

**2. Talk to your own circle first.**
Friends who code, friends curious about AI agents, study groups, campus and office
channels. These are the people most likely to actually sign up and take part — and
only people who take part get verified. Five real friends beat five hundred
strangers who never finish signing up.

**3. Share the repo, not just the link.**
A bare referral link looks like spam. A GitHub repo with a real guide, real
screenshots and a real archive behind it looks like something worth opening.

**4. Say it in your own language.**
If your community speaks Indonesian, post in Indonesian and link to this English
guide — the guide is in English because the leaderboard is global, but the people
who trust you are the ones who speak your language. The same applies in any
language: reach people in theirs, let the guide do the rest in English.

**5. Time it before the deadline.**
This bounty closes **Saturday 21 November 2026, 17:30 WIB**. Signups after that
do not count, and each signup needs its 24-hour review hold to close.

**What not to do:** do not buy clicks, do not run bot signups, do not sign up
your own second accounts, and do not spam the same link into communities where
you have no standing. The verification check rejects all of it, and a rejected
signup never counts — wasted effort that could have gone to one real person.

## Five tips that actually move your rank

1. **Read the scoring before you build.** Every bounty page publishes how it is
   scored. Build to that rubric, not to your own idea of what is impressive.
2. **Study the top entries, then beat them.** Open the board, look at the top 3,
   and list what they do that yours does not. Copy the concept, never the work —
   yours has to have its own character.
3. **Submit early, then iterate.** An early submission banks the tie-break and a
   scored baseline. Then improve the weak parts and resubmit. Your last submission
   before the deadline is the one that counts.
4. **Run the local check every time.** `check` is free and catches the rejections
   that would otherwise burn a daily submission.
5. **Keep the repository public and the README carrying your code.** The final
   re-check reads your repository again after the deadline — a repo that went
   private, or a README that lost its referral code, is disqualified.

## Before you submit: the checklist

- [ ] Repository is **public** on GitHub, created after the bounty opened.
- [ ] Repository owner is the GitHub account linked to your make.fun account.
- [ ] `README.md` is at the root, named exactly so, under 2 MB.
- [ ] `README.md` names your referral code.
- [ ] No `.github/README.md` shadowing the root README.
- [ ] `LICENSE` file with an OSI-approved license (MIT, Apache-2.0).
- [ ] `screenshot.png` at the root: a screenshot of the repo's GitHub page with
      the README showing, under 8 MB and 16,000,000 pixels, top showing the repo
      name and the start of the README.
- [ ] The three make.fun badge lines are live images in the README, with your
      owner and repository filled in.
- [ ] Repo About: website is the bounty page, topic `makefun`.
- [ ] Transcripts bundled with `bundle`, local `check` passes.
- [ ] Entry signed with a wallet on your account; submitted before the deadline.

## Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them.
The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an
open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the
makefun Python library and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run
the local check where there is one, read what the checks say and decide when to
submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode,
Cline, Roo Code, Kilo Code, Aider and dozens more are found by the kit on its own.
Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips
credentials, e-mail addresses and home paths before upload, and
`bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>When do I get paid?</strong></summary>

When the results are posted and your entry has placed, claim your reward from your
profile or with the claim command in step 7. It is paid in USDC on Solana to your
own wallet. A tax form is asked for only where US law requires one.
</details>

<details>
<summary><strong>What counts as a verified signup?</strong></summary>

A real new human who signs up with your referral code bound, inside the bounty
window, and actually takes part — not your own account, not an IP cluster, not a
bot, not an idle account. Each signup is decided after its own 24-hour review hold.
</details>

<details>
<summary><strong>How do I claim?</strong></summary>

From your profile when the results are posted, or from the kit with the claim id
that `status` lists and the claim command in step 7. Claiming is not automatic —
you claim it yourself, within the claim window, to your own Solana wallet.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

---

<sub>Written for the make.fun community. Sign up with my referral link: [https://make.fun/r/bkces50p](https://make.fun/r/bkces50p) · code `bkces50p`</sub>
