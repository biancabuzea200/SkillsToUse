---
name: gap-take
description: Turn a big claim, post or draft take into a deadpan quote-tweet using the gap technique, showing each step's result and a final ready-to-post tweet.
---

# Gap Take

Turns a big claim (someone else's post, a trending take, or the user's own rough draft) into a short, deadpan quote-tweet that quietly undercuts the claim by showing the real gap between effort and payoff.

The technique is reverse-engineered from a quote tweet by @paularambles.

The original post, by Paul Graham (@paulg):

> Amazon banning agents is the first opportunity I've seen since Amazon was founded for a startup to create an Amazon competitor. People will want agents to buy stuff for them. It will be one of the main use cases. And they won't want to use some Amazon-supplied agent to do it.

Paula's quote tweet of it:

> people want an agent to spend 40 minutes finding the best and cheapest vacuum cleaner so they can spend 10 seconds buying it themselves

Why it works:
- It rides a bigger account's reach (quote tweet).
- It disagrees without saying "actually". It describes real behavior and lets the reader see the claim focused on the trivial step.
- It mirrors the claim's own wording ("people will want" becomes "people want").
- It uses a concrete object (vacuum cleaner) and a lopsided ratio (40 minutes vs 10 seconds).
- Deadpan, lowercase, one sentence, no hashtags or emojis.

## Input

The user gives one of:
- A claim or post to respond to (e.g. "Airdrops build loyal communities.")
- A claim plus their own core idea or rough draft take

If the user gave a draft, start by rating it out of 10 with 2 to 4 specific improvement points, then run the steps using their insight as the starting point. Keep the user's insight whenever it is good. Do not replace it with a generic one.

If a personal-voice skill is available, apply it as the voice layer for the final drafts.

## The steps

Run every step in order. For each step, show a short header, one line on what the step does, and the result for this claim.

### Step 1: Isolate the core idea
State in one sentence the truth underneath that the claim misses. This is an opinion at this stage.
*Example (airdrops):* people are loyal to money, not to the community.

### Step 2: Turn the opinion into a behavior
Describe the exact observable moment the opinion becomes visible. Actions, not feelings. Include speed or time, since speed is often what makes it funny.
*Example:* people claim the airdrop, sell it on uniswap within 10 minutes, and mute the discord.

### Step 3: Find the claim's key word
Pick the one word the claim leans on most (e.g. "loyal", "community", "liquidity", "anyone", "build"). The final line must show the opposite of that word happening, and ideally reuse the word.
*Example:* "community". They don't leave the community, they use the word as a weapon while dumping.

### Step 4: Name both sides of the gap
List the big side (effort, money, time, hype invested) and the tiny side (the trivial payoff or how briefly it lasts). If there are several possible gaps, list them and pick the strongest, with one sentence on why. Prefer the gap that is most original over the one everyone has already posted.
*Example:* Gap A: months of points program vs 10 minutes of loyalty. Gap B: 10 minutes selling vs 1 hour writing a post about fairness to the community. Pick B, it's fresher.

### Step 5: Make it specific
Replace every category with an object and a number ("people" becomes "40,000 wallets", "a while" becomes "6 months", "settlement" becomes "a $500m bond settling in seconds instead of a day"). Flag any number that the user should verify before posting. Never present an invented statistic as fact.

### Step 6: Draft three versions from different angles
- The actor's view (the people doing the behavior)
- The other party's view (the project, company, or builder)
- Self-deprecating first person. Mark it "only post if true for you".

Useful shapes:
- "[who] want [big effort] so they can [tiny payoff]"
- "[who] [big effort], and then [ironic turn]"
- "[thing]: built for [claim's word], bought for [real reason]"

### Step 7: Cut and read aloud
Remove every word the line works without. Lowercase. One or two sentences. Under 280 characters. No hashtags, no emojis, no em dashes. Show the tightened versions.

### Step 8: Run the checklist and rate
Rate each tightened draft out of 10 against:
- Real gap: a big side and a tiny side
- Specific object and number
- Answers the claim's key word
- True, or flagged for checking
- Joke is about behavior, never about the person being quoted
- Reads naturally aloud

Pick the winner and say why in one sentence.

## Output format

```
[If the user gave a draft: Rating X/10 + improvement points]

## Step 1: Isolate the core idea
<result>

## Step 2: Turn the opinion into a behavior
<result>

## Step 3: Find the claim's key word
<word> + <what its opposite looks like>

## Step 4: Name both sides of the gap
Big side: ...
Tiny side: ...
(chosen gap + why)

## Step 5: Make it specific
<objects and numbers> + <numbers to verify>

## Step 6: Three drafts
1. ...
2. ...
3. ... (only post if true for you)

## Step 7: Tightened
1. ...
2. ...
3. ...

## Step 8: Checklist and ratings
1. X/10, reason
2. X/10, reason
3. X/10, reason

## Ready to post
> <final tweet>

When to post: quote a large account making this claim, within a few hours of their post.
Check first: <any number to verify, or "nothing to verify">
```

## Rules

- Never write an em dash anywhere in the output.
- Never attack the person being quoted. Redirect, don't fight.
- Never use "Not X, but Y" phrasing in the tweet.
- Never invent a statistic and present it as real. Flag it.
- Avoid AI vocabulary: delve, crucial, pivotal, landscape, foster, showcase, enhance, testament, underscore.
- Keep explanations in each step to one or two lines. The steps are for learning, so make each result visible, but don't pad.

## Worked examples from training

These are the user's chosen examples. Use them as the quality bar.

**Claim: "tokenization unlocks liquidity for real-world assets"**
- people want to buy 0.003% of a building in one click so they can spend 6 weeks figuring out how to sell it
- everyone says tokenization is about liquidity. banks want it so they can stop paying a back office to reconcile the same trade three times
- tokenization: built for liquidity, bought for settlement

**Claim: "vibe coding means anyone can build an app"**
- people vibe code a social media app in a weekend so they can message its only other user, their mum
- anyone can build an app in 3 prompts now. getting a second user who isn't your mum still takes 3 years
- vibe coded a social app this weekend. we're at 2 users. me and my mum. she's churning (self-deprecating: only post if true)

**Claim: "airdrops build loyal communities"**
- people sell their airdrop on uniswap in 10 minutes, then spend an hour writing a post about how the distribution was unfair to the community

**Claim: "agents will pay for everything with stablecoins"**
- people want an agent with a wallet so it can pay $0.002 for an API call, and then spend 20 minutes checking it didn't spend $200
