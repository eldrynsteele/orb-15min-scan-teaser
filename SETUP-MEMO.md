# ORB teaser — setup memo

Set up the free teaser in Muse. For best results, use Muse.

## Step 1 — Get Muse (skip if you already have it)

Join Muse here:
https://muse.ai/join

Redeem this invite code within 48 hours of joining:
**Code: B48FI2**

- On the Muse app, go to Settings > Redeem token and enter the code.
- On the web, go to Settings > General > Usage > Redeem invite code.
- Both sides get 1 billion Muse tokens when the code is redeemed.

## Step 2 — Install the teaser

In Muse, install the free teaser:

```
npx skills add eldrynsteele/orb-15min-scan-teaser
```

Repo: https://github.com/eldrynsteele/orb-15min-scan-teaser

## Step 3 — Tell Muse to read it, then run it

Tell Muse to read and learn the skill, then run the scan:

> Read the orb-15min-scan-teaser skill and run the 9:50 scan on SPY, QQQ, NVDA, QCOM, NBIS.

Use your own watchlist if you prefer — the scan works on any ticker with
real volume. Have your chart open: the scan marks the 9:30–9:45 ET opening
range, then looks for a candle CLOSE beyond it.

## Alternative — using another agent provider

If you prefer another agent provider, you can still use the teaser: give
your agent this repo's `SKILL.md` and ask it to run the 9:50 scan the same
way — same manual scan, same grades, same preview + explicit yes.

Best results are still with Muse. That is how the teaser is set up and
tested, and the full skill's pings install is written for Muse.

## Step 4 — What to expect

- Muse grades each ticker ready / waiting / rejected / already played out.
- Entries use 1:1 risk/reward. Nothing is ordered without a preview and
  your explicit yes.
- The teaser is an on-demand scan: you ask for a read, it answers. It does
  not send trade pings on its own, and it never places a trade.

If Muse does not seem to know the skill, tell it to read `SKILL.md` again
and run the scan.

## Trade pings

Trade pings come with the full `orb-15min-breakout` skill purchase — see
`PINGS-MEMO.md` in this repo. The full skill includes the install memo for
setting pings up on your own Muse agent.

## Disclosure

Educational tool, not financial advice. Trading involves risk and you can
lose money. No profits are promised and none should be expected.
