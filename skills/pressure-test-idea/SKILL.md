---
name: pressure-test-idea
description: This skill should be used when a founder wants to evaluate, compare, or kill startup ideas — "pressure test my idea", "which of these ideas should I pursue", "is this a good startup idea", "should I quit my job for this", "rank my ideas", "/pressure-test-idea". Runs the idea filters used by solo founders on the Solo Founders Podcast and returns a scored verdict.
---

# Pressure-Test an Idea

Score one or more ideas against the filters successful solo founders actually used. Output a ranking and a decision.

Load `${CLAUDE_PLUGIN_ROOT}/skills/solo-founder-playbook/references/frameworks.md` (section 2).

## 1. Intake

Get, for each idea: one-line description, target customer, why now, and the founder's relevant history. If the founder supplied a memo or deck, read it. Ask for funding intent (venture / bootstrap / undecided) once.

## 2. The filters

Score each 0–2 (0 = fails, 1 = unclear, 2 = passes). Give one sentence of evidence per score — from what the founder said, not assumed.

| # | Filter | Question | Source |
|---|--------|----------|--------|
| 1 | Original insight | What do you know about this market that most insiders would disagree with? | Sunil Rajaraman, Ep. 9 |
| 2 | Right to win | Why you, specifically? Would this idea justify your resignation letter? | John Glasgow, Ep. 25 |
| 3 | Solo-buildable | Can one person (plus AI) ship a version customers pay for? | David Phillips, Ep. 11 |
| 4 | Capital-light start | Can it reach first revenue for ~$40K without raising? | Phillips, Ep. 11 |
| 5 | Domain + empathy | Are you the domain expert? Do you viscerally understand the buyer? | Phillips, Ep. 11 |
| 6 | Ten-year fit | Would you happily work on this problem for a decade? | Thais Castello Branco, Ep. 18; Sara Du, Ep. 32 |
| 7 | Extension of you | Does it extend your history, notes, network? | Yakko Majuri, Ep. 24 |
| 8 | Venture-sized *and* fast | (Venture only.) Is the market big and moving fast enough? | Jimmy Douglas, Ep. 10 |
| 9 | Be the only | Is there a way to be the only option for a specific buyer? | Office Hours, Ep. 29 |
| 10 | Dinner test | Would you want to talk about it at 10,000 dinners? | Dave Morin, Ep. 30 |

Skip filter 8 for bootstrapped ideas and note it.

**Kill rule:** Filters 1 and 2 are gates. Two zeros on gates = recommend not starting, regardless of total. (Rajaraman: no original insight, don't start.)

## 3. Disproof plan

For the top idea, write the cheapest test that could **disprove** it in two weeks (Douglas, Ep. 10). Name the specific signal that would mean "stop." Examples: a mini-product that gets ten paying customers (Phillips's Delaware franchise-tax tool, Ep. 11); a pricing page live before the product (Yasser Elsaid, first payment in 30 minutes, Ep. 6); a ~3,000-word memo that has to survive a skeptic (Paul Klein IV, Ep. 2).

## 4. Output

1. **Verdict line:** "Pursue X." / "Don't start any of these." / "Pursue X only if [test] passes."
2. **Scorecard table** (ideas × filters, totals).
3. **Why the winner wins** — two or three sentences, cited.
4. **Biggest risk** in one sentence.
5. **Two-week disproof test** with the stop signal.

Be willing to say none of the ideas clears the bar. Don't inflate scores to be encouraging.
