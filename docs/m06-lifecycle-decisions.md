# M6 · The Four Lifecycle Decisions

!!! abstract "Learning objectives"
    By the end of this module you will be able to:

    - Frame the only four decisions an investor ever really makes — **enter, stay, switch/shift, exit** — and apply a rule to each.
    - Choose between **lump sum, SIP and STP** at entry, and explain why *time in the market* usually beats *timing the market*.
    - Decide **how long to stay** by horizon and goal, and recognise the behaviour (stopping SIPs in a crash) that destroys the most wealth.
    - Know the *valid* reasons to **switch** a fund and the *valid* triggers to **exit** — and the friction (exit load, tax) that should make you pause first.

This is the **beginner** version. Each decision here returns in quantitative form later: entry in [**M12**](m12-valuation-aware-entry.md), monitoring/rebalancing in [**M13**](m13-monitoring-rebalancing.md), switch/exit tax-math in [**M14**](m14-tax-aware-exit.md). Tax mechanics themselves are [**M8**](m08-taxation.md) — here we keep tax as a "friction to remember", not a calculation.

---

## 1. Intuition first — investing is just four decisions, repeated

Strip away the noise and a fund investor faces exactly four decisions across a lifetime:

```mermaid
flowchart LR
    E["1 · ENTER<br/>how to put money in"] --> S["2 · STAY<br/>how long to hold"]
    S --> W["3 · SWITCH / SHIFT<br/>rebalance or change fund"]
    W --> X["4 · EXIT<br/>when to take money out"]
    W -.-> S
    classDef d fill:#e8eaf6,stroke:#3949ab,color:#1a237e;
    class E,S,W,X d;
```

Most investing mistakes are not stock-picking errors — they are **decision errors** at these four points: entering all at once and panicking, staying too short, switching for the wrong reason, or exiting in fear. Get the four right and average funds will serve you well; get them wrong and the best fund won't save you.

---

## 2. Decision 1 — When and how to **enter**

The question is rarely "should I invest?" but "**how should I deploy the money I have?**" Three tools:

- **SIP (Systematic Investment Plan)** — fixed amount monthly. Best for money you *earn over time* (your salary). It removes timing from the decision and gives rupee-cost averaging ([**M1**](m01-what-is-a-fund.md)).
- **Lump sum** — invest a large amount at once. Best when you have a windfall *and* a long horizon; statistically it often beats staggering because markets rise more often than they fall — but it carries **timing regret** if a crash follows.
- **STP (Systematic Transfer Plan)** — park a lump sum in a **liquid/debt fund** and *transfer* a fixed amount into an equity fund each month. A compromise: the un-deployed money earns a liquid return while you average in.

!!! note "Definition — STP (Systematic Transfer Plan)"
    A facility to move a fixed sum periodically from one scheme (usually liquid/debt) to another (usually equity) within the **same AMC**. It is the lump-sum investor's version of an SIP — averaging entry while parking the rest productively.

### Worked example 1 — lump sum vs STP for ₹12,00,000

You receive a **₹12,00,000** bonus and want it in equity.

- **Lump sum:** all ₹12L in equity today. If the market rises steadily, you capture the *full* rise — usually the higher-return path. If it falls 20% next month, you feel every rupee of it.
- **STP:** park ₹12L in a liquid fund (earning ~6–7%), transfer **₹1,00,000/month** to equity over 12 months. You average your entry price, the parked balance keeps earning, and a near-term crash hurts far less. The cost: in a *rising* market you give up some upside on the money still waiting.

**The rule:** for a long horizon and steady nerves, lump sum is statistically fine; if a near-term fall would make you panic-sell, **STP buys you the discipline to stay invested** — and discipline is worth more than the small expected-return give-up.

!!! tip "Why not just wait for a dip?"
    Because the dip you wait for may come only after a 30% rise you missed. *Time in the market* compounds; *timing the market* requires being right twice (when to leave, when to return) and most people are right neither time.

---

## 3. Decision 2 — How long to **stay**

The holding period should be set by the **goal's horizon**, decided **before** you invest — not by how the fund is doing.

| Horizon to the goal | Sensible vehicle | Why |
|---|---|---|
| < 1 year | Liquid / overnight | No time to recover from equity falls |
| 1–3 years | Short-duration debt / arbitrage | Low volatility, modest growth |
| 3–5 years | Hybrid / balanced advantage | Cushioned equity exposure |
| 5+ years | Equity (diversified) | Time for volatility to wash out |

The single most important behaviour is **not interrupting an SIP during a fall**. A market crash is when your fixed SIP buys the *most* units at the *lowest* NAVs — exactly the fuel for the eventual recovery. Stopping the SIP in fear converts a temporary dip into a permanent loss of those cheap units.

### Worked example 2 — the cost of pausing in a crash

You run a **₹10,000** SIP. In a sharp fall the NAV drops from ₹100 to ₹70. Your ₹10,000 now buys **142.9 units** instead of 100. If you *pause* the SIP "until things stabilise" and the NAV recovers to ₹110, you bought **zero** cheap units and resume only after the recovery — the most expensive possible behaviour. Staying invested means those low-NAV months become your best-performing instalments.

---

## 4. Decision 3 — When and how to **switch or shift**

"Switch/shift" covers two very different actions:

**(a) Rebalancing (shifting between asset classes).** Over time a rally pushes your equity weight above target; you **shift** some back to debt to restore your chosen risk. This is mechanical and *good* — it sells high and buys low automatically.

**(b) Changing a fund (switching schemes).** Replacing one fund with another. This is justified by **valid reasons only**:

