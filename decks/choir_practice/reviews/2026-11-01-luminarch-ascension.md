# Luminarch Ascension (2026-11-01): ADD IF, cut Metastatic Evangel

Moxfield list last updated 2026-10-31T03:18:51.177Z (sync exit 0, 100 cards).

## Verdict

**ADD IF most rounds at least two of your three opponents' turns go by without you losing life. Cut Metastatic Evangel.**
If two or more opponents hit you nearly every round, it's **NO**.

This reverses the 2026-10-02 build-out review, which rejected it in one line: "slow and turns off whenever you take damage." **The second half of that was a misreading.**
Losing life doesn't remove quest counters. It only skips the counter for that one turn. The card is a count of clean opponent turns, not a streak.

## Verified text

> At the beginning of each opponent's end step, if you didn't lose life this turn, you may put a quest counter on this enchantment. (Damage causes loss of life.)
> {1}{W}: Create a 4/4 white Angel creature token with flying. Activate only if this enchantment has four or more quest counters on it.

Rulings (2018-03-16):
- It checks the whole turn, even before the Ascension was on the battlefield.
- Gaining life doesn't offset losing it. "It doesn't care how much you lost, whether you also gained life, or even whether you gained more life than you lost."
- You can activate it in the same end step that it gets its fourth counter.

Colour identity W, Commander legal, not a Game Changer. Commander Spellbook: completes 0 combos and brings 0 within reach.

**Trigger scope:**
- Whose turn: **opponents' turns only**. Up to 3 counters per round in this pod, so a turn-2 cast can be making Angels in round 3.
- Who it watches: only you. Any life loss counts, from any source.
- Activation: unlimited, at instant speed, {1}{W} each.

## Best case

It's a 2-mana non-creature engine that turns spare mana into 4/4 flying **Angel** tokens at instant speed, as many as you can pay for. It survives every creature wipe, including your own Kindred Judgment and Farewell's creature mode.

## What each token triggers (verified from `cards.md`)

| Card | Clause | Effect per token |
|---|---|---|
| Giada | "Each other Angel you control enters with an additional +1/+1 counter … for each Angel you already control" | The token enters bigger. |
| Bishop of Wings | "Whenever an Angel you control enters, you gain 4 life" | 4 life. |
| Righteous Valkyrie | "Whenever another Angel or Cleric you control enters, you gain life equal to that creature's toughness" | 4+ life. |
| Seraph Sanctuary | "Whenever an Angel you control enters, you gain 1 life" | 1 life. |
| Youthful Valkyrie | "Whenever another Angel you control enters, put a +1/+1 counter on this creature" | One counter. |
| Cathars' Crusade | "Whenever a creature you control enters, put a +1/+1 counter on each creature you control" | A counter on each of your creatures. |
| Lyra Dawnbringer, Patchwork / Vanquisher's Banner (naming Angel) | static | +1/+1, and lifelink from Lyra. |

Each life gain then triggers Archangel of Thune, Lyra, Archangel of Dawn, Exemplar of Light, Dawn of Hope and Angel of Vitality.
One token with Bishop and Valkyrie out is 8+ life. That turns on the end-step token makers: Resplendent Angel ("gained 5 or more life this turn"), Valkyrie Harbinger ("4 or more") and Ob Nixilis, the Ascended ("if you gained life this turn"). All three check at **each** end step, so this works on opponents' turns too.
**That makes it a multiplier, not just one more token maker.**

Doesn't trigger: Folk Hero and Vanquisher's draw (both need a *cast* spell), and Metastatic Evangel (nontoken only).

## Tests

**Redundancy (effect × frequency × duration).**

| Source | Rate | Survives a creature wipe |
|---|---|---|
| Luminarch Ascension | one 4/4 Angel per {1}{W}, unlimited, instant speed | yes |
| Court of Grace | one per upkeep; a 4/4 only while you're monarch, otherwise a 1/1 Spirit | yes |
| Serra the Benevolent | one per −3, roughly every other turn | yes (planeswalker) |
| Resplendent Angel, Valkyrie Harbinger, Ob Nixilis | one per end step, needs a lifegain condition | no, they're creatures |
| Castle Ardenvale, Dawn of Hope | 1/1 non-Angels, mana sinks | yes |
| Emeria's Call | two, once | no (one-shot) |

