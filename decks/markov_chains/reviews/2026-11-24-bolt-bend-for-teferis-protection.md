# markov_chains — Bolt Bend for Teferi's Protection, 2026-11-24

Proposed: **Bolt Bend** in, **Teferi's Protection** out (the Teferi's copy moves
to `choir_practice`; see `choir_practice/reviews/2026-11-24-teferis-protection-for-clever-concealment.md`).

List synced from Moxfield (last updated 2026-11-23T18:28:31.793Z). Context:
Edgar Markov · bracket 3 · $40/card cap · Game Changers 2/3 (Necropotence,
Teferi's Protection).

## Verdict: **NO** while Armageddon is still a regular threat in the pod.
**ADD IF** Armageddon has stopped appearing.

## The cards, verified (Scryfall, 2026-11-24 00:48 UTC)

- **Bolt Bend** `{3}{R}` Instant: "This spell costs {3} less to cast if you control
  a creature with power 4 or greater. Change the target of target spell or ability
  with a single target." Ruling: it can't hit a spell with more than one target.
- **Teferi's Protection** `{2}{W}` Instant, Game Changer: "Until your next turn,
  your life total can't change and you gain protection from everything. All
  permanents you control phase out."
- **Clever Concealment** `{2}{W}{W}` Instant, convoke: "Any number of target
  **nonland** permanents you control phase out."

## Why Teferi's is in this deck

It was added on 2026-08-31 (Addendum 1 of `2026-08-31-teferis-protection.md`) for
one reason: it was the **only card in the 99 that answers Armageddon**. Clever
Concealment can't, because it only phases out *nonland* permanents. The original
verdict before that pod fact was NO, because Teferi's turns off the life-change
engine (Vito, Marauding Blight-Priest, Bloodthirsty Conqueror) and phases out
your lands for a turn cycle.

That reasoning still holds. If Teferi's leaves:

| Threat | Before | After |
|---|---|---|
| Armageddon | Teferi's Protection | **nothing** |
| Exile wipe (Farewell) | Teferi's, Clever Concealment | Clever Concealment |
| Lethal aimed at you / combo kill | Teferi's | nothing |
| Single-target removal | Akroma's Will, Clever Concealment, Malakir Rebirth, Teferi's | Akroma's Will, Clever Concealment, Malakir Rebirth, **Bolt Bend** |

## Steel-man for Bolt Bend

When it's cheap, it costs one mana and does two jobs: it saves your creature, and
it sends their removal at one of their own. That makes it a counterspell and a
removal spell at once. It also redirects single-target abilities, so it can
protect Vito or Edgar from a kill spell.

## Why it doesn't take this slot

1. **It replaces the wrong category.** Bolt Bend adds a fourth answer to
   single-target removal, which already has three. Taking Teferi's out drops
   Armageddon answers from one to zero. That is the deck's worst gap.
2. **The discount isn't guaranteed.** Six creatures have base power 4 or more:
   Edgar Markov, Patron of the Vein, Anowon, Vein Ripper, Bloodthirsty
   Conqueror and High-Society Hunter (counted from `cards.json`). The 1/1 tokens
   that make up most of the board don't qualify without anthems. Without one of
   those six, it costs 4 mana.
3. **It does nothing against wipes.** Farewell and Armageddon don't target.

## If Armageddon is no longer common

Then Teferi's goes back to its original NO, and it's the right cut. Bolt Bend is
a reasonable fit at that point: cheap with Edgar out, and both protection and
removal in one card. **ADD IF**, cutting Teferi's Protection. This also frees a
Game Changer slot (2 → 1).

## Open question

Is Armageddon still showing up? The pod rotates between 10+ decks, and the
"commonly played" fact dates from 2026-08-31. The verdict depends on that answer.
The same fact affects the Choir Practice half of this swap.

## Prices (fetched 2026-11-24 00:48 UTC, own factor, not part of the case)

- Bolt Bend $6.47
- Teferi's Protection $47.38 (default print; you already own the copy)

The NO above does not depend on either price.

## Sources

- `card_facts.py lookup --rulings`, 2026-11-24 00:48 UTC.
- EDHREC: Bolt Bend is not in Edgar Markov's top, high-lift or new-card lists
  (`edhrec.py commander --diff`, 2026-11-24). Its top commanders are big-power
  red decks (Valgavoth 27.3%, Ob Nixilis Captive Kingpin 56.9%).