- The fund **drifts from its mandate** / breaches true-to-label ([**M3**](m03-taxonomy.md)).
- A **persistent** underperformance versus its *category* over a meaningful period (not one bad quarter).
- A **fundamental change** — manager/AMC change you don't trust, mandate change, strategy change.
- Your *own* asset allocation or goal changed.

!!! warning "Switching has friction — pause before you do it"
    A switch is a **redeem + re-buy**: it can trigger an **exit load** (if within the load period) and a **capital-gains tax** event (computed in [**M8**](m08-taxation.md)/[**M14**](m14-tax-aware-exit.md)). Chasing last year's top performer by switching often costs more in tax and friction than the performance gap you're chasing. **Rebalance for risk; switch only for cause.**

### Worked example 3 — a rebalance in numbers

Your target is **60% equity / 40% debt** on a ₹10,00,000 portfolio (₹6L/₹4L). A strong year takes equity to ₹8L and debt to ₹4.2L — total ₹12.2L, now **65.6% / 34.4%**. To restore 60/40 you need ₹7.32L equity / ₹4.88L debt, so you **shift ₹0.68L from equity to debt** (ideally via an STP, and mindful of tax). You have just *sold equity high and bought debt low* — without forecasting anything.

---

## 5. Decision 4 — When to **exit**

Exiting should be **planned**, driven by one of three triggers — never by fear:

1. **The goal is near.** As a goal comes within ~2–3 years, **glide** money from equity to safer assets so a late crash can't derail it. (Life Cycle Funds from [**M3**](m03-taxonomy.md) automate exactly this glide path.)
2. **Asset allocation can't be restored by rebalancing**, or your risk capacity changed.
3. **A fundamental, lasting problem** with the fund that switching to a peer won't fix.

For *income* rather than a full exit, use an **SWP**:

!!! note "Definition — SWP (Systematic Withdrawal Plan)"
    A facility to **withdraw** a fixed amount periodically from a fund — the mirror image of an SIP. Used in retirement to draw a monthly "paycheck" from a corpus while the remainder stays invested. (Its tax efficiency vs IDCW is shown in [**M8**](m08-taxation.md).)

### Worked example 4 — gliding out as a goal nears

Your child's college fee of **₹15,00,000** is due in 3 years and you're at ₹14L in equity. A 30% crash in year 2 would leave ₹9.8L — a disaster with no time to recover. So you **glide**: move (say) one-third to debt now, another third next year, so that by the goal year most of the corpus is in short-duration debt and *certain*. You trade a little expected upside for the **certainty of meeting a non-negotiable goal** — the right trade when the money is *needed*, not merely *wanted*.

---

## 6. Common mistakes & Do's and Don'ts

!!! danger "Behavioural traps (the real enemy)"
    1. **Stopping an SIP in a crash** — forfeits the cheapest units; the costliest mistake of all.
    2. **Performance-chasing switches** — buying last year's winner, paying tax and load, then watching it mean-revert.
    3. **Waiting for the "right time" to enter** — the cost of being out usually exceeds the cost of a bad entry.
    4. **Exiting in panic** — converting a paper dip into a realised loss.
    5. **Setting the horizon by the fund's mood**, not by the goal decided up front.

!!! success "Do"
    - **Do** decide the **horizon and exit plan before** you invest.
    - **Do** use **SIP** for income-flow money, **STP** to deploy a lump sum you'd panic over.
    - **Do** **rebalance for risk** on a schedule; **switch only for cause**.
    - **Do** **glide to safety** as a needed goal approaches.

!!! failure "Don't"
    - **Don't** interrupt SIPs in downturns.
    - **Don't** switch funds for last year's returns without counting **load + tax**.

---

## 7. Applicable SEBI (Mutual Funds) Regulations, 2026

- **Exit load** framework — schemes may levy an exit load to deter quick redemptions; relevant to every switch/exit decision (and recall the 2026 removal of the 5 bps exit-load TER allowance, [**M4**](m04-cost-and-plans.md)). *[verify section no.]*
- **True-to-label & categorisation** — the legal basis for a *valid* "mandate drift" switch trigger ([**M3**](m03-taxonomy.md)). *[verify]*
- **Riskometer & product labelling** — schemes must display a standard risk label, helping the horizon-matching in Decision 2. *[verify]*
- **Life Cycle Funds** — the 2026 glide-path category that automates the Decision-4 exit glide. *[verify]*
- **SIP/STP/SWP** are scheme **facilities** operated within these rules, not separate regulations.

(The quantitative versions — valuation-aware entry, rebalancing bands, tax-aware exit calculus — are **M12–M14**.)

---

## 8. Key takeaways

!!! quote "Key takeaways"
    - Investing is **four decisions**: enter, stay, switch/shift, exit — most losses are decision errors here, not fund-selection errors.
    - **Enter** by SIP (for salary) or STP (for a lump sum you'd panic over); don't wait for a perfect dip.
    - **Stay** for the **goal's horizon**, and **never stop an SIP in a crash** — that's when it buys the cheapest units.
    - **Rebalance for risk; switch funds only for cause** — and count **exit load + tax** first.
    - **Exit on a plan**: glide to safety as the goal nears; use **SWP** for income, not panic.

---

## 9. A word from the field

!!! quote "On timing the market"
    *"Far more money has been lost by investors preparing for corrections, or trying to anticipate corrections, than has been lost in the corrections themselves."*

    — **Peter Lynch**, *One Up on Wall Street*. The four decisions are won by **discipline and patience**, not prediction: stay invested, automate, rebalance mechanically, and exit on a plan — not on a forecast.