**No other card makes Angels at an unlimited rate.** Court of Grace is the nearest match, and it has the same weakness: combat damage to you takes the monarchy.

**Density.** It needs mana and clean opponent turns. The deck has 37 lands, Land Tax, 4 rocks, 3 reducers and Three Tree City. The Land Tax review flagged flooding as a risk, and this is the deck's best mana sink.
For clean turns, the deck already runs four cards built to push attacks elsewhere: Ghostly Prison, Archangel of Tithes, Magus of the Moat and Authority of the Consuls. Magus ("Creatures without flying can't attack") lines up directly with the pod's recorded ground-attack wins.

**Marginal impact.** The recorded loss modes are wipes, Giada being removed, and ground alpha strikes. It helps against the first two. After a wipe, it's an untouched permanent that rebuilds at instant speed. It doesn't depend on Giada.
Against alpha strikes, a flashed-in 4/4 blocker in an opponent's combat (once it has 4 counters) is real, but small. **This is not a win-more card:** its best moment is the turn after a wipe.

**Cost of entry.** {1}{W}: one pip, cheap. It replaces a 2-drop, so the curve doesn't change.

**Anti-synergy and self-inflicted loss.** War Room ("Pay life equal to the number of colors…") and Emeria's land side ("you may pay 3 life") both cost life. **Only use them on your own turn**, where they don't matter. Opposing drain or symmetrical life-loss effects shut it off, and you can't control that.

**Worst case.**
- Opening hand: excellent, if the table leaves you alone early.
- Drawn on turn 12 with an empty board while you're being attacked: it needs 4 clean opponent turns, so it does nothing for two rounds. **Its dead end is being the focus of the table, and the user reported on 2026-10-28 that they're targeted a lot.** That's why this is an ADD IF and not an ADD.

**Speed premise.** The verdict depends on how often you lose life on opponents' turns, not on game length. The old "slow" objection assumed the deck closes fast. Nothing on file says it does.

**Disagreement check.** EDHREC: **33.4% of Giada decks (13,019 / 39,027)**, Giada's top home by count. This review now agrees with the community. The independent reason is the trigger table above plus the four attack deflectors, not the inclusion rate.

**Price:** $17.83 (foil $31.17), fetched 2026-11-01 15:36 UTC. Under the $40 per-card cap. The ~$300 total was likely already exceeded after Battle Angels (see the 2026-10-30 review). That's your call. **The verdict is on merit and would be the same if the card were free.**

## The cut: Metastatic Evangel

- It's the same 2-mana slot, so the curve is unchanged.
- It's a 3/1 Human, so it dies to your own Kindred Judgment naming Angel. The Ascension survives it.
- It doesn't trigger on tokens ("another **nontoken** creature"), so the Ascension's output never feeds it.
- Not the last of its role. Compounding counter engines that remain: Giada, Cathars' Crusade, Archangel of Thune, Lyra, Archangel of Dawn, and Norn's Choirmaster (proliferates on Giada entering or attacking).
- The Angel count is unchanged.

Runners-up, spared:
1. **Thraben Watcher.** Static anthems are the deck's deepest amplifier group (Lyra Dawnbringer, Field Marshal, Angel of Invention, two Banners, Elesh Norn). But it's an Angel: Giada counters, Bishop, Valkyrie and Folk Hero all key off it. Cut this instead if you'd rather keep the 2-drop count.
2. **Youthful Valkyrie.** Spared because the Ascension makes it better: it gets a counter for every token.
3. **Valorous Stance, Fateful Absence.** Still reserved as the cuts for Teferi's Protection and Darksteel Mutation.

## What would change the verdict

- **Two or more opponents make you lose life most rounds → NO.** At one clean turn per round it takes four rounds to come online.
- **The pod adds drain or Phyrexian-mana-heavy decks → NO**, for the same reason.
- **You keep Firemane Commando out** (the 2026-10-28 ADD IF wasn't taken). That's fine. The four deflectors already in the list are what this verdict leans on.

Play notes: activate it **before** the end step (main phase 2 or end of combat), not during it. That way Bishop's and Valkyrie's gains count toward Resplendent, Harbinger and Ob Nixilis that same end step. Don't activate War Room on an opponent's turn.
