# Narset, Parter of Veils — lander_commander (Aesi, Tyrant of Gyre Strait)

**Verdict: NO.**

Bracket 3, 4-player casual, $40/card cap. List synced from Moxfield (last updated
**2026-10-31T03:28:18.567Z**): 100 cards, 78 distinct. Oracle text, legality and price
fetched **2026-11-01 15:11 UTC** via `card_facts.py lookup --rulings`.

Note: the request said `lander`; the only matching deck is `decks/lander_commander`.

## Verified text

> Narset, Parter of Veils {1}{U}{U} — Legendary Planeswalker, loyalty 5
> Each opponent can't draw more than one card each turn.
> −2: Look at the top four cards of your library. You may reveal a noncreature,
> nonland card from among them and put it into your hand. Put the rest on the bottom
> of your library in a random order.

- Colour identity U — legal. Commander legal.
- **Game Changer: yes.** Deck currently runs 2 of 3 (Cyclonic Rift, Rhystic Study).
  Narset would use the last slot.
- `combos.py --add`: **0 new combos** (baseline 12 assembled).
- Price: **$1.26** (fetched 2026-11-01 15:11 UTC). Not a factor; the verdict holds if free.

## Premise used

From the 2026-09-01 weakness audit (asked, not assumed): games run **turns 9–12**;
the pod's threats are **combo/spell-based kills, go-wide combat, mill, aristocrats**.
The verdict below leans on the opponent mix, not on speed.

## Best case

Scope check, axis "whose": the static reads **"Each opponent"** — so there is *no*
nonbo with Aesi ("Landfall — … you may draw a card"), Tatyova, Rhystic Study or
Nezahal. You keep drawing your deck; opponents are capped at one card per turn.
That also blunts the downside of Arcane Denial ("Its controller may draw up to two
cards" — capped at one under Narset). At MV3 it fills a curve slot, and the −2 digs
for interaction.

## The attack

**1. It spends the last Game Changer slot on a card that does nothing for the
deck's plan.** Zero text about lands, land drops or landfall; the deck's one stated
preference is cards that grant land drops, trigger on landfall or turn lands into
cards. Once Narset is in, any future Game Changer upgrade costs a cut of Rift or
Rhystic.

**2. The static is only as good as the opponents' multi-draw — and the pod's threats
mostly aren't that.** Against the four measured threats:
- Combo/spell kills: hampers a draw-engine combo player's setup; does not stop the kill.
- Aristocrats: caps draw-on-death engines at one per turn. Partial.
- Go-wide combat: no effect.
- Mill: no effect.
Two of four untouched, two partially. It is a hate piece whose value is set by
someone else's deck.

**3. The −2 adds to the category the deck is deepest in.** Card flow is already
the deck's strength: 4 repeatable draw engines (Aesi, Tatyova, Rhystic Study,
Nezahal) per the 2026-10-23 review, plus Growth Spiral, Urban Evolution, Arcane
Denial, Cultivator Colossus, Yavimaya Elder. Hit rate by hypergeometric on the 99:
27 noncreature nonland cards (Instant 8, Sorcery 8, Enchantment 6, Artifact 5) →
**~73%** to find *something* in four cards; 8 of those are actual interaction
(Arcane Denial, Counterspell, Negate, Beast Within, Pongify, Cyclonic Rift, Heroic
Intervention, Imprisoned in the Moon) → **~29%** per activation to find an answer.
Two activations, then she sits at 1 loyalty. Additive, not multiplicative.

**4. Worst case.** Early, she's a 3-mana walker that protects nothing and draws
attacks from the go-wide deck (Propaganda helps only if it's out). Late, with Aesi
online, the −2 is a worse version of what a single land drop already gives you.

**Disagreement check.** Narset does not appear in any listed section of Aesi's
EDHREC page. Her top homes are stax/control commanders (Grand Arbiter Augustin IV
45.5% of 14,427; Commodore Guff 69.5% of 7,801; Lavinia 52.9% of 3,604) — decks
whose plan *is* restricting opponents. This deck's plan is drawing its own cards off
lands. EDHREC and this analysis agree, for an independent reason.

## Cut

None — the card doesn't survive step 5.

## What would change the verdict

An opponent in the pod whose **win depends on drawing several cards per turn**
(wheels, draw-punisher like Niv-Mizzet or Kefka, a Sanctum Lurker/Locust God-style
draw engine). Then Narset is a cheap, one-sided hoser against the pod's scariest
deck and is worth the Game Changer slot. That's a fact about the pod I don't have.

## Counter-proposal

The real gap against the combo/spell player is still instant-speed answers — the
2026-09-01 audit's Krosan Grip / An Offer You Can't Refuse / Reality Shift swaps
were not applied (Herd Heirloom, Negate, Goldvein Hydra are still in the list).
Those answer the kill itself, cost no Game Changer slot, and remain the
recommendation.
