---
name: should-i-go-solo
description: This skill should be used when a founder is deciding whether to start alone or with a co-founder — "should I go solo", "do I need a co-founder", "should I bring on this person as co-founder", "my co-founder is leaving", "investors want me to have a co-founder", "/should-i-go-solo". Runs a short interview and returns a verdict.
---

# Should I Go Solo?

Give the founder a verdict on the co-founder question for *their* situation, not a general essay.

Load `${CLAUDE_PLUGIN_ROOT}/skills/solo-founder-playbook/references/frameworks.md` (section 1) and cite episodes from `episodes.md` in the same folder.

## 1. Interview

Ask only what the founder hasn't said. Use AskUserQuestion, max two rounds.

- **Situation:** pre-idea / have an idea / building / have revenue / raising.
- **Candidate:** Is there a specific co-founder candidate? How do they know each other, how long, have they shipped together?
- **Motive:** Why consider a co-founder? (investors expect it / missing skill / don't want to be alone / they're genuinely exceptional)
- **Gaps:** Which of the five tools are weak — product, sales, fundraising, hiring, operations? (Paul Klein IV, Ep. 2)
- **Funding path:** venture, bootstrapped, undecided.
- **Prior founding experience.**
- **Support system:** peers, advisors, community they talk to weekly.

## 2. Diagnose

Run these tests and record pass/fail:

1. **Convenience test.** Is the candidate chosen because they're available, or because they'd clear the bar of the best person you could ever hire? Convenience = fail. (Ep. 8, 14, 28)
2. **Prerequisite test.** Is the search delaying building? If yes, the search is the problem. (Ep. 7, 26)
3. **Ten-year test.** Would both of you plausibly stay a decade? (Grinich, Ep. 13)
4. **Decider test.** Who breaks ties? If unclear, expect debate instead of decisions. (Kuyda, Ep. 4; Cera, Ep. 38)
5. **Gap test.** Can the missing skill be hired, contracted, advised, or done by AI agents instead of given 20–50% of the company? (Hudson, Ep. 3; Vo, Ep. 20; Glasgow, Ep. 25)
6. **Isolation test.** Is the real motive loneliness? Then the fix is a peer group, not a co-founder. (Ep. 3, 28)
7. **Experience test.** First-time founder with three or more weak tools → the bear case applies. (Klein, Ep. 2)

## 3. Verdict

Lead with one of:

- **Go solo.** Name which type fits: True Solo, Free Solo, or Juiced Solo (Ep. 8).
- **Go solo now; elevate a hire later.** Build first; promote an exceptional early hire to co-founder-level equity if earned. (Ep. 26)
- **Take this co-founder.** Only if the candidate passes convenience, ten-year, and decider tests.
- **Don't take this co-founder — and don't search for another.**

Then:
- The two or three tests that decided it, each with its episode citation.
- **The honest bear case** for their path, in two sentences.
- **What to do this week:** three concrete actions (e.g., "list the five tools and who covers each," "book weekly time with two solo founders," "write the vesting and departure terms before any co-founder handshake").
- If they're keeping a co-founder: insist on standard vesting with a cliff and a written departure plan; dead equity is the common failure (Hudson, Ep. 3).

If the founder's co-founder is leaving, switch to breakup mode: clean severance and stock terms, move fast, tell investors early. (Phillips, Ep. 11)

Keep the output under 400 words. No reassurance padding.
