# choir_practice — Teferi's Protection for Clever Concealment, 2026-11-24

Proposed: **Teferi's Protection** in (the copy moving out of `markov_chains`),
**Clever Concealment** out.

List synced from Moxfield (last updated 2026-11-16T22:56:16.937Z). Context:
Giada · bracket 3 · Game Changers 2/3 (Drannith Magistrate, Farewell).

## Verdict: **ADD Teferi's Protection, but cut Valorous Stance, not Clever Concealment.**
(The ADD assumes you've decided Teferi's leaves Edgar. See the Markov review.)

## Verified (Scryfall, 2026-11-24 00:48–00:49 UTC)

- **Teferi's Protection** `{2}{W}` Game Changer: "your life total can't change and
  you gain protection from everything. All permanents you control phase out."
- **Clever Concealment** `{2}{W}{W}` convoke: "Any number of target nonland
  permanents you control phase out."
- **Valorous Stance** `{1}{W}`: "Target creature gains indestructible until end
  of turn" / "Destroy target creature with toughness 4 or greater."
- **Flawless Maneuver**, **Akroma's Will**: both give **indestructible**, so
  neither stops exile.

## Consistency with the 2026-10-02 reviews

The buildout review said Clever Concealment beats Teferi's **in this deck, at
$0**. Its reasons were: your lands stay in so you can still cast instants;
convoke is cheap here because the creatures are vigilant; it's selective, so
Ghostly Prison stays up; and the lifegain engine keeps running. All of that
still holds. The remaining-budget review set **Valorous Stance** as the cut for
Teferi's as Game Changer #3, and the Banishing Light and Greaves reviews both kept
it for that cut. Nothing in the list has changed that reasoning.

**New factor: Armageddon.** The Choir reviews never considered it. The Markov
reviews record it as common in the same pod. Clever Concealment can't answer it,
because it only phases out nonland permanents, and Teferi's can. That makes
Teferi's worth a slot here. It doesn't make Clever Concealment the right cut.

## Why Valorous Stance, not Clever Concealment

Answers to exile wipes (Farewell):

| Plan | Phasing answers | Armageddon answers |
|---|---|---|
| Your swap (TP for CC) | 1 (TP) | 1 |
| **TP for Valorous Stance** | **2 (TP, CC)** | 1 |

Your swap keeps one answer to exile wipes, and it becomes the one that also
phases out your lands, Ghostly Prison and the lifegain engine. Cutting Valorous
Stance keeps both. Valorous protects one creature from destroy effects only.
Flawless Maneuver, Akroma's Will and Clever Concealment already cover that, and
better.

## Costs to accept

- **Game Changers 2 → 3, the bracket-3 cap.** No more Game Changers can go in
  without cutting one.
- The Teferi's turn cycle shuts off lifegain payoffs and Prison, as recorded on 10-02.

## Prices (fetched 2026-11-24 00:48–00:49 UTC, own factor)

Teferi's Protection $47.38 (default print, already owned) · Clever Concealment $4.02 ·
Valorous Stance $0.30. The verdict doesn't depend on price.

## Sources

- `card_facts.py lookup`, 2026-11-24.
- EDHREC: Clever Concealment appears in 10.7% of Giada decks (4,272 / 39,897).
