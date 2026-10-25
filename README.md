<p align="center">
  <img src="assets/panda.png" width="160" alt="Kesef+ panda holding a gold coin">
</p>

<h1 align="center">Money Skills for Claude</h1>

<p align="center">
  12 free Claude skills that help you make, keep and ask for more money.<br>
  Each one runs a <b>panel of Claudes</b> that interview you, argue, and hand you a real plan.
</p>

---

## Install (Claude Code)

```
/plugin marketplace add ilan-uzan/claude-money-skills
/plugin install money-skills@money-skills
```

Then type any command below, like `/hustle`, or just ask ("help me ask for a raise") and Claude picks the right skill.

**Without the plugin system:** copy any folder from [`plugins/money-skills/skills/`](plugins/money-skills/skills) into `~/.claude/skills/`.

## The skills

| Command | What happens | You leave with |
|---|---|---|
| [`/hustle`](plugins/money-skills/skills/hustle/SKILL.md) | 8 Claudes pitch 6 side hustles that fit your skills, then tear them apart | The one that survives + a 7-day plan to a first paying customer |
| [`/pitch`](plugins/money-skills/skills/pitch/SKILL.md) | "Sell me this pen": 5 Claudes play 5 tough buyers | A rewritten 30-second pitch + answers to the 3 objections you'll hear |
| [`/roast`](plugins/money-skills/skills/roast/SKILL.md) | A Claude head chef tastes every part of your business plan | The 3 changes that matter most, in order |
| [`/raise`](plugins/money-skills/skills/raise/SKILL.md) | A 6-Claude heist crew plans your raise and rehearses the meeting | The ask, the proof, the opening line and the fallback |
| [`/expenses`](plugins/money-skills/skills/expenses/SKILL.md) | 7 Claudes hold tribal council and vote off your subscriptions | A cancel list and the money you keep each year |
| [`/budget`](plugins/money-skills/skills/budget/SKILL.md) | 4 Claudes play Monopoly with your real budget | A simple monthly budget that adds up |
| [`/niche`](plugins/money-skills/skills/niche/SKILL.md) | 10 niches, 3 rounds, 1 rose | Your niche + a 7-day test to prove it |
| [`/clients`](plugins/money-skills/skills/clients/SKILL.md) | 9 Claudes play 9 possible dream clients | Your ideal client card + where to find the first 10 |
| [`/startup`](plugins/money-skills/skills/startup/SKILL.md) | 12 startup ideas enter the arena | One winner + a 2-week test before you build anything |
| [`/negotiate`](plugins/money-skills/skills/negotiate/SKILL.md) | Poker night: Claudes read your hand and play the recruiter | A counter-offer email and phone script |
| [`/price`](plugins/money-skills/skills/price/SKILL.md) | 3 Claudes fight for the low, fair and premium price | Your price, the math behind it, and how to test it |
| [`/quiz`](plugins/money-skills/skills/quiz/SKILL.md) | Who Wants to Be a Millionaire, for money habits | Your level + the 3 things to learn next |

## How they're built

Every skill follows the same shape:

1. **Interview first.** Claude asks for your real situation and waits. No generic advice.
2. **A panel of roles.** Several "Claudes" each judge from one angle (the customer, the accountant, the skeptic...) so you see the trade-offs, not one opinion.
3. **A verdict.** Scores, a winner, and why the others lost.
4. **A plan you can start today.** Concrete steps, ending with the next 30 minutes.

And the same rules: no income promises, no invented numbers or statistics (estimates are labelled), no scams, MLM or crypto signals. Not financial, legal or tax advice.

## Contributing

New skill ideas and fixes are welcome. Open an issue or a pull request. A good skill interviews before it advises, uses only the user's numbers, and ends with one concrete next action.

## License

[MIT](LICENSE). Made by [@kesefplus](https://www.instagram.com/kesefplus/). A new skill every few days.

If one of these helped you, a ⭐ helps other people find it.
