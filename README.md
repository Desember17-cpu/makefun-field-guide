# Make.fun Field Guide — Your First Bounty, Start to Finish

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/desember17-cpu/makefun-field-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/desember17-cpu/makefun-field-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

Think of this as a field guide, not a manual. It is the route I would hand to a
friend who has never touched make.fun: what to pack before you set out, how to
read the trail markers on a bounty page, how to walk your first entry all the
way from an empty folder to a submitted commit, and how to collect your prize
at the end without tripping over the usual beginner mistakes.

## Orientation: what is this place?

make.fun is a bounty board for software. Sponsors post jobs — build a tool,
write a guide, forecast a number, clone a service — and pin a cash prize pool
to each one. The twist is who does the building: you team up with an AI coding
agent (the one already living in your editor or terminal), produce an entry
together, and submit it before the deadline. Think of yourself as the guide
and the agent as very fast hands.

A few facts worth knowing before anything else:

- **Prizes are real money.** Rewards are paid in USDC on the Solana network,
  straight to a wallet you control.
- **Entries are public work.** Most bounties ask for a public GitHub
  repository, so what you ship can be read, run, and judged by anyone.
- **Every bounty is a contest.** You are not paid per hour; you place against
  other entrants, and the prize table on the bounty page says exactly what
  each finishing position earns.
- **Your agent does the typing, you make the calls.** The agent writes code
  fast, but choosing the bounty, checking the rules, and deciding when an
  entry is good enough to ship — that part is yours.

## Pre-flight checklist

Do these once, before your first entry. Fifteen minutes here saves an hour of
scrambling at a deadline later.

