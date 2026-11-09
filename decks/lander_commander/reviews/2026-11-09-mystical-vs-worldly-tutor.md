# Mystical Tutor vs Worldly Tutor — lander_commander (Aesi, Tyrant of Gyre Strait)

**Verdict: NO. Keep Mystical Tutor; don't swap in Worldly Tutor.**

Bracket 3, 4-player casual, $40/card cap. List synced from Moxfield (last updated
**2026-11-04T15:25:39.92Z**): 100 cards, 78 distinct. Mystical Tutor went in for
Goldvein Hydra on the 2026-11-03 review. Oracle text, legality and prices were fetched
**2026-11-09 03:45–03:46 UTC** with `card_facts.py lookup`.

## The two cards are competing for one slot

Both are Game Changers. The deck holds 3 of 3: Cyclonic Rift, Rhystic Study and
Mystical Tutor. So Worldly can only come in by replacing Mystical, and the question
is which of the two is better.

> Mystical Tutor {U}, Instant: Search your library for an instant or sorcery card,
> reveal it, then shuffle and put that card on top.
>
> Worldly Tutor {G}, Instant: Search your library for a creature card, reveal it,
> then shuffle and put the card on top.

- **Targets**, from `cards.json`. Worldly can reach **28 creatures**: 29 creature cards,
  minus Aesi, who starts in the command zone. Mystical can reach **16 instants and
  sorceries**: 17 including the Turntimber Symbiosis MDFC, minus Mystical itself.
- `combos.py --add "Worldly Tutor"`: **0 new combos** (baseline 12).
- EDHREC: neither card shows up on Aesi's commander page. Both are mostly played in
  cEDH or high-power decks (Worldly: Kinnan 52.6%, Thrasios/Tymna 49.7%. Mystical:
  Kraum/Tymna 83.3%, Rograkh/Silas 90.5%). That tells us nothing about this deck.

## Worldly's best case

It gets **Craterhoof Behemoth** for 9 mana total ({G} + {5}{G}{G}{G}). Mystical gets
there through Finale of Devastation at X=8, which costs 11. Worldly gets **Kodama of
the East Tree** for 7 mana; the Mystical → Finale route costs 9. It can also find the
early engines directly: Lotus Cobra, Dryad of the Ilysian Grove, Azusa and Oracle of
Mul Daya. Like Mystical, it puts the card on top, so Aesi or Tatyova landfall draws it
the same turn.

## Why that isn't enough

1. **Mystical already reaches every creature Worldly does.** One of Mystical's targets
   is Finale of Devastation, which says *"Search your library and/or graveyard for a
   creature card with mana value X or less and put it onto the battlefield."* So
   Mystical → Finale finds any of the same 28 creatures, for **2 more mana**: a
   creature of MV *n* costs *n*+3 instead of *n*+1. In exchange, that route:
   - also searches the **graveyard**, so a milled Hoof or Kodama can still be found.
     Worldly only searches the library.
   - **puts the creature onto the battlefield** instead of casting it, so a
     counterspell aimed at Hoof can't stop it.
   - at X ≥ 10, also gives creatures +X/+X and haste.
   Worldly can't reach Finale, Cyclonic Rift, Counterspell, Arcane Denial, Negate,
   Beast Within, Pongify, Heroic Intervention or the ramp sorceries. What it adds over
   Mystical is 2 mana of efficiency. What it gives up is all of Mystical's
   non-creature targets.
2. **Your chances of reaching Hoof barely change.** In either version, the cards that
   lead to Hoof are {Hoof, Finale, tutor}. Mystical relies on Finale still being in the
   library. Worldly doesn't, so it's still live after Finale has been drawn or used.
   That only matters in games where you used Finale on something other than Hoof and
   still need Hoof afterwards. It's a real edge case, but a narrow one.
3. **The gap that loses this deck games is interaction, not closers.** The 2026-09-01
   audit found the deck loses to threats it can't answer. Mystical can find 8 answers:
   Rift, Counterspell, Arcane Denial, Negate, Beast Within, Pongify, Heroic Intervention
   and Overwhelming Stampede. The last one isn't an answer, but it's a finisher that
   isn't a creature. Worldly's answer-shaped targets are creature ETBs: Acidic Slime,
   Reclamation Sage and Terastodon. Each one hits one target at sorcery speed, and the
   deck already has them.
4. **Early game is a wash.** Worldly → Cobra/Dryad/Azusa is a better turn-2 play than
   Mystical → Rampant Growth or Growth Spiral. It's an additive gain, in a deck that
   already runs 43 lands plus Exploration, Burgeoning and those same three creatures.

**Worst-case draws.** Drawn on turn 12 with Hoof gone: both tutors still work. Worldly
finds Kodama or Avenger; Mystical finds Rift, a counter or Finale for Kodama. Drawn
facing a combo player: only Mystical can find something that stops them.

## When Worldly would be the right card

- **If Finale of Devastation leaves the deck.** Then Mystical has no way to reach
  creatures, and Worldly becomes the only tutor for the deck's finishers.
- **If you'd rather spend a different Game Changer slot.** Swapping Rhystic Study for
  Worldly so you can run both tutors is a separate question. It would trade a draw
  engine for a second consistency card. This review doesn't recommend it.

## Price (its own factor)

Worldly Tutor **$30.05**, Mystical Tutor **$17.60** (2026-11-09 03:45 UTC). Both are
under the cap. The verdict would be the same if Worldly were free.

## Housekeeping

`meta.json` still says "currently 2: Cyclonic Rift, Rhystic Study." With Mystical in,
the deck has 3 Game Changers.
