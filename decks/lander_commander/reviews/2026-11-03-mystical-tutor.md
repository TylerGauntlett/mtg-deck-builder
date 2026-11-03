# Mystical Tutor — lander_commander (Aesi, Tyrant of Gyre Strait)

**Verdict: ADD, cutting Goldvein Hydra.** It takes the 3rd and last Game Changer slot.

Bracket 3, 4-player casual, $40/card cap. List synced from Moxfield (last updated
**2026-11-03T13:10:35.72Z**): 100 cards, 78 distinct. Oracle text, legality and prices
fetched **2026-11-03 13:15–13:16 UTC** via `card_facts.py lookup --rulings`.

## Verified text

> Mystical Tutor {U} — Instant
> Search your library for an instant or sorcery card, reveal it, then shuffle and put
> that card on top.

- Colour identity U, so it's legal. **Game Changer: yes.** The deck runs 2 of 3 (Cyclonic Rift,
  Rhystic Study); this one would fill the last slot.
- `combos.py --add`: **0 new combos** (baseline 12). Bracket-neutral apart from the GC count.
- EDHREC: doesn't appear in any section of Aesi's commander page. Its top homes are
  cEDH/spellslinger shells (Kraum/Tymna 83.2%, Rograkh/Silas 90.4%). That's no signal
  either way for this deck.
- Price: **$17.29** (2026-11-03 13:15 UTC). The verdict doesn't depend on price.

## Correcting the stated line

"Finale + Craterhoof at 10 mana": Finale is {X}{G}{G}, and Craterhoof is MV 8, so
Finale for Hoof is **X=8 = 10 mana**. Add Mystical's {U} and the line costs **11**,
unless Mystical goes off at an opponent's end step and you then draw normally. For
both pumps (Finale's "If X is 10 or more … +X/+X and haste" plus Hoof's own trigger)
you need X=10, which is **12 mana** for Finale alone.

## Best case

1. **It puts the card on top, and this deck draws extra cards in the same turn.** Cast
   it main phase, then play a land: Aesi ("Landfall — … you may draw a card"), Tatyova
   ("Landfall — … draw a card") or Growth Spiral ("Draw a card") pulls it into hand that
   turn. Waterlogged Grove and Yavimaya Elder also draw. The usual tutor drawback
   (no new card until your next draw step) mostly goes away here.
2. **Mystical → Finale holds up against the pod's mill.** Finale searches "your library
   and/or graveyard", so it still reaches a milled Craterhoof. Finale *puts* Hoof onto
   the battlefield, so counterspells aimed at Hoof miss.
3. **It does more than set up the kill.** It can find any of the 16 instants and sorceries (Instant 8,
   Sorcery 8, per `cards.md`): Cyclonic Rift (overloaded, it clears the board before an
   alpha strike), Counterspell / Arcane Denial / Beast Within against the combo player,
   Heroic Intervention to protect the swing, or Cultivate / Kodama's Reach / Growth
   Spiral early on. So it helps both the closing plan and the interaction gap the
   2026-09-01 audit flagged as the way this deck loses.
4. **It raises closer density.** It gives a second way to reach Hoof (Hoof itself and
   Finale are the others) and a fourth closer if you count Overwhelming Stampede. Odds of
   seeing one of them (hypergeometric over the 99): at 25 cards seen, Hoof access goes
   from **44% to 59%**. At 35 cards seen, it goes from 58% to 73%.

## The attack

- **It costs the last Game Changer slot.** That's what sank Narset on 2026-11-01. The
  difference is that Narset did nothing for the plan, while this card finds the finisher,
  the ramp and the answers. The audit's preferred use of the slot, Fierce Guardianship,
  now costs **$63.59** (13:16 UTC), so it's still ruled out by the budget cap.
- **It costs you a card.** Bad in a vacuum. In this deck it's partly offset by the draw
  engines in (1), but if Aesi isn't out, it's a real card down.
- **It's additive, not multiplicative.** The deck already has two ways to Hoof. The gain
  is consistency, not new power, and the honest size of that gain is the roughly +15
  points above.
- **Natural Order competes for the same slot**, and on your stated axis it's better:
  {2}{G}{G} plus sacrificing a green creature puts Hoof onto the battlefield for **4
  mana**, leaving 6 mana spare. Every token maker in the deck makes green tokens (Avenger
  Plants, Baloths Beasts, Scute/Springheart Insects, Roil Elementals, Greensleeves
  Badgers, Verdant Kraken Tentacles). Natural Order loses on everything else. It searches
  only your library, so a milled Hoof can't be reached. It's a sorcery, it does nothing
  early, and it never finds an answer. $35.48, GC, 0 new combos.
  **Mystical wins the slot because it covers both closing and interacting. Natural Order
  only closes.** If you care more about closing out a game than about answering the combo
  player, take Natural Order instead.

## Cut

| Rank | Card | Why |
|---|---|---|
| **1** | **Goldvein Hydra** ($3.72) | No landfall, no ETB, no land text; an X-body that's also the weakest finisher. The audit flagged it already. Cutting a creature keeps Mystical's 16 targets intact. |
| 2 | Herd Heirloom ($4.76) | Creature-only mana plus a trample/draw tap. Audit-flagged. |
| 3 | Negate | Audit-flagged, but it's interaction, and cutting it drops Mystical's targets to 15. |

Consistency note: the 2026-09-01 audit gave Goldvein Hydra's slot to **Reality Shift**
and Herd Heirloom's to Krosan Grip. Neither swap has been made two months on. If you
still plan to make them, take Mystical's cut from whichever of the two you're keeping
the card for, and don't count the same slot twice.

## Aggregate delta

- Game Changers **2 → 3** (now full: Rift, Rhystic, Mystical).
- Tutors for nonland cards: 1 → 2 (Finale, Mystical).
- Pips: G −1 (Hydra {X}{G}), U +1. Creatures −1. MV curve: one MV1 out, one MV1 in.

## What would change it

- Moving to a pod where you never need instant-speed answers → Natural Order is better.
- Fierce Guardianship falling under $40 → re-run the slot comparison.