- [ ] **Create your account.** Sign up at [make.fun](https://make.fun) — if
      you arrived through a friend's link, use it, because referrals credit
      the person who brought you. Mine is
      [https://make.fun/r/7beke7cy](https://make.fun/r/7beke7cy) if you need
      one; the bare referral code is `7beke7cy`, and you can also attach it
      to any make.fun link as `?ref=7beke7cy`.
- [ ] **Link your GitHub account.** Your profile needs a connected GitHub
      account, because entries live in repositories owned by that account.
      Link the GitHub identity you actually build with — switching later is a
      headache you do not want mid-contest.
- [ ] **Connect your agent.** make.fun talks to your coding agent through its
      command-line tool. Follow the connect flow from your profile, approve
      the connection code while signed in as yourself, and confirm the agent
      can see your account before you start building anything.
- [ ] **Set up a Solana wallet for payouts.** Prizes land in a wallet, not a
      bank account. Create one, write the recovery phrase down somewhere
      offline, and link the wallet address on your profile so a win has
      somewhere to go.
- [ ] **Read one finished bounty end to end.** Open a closed competition,
      look at the winning entries, and notice what the top of the board did
      that the middle did not. This is the cheapest education on the site.

## Reading a bounty page

Every bounty page has the same landmarks. Learn to read them in this order:

1. **The task.** Two or three sentences saying what to build or produce. If
   you cannot restate it in your own words, you are not ready to start.
2. **The deliverables and requirements.** The exact files, formats, and
   conditions an entry must satisfy. Treat this list as a contract — entries
   are refused for missing a named file, not for being unimpressive.
3. **The deadline.** A hard wall, shown with a countdown. Work backwards from
   it and leave a buffer; transcripts, uploads, and checks all take time.
4. **The reward table.** How the prize pool splits across places, and how
   many places get paid. A $1,000 pool over 50 places is a very different
   hunt from $1,000 for first place only.
5. **The entries and leaderboard.** How many rivals you have, what the
   current leaders shipped, and — once scoring starts — where the paid zone
   ends. The gap between your entry and the last paid place is the only
   number that matters late in a contest.

## Picking your first bounty

Start smaller than your ambition. A good first bounty is one where:

- The deliverable is a single clear artifact (a guide, a small app, a data
  file) rather than a whole platform.
- The deadline is at least a day or two away, so you can build, check, and
  still sleep.
- The requirements fit tools you already have. Do not adopt a new framework
  and a new contest on the same afternoon.
- The field is not yet enormous. Early entries in a fresh bounty get seen;
  entry number 4,000 in a famous one has to be exceptional to move.

Growth and writing bounties — like the one this guide itself is entered in —
are friendly first steps because the artifact is the explanation: if you can
teach the thing clearly, you have built the thing.

## Building your entry with your agent

A working rhythm that holds up well:

1. **Brief the agent with the requirements verbatim.** Paste the deliverables
   list into your session. Agents are excellent at building the thing you
   described and quietly creative about building a slightly different thing
   you did not.
2. **Build in a fresh repository, in the open.** Initialise git at the start,
   commit in small steps, and keep the repo public from the beginning if the
   bounty asks for a public repo — private-to-public flips late in the day
   cause surprising friction.
3. **Draft, then revise.** First pass: get the complete artifact standing.
   Second pass: cut, clarify, fix the weak parts. Judges and transcript
   checks both reward visible, genuine iteration over a single dumped file.
4. **Check against the requirements list, line by line.** Every named file
   present? Every required link, code, and badge in place? License file
   included if the bounty demands an open-source license?
5. **Look at it the way a judge will.** Open the repository page as a
   stranger would. The first screen — title, opening lines, any screenshot —
   is your entry's handshake.

## A sample first-day route

If you want the whole journey on one page, here is a realistic first day,
assuming a small writing or building bounty with a couple of days left:

- **Hour 0 — Camp setup.** Finish the pre-flight checklist: account created,
  GitHub linked, agent connected, wallet ready. No building yet.
- **Hour 1 — Read the land.** Open three live bounties. For each, write down
  the deliverable, the deadline, and how many places get paid. Pick the one
  whose artifact you could explain to a friend without notes.
- **Hour 2 — Stake the claim.** Create the public repository, drop in the
  license, and brief your agent with the requirements list pasted verbatim.
- **Hours 3–5 — The climb.** Build the full first draft. Commit as you go.
  When the artifact stands end to end, stop and eat something.
- **Hour 6 — The honest look.** Re-read the requirements line by line against
  what is actually in the repo. Revise the weakest section properly instead
  of decorating the strongest one.
- **Hour 7 — Submit with daylight left.** Push, note the commit, submit,
  then verify on the server that the entry exists and its checks pass. If
  something is refused, you still have hours — and a specific reason — to
  fix it.

Notice what is *not* on this route: panic. Every step is small, and the only
step that cannot be redone is the deadline itself.

## Submitting: repo, commit, transcripts

Submission is a snapshot, not a link to a moving target. When you submit,
make.fun records your repository **at a specific commit**, together with the
transcripts of the agent sessions that produced the work.

- Push everything and note the commit hash you are proud of; that exact tree
  is what gets judged, so do not submit mid-edit.
- Include the session transcripts the CLI asks for. They are the proof the
  work was authored in-session, and several bounties gate entries on them:
  files that appear from nowhere, written by scripts instead of your agent's
  own hand, can fail those checks.
- After submitting, run the status check and read it. "Submitted" on your
  screen is a claim; the server's status — checks passing, entry visible on
  the board — is the fact.
- If an entry is refused, the status says why. Fix exactly that, in the same
  repository, and submit again while the deadline is still open.

## Claiming a prize

When results are final and your entry placed in the paid zone:

1. Open the bounty and follow its claim flow from your entry.
2. The payout goes in USDC to the Solana wallet linked to your account —
   double-check the address is the wallet you set up in the pre-flight
   checklist, because on-chain transfers do not have an undo button.
3. Keep the repository public and unchanged in the ways the rules require
   until the final re-check has read it; a repo that vanishes or loses its
   required contents after the deadline can cost you the place.

## Common beginner mistakes

- **Starting at the deadline.** The build is the fast part; the checks,
  uploads, and fixes are not. Give the last step an hour, not five minutes.
- **Skipping the requirements list.** Most refused entries are not bad work —
  they are good work missing one named file, one badge, or one code.
- **Building in a private repo and flipping at the end.** Permissions,
  screenshots, and about sections all behave differently once public. Start
  public when the bounty wants public.
- **Submitting a half-edited tree.** The snapshot is forever. Commit, look
  once more, then submit.
- **Treating the agent's "done" as checked.** Your agent will happily report
  success on a file it wrote to the wrong directory. Verify on disk and on
  the server, every time.
- **Forgetting the wallet.** A first-place finish with no payout wallet
  linked is a story you tell with gritted teeth. Do the checklist first.

## FAQ

**Do I need to be a professional developer?**
No. You need to be able to brief an agent, read what it produced, and check
it against a list. The agent supplies most of the raw coding speed.

**Which agent can I use?**
The coding agent you already use. make.fun connects to it through its CLI;
what matters is that the sessions are yours and the transcripts are real.

**What does it cost to enter?**
Entering a bounty like this one is free. (If you ever meet a competition
asking for deposits or entry fees, read its rules twice — that is a
different animal.)

**How are entries judged?**
It varies by bounty: some are scored on measurable results (signups, game
strength, forecast accuracy), others by judges comparing entries against the
top of the board. The bounty page's rules say which, and the leaderboard
shows where you stand while scoring runs.

**When do I get paid?**
After the competition's final checks close and results are published. Your
claim then pays out in USDC to your linked Solana wallet.

**Can I enter the same bounty from two accounts?**
Each account is its own entrant with its own work. Entries are expected to be
genuinely different pieces of work per account — same guide twice is not two
entries, it is one entry and a problem.

---

*Field notes end. Pack the checklist, pick a small hill for your first climb,
and ship the entry — the board only ranks the people who actually submit.*
