# markov_chains — Preacher, Markov Baron, Elas il-Kor, Vraan (2026-11-02)

List re-synced: unchanged (Moxfield 2026-10-31T03:20:30Z). That means the
Procession-for-Bastion swap from this morning's review hasn't been applied yet.
I'm treating it as pending: **Bastion counted as leaving, Procession as coming in.**

## Verdicts

| Card | Price (Scryfall 2026-11-02 04:59 UTC) | Edgar decks (EDHREC, n = 52,441) | Verdict |
|---|---|---|---|
| Elas il-Kor, Sadistic Pilgrim | $2.78 | not in its top-24 commanders | **NO** — close. The only one here that does something new, but the cut it needs costs a Vampire |
| Markov Baron | $0.36 | 49.3% | **NO** — sixth static Vampire anthem |
| Preacher of the Schism | $0.86 | 19.8% | **NO** — good card, no cut in the 3-slot |
| Vraan, Executioner Thane | $0.62 | 8.0% | **NO** — a drain payoff, the tier I cut Bastion from this morning |

Commander Spellbook: **0 new, 0 near** combos for all four. None is a Game Changer.

---

## Elas il-Kor, Sadistic Pilgrim — NO (closest call)

> `{W}{B}` Legendary Creature — Phyrexian Kor Cleric 2/2, deathtouch —
> *Whenever another creature you control enters, you gain 1 life. Whenever another
> creature you control dies, each opponent loses 1 life.*

**Best case.** The death half is a copy of Cruel Celebrant. The enter half is new.
Every creature entering, tokens included, gains 1 life. With **Vito** (*"Whenever
you gain life, target opponent loses that much life"*) or **Marauding
Blight-Priest** (*"each opponent loses 1 life"*), that becomes an Impact Tremors on
top of the drain. Procession doubles the tokens, so it doubles those triggers.
It's a link between the go-wide plan and the drain plan, the kind of card the
rubric says not to under-rate.

**Why it falls short:**
- **The new half needs one of two specific cards.** Only Vito and Blight-Priest
  turn life gain into damage. Without them, it's 1 life per creature.
- **The death half repeats a category I just cut from.** The payoff tier is the one
  this morning's review trimmed by removing Bastion. Adding Elas on top of that
  would undo the reason Bastion went.
- **So the honest cut is Cruel Celebrant**, a same-cost, same-role swap. Elas has
  more text than Celebrant, but Celebrant is a **Vampire**, and in this deck that
  type is worth a lot. It makes a token through eminence every time you cast it.
  Forerunner can find it, and Herald's Horn makes it cheaper. It also gets bonuses
  from the five static anthems (Lord of Lineage, Stromkirk Captain, Captivating
  Vampire, Legion Lieutenant, Charmed Groom) and Edgar's attack counters. Those
  are live every game. Elas's extra half is live only when Vito or Blight-Priest
  is out.

That's close, and I'd say so plainly. **What would change it:** adding a third
"whenever you gain life" payoff. Elas's enter half would then rarely be blank.

## Markov Baron — NO

> `{2}{B}` Vampire Noble 2/2, convoke, lifelink — *Other Vampires you control get
> +1/+1.* Madness `{2}{B}`.

The best case is its 49.3% rate on the Edgar page, and convoke makes it close to
free on a wide board. But the deck already has five static Vampire anthems
(listed above). This would be the sixth, in the category Door of Destinies (08-31),
Vanquisher's Banner (09-03) and Heraldic Banner (10-28) were rejected from. None of
the drain payoffs care about power. It also adds to the crowded 3-slot. Madness
does nothing here, because nothing in the deck discards. The NO holds even though
the card costs nothing.

## Preacher of the Schism — NO

> `{2}{B}` Vampire Cleric 2/4, deathtouch — attacking the player with the most life
> makes a 1/1 lifelink Vampire. Attacking while *you* have the most life draws a
> card and costs 1 life.

**Best case.** This deck gains life constantly, so you'll often have the most life,
and then it's a card every attack. It's a Vampire, and a 2/4 deathtouch holds the
ground.

**Why not.** It only pays off when it attacks, and as a 2/4 it can't attack safely
into most boards without the anthems. The draw category is deep: Necropotence,
Black Market Connections, Skullclamp, Welcoming Vampire, High-Society Hunter,
Bloodline Recollector, Vampire Gourmand, Idol of Oblivion, Baron, Clavileño,
Henrika. Vampire Gourmand (10-30) already fills the "card when it attacks" slot.
And there's no cut in the 3-slot: Forerunner is kept, and the rest are
interaction, engines or loop pieces (same finding as Mavren Fein this morning).

## Vraan, Executioner Thane — NO

> `{1}{B}` Phyrexian Vampire 2/2 — *Whenever one or more other creatures you
> control die, each opponent loses 2 life and you gain 2 life. This ability
> triggers only once each turn.*

It's a Vampire, unlike Bastion, and it drains for 2. But the drain fires *once a
turn*, so on a big sacrifice turn it's worth one Cruel Celebrant trigger. This
morning I cut Bastion because the drain-payoff tier was overstuffed. Adding Vraan
now would contradict that. At 8.0%, the community agrees.

---

## The batch

Four adds, zero honest cuts. All four would compete for the 2- and 3-slots, where
every remaining card has an earlier reason to stay. Elas is the only one that
offers something the deck doesn't already have, and even that depends on two cards
being out.

## Figures recorded

| Item | Value | Source / time |
|---|---|---|
| Moxfield last updated | 2026-10-31T03:20:30Z | `build_card_details.py` |
| Prices | Elas $2.78 · Preacher $0.86 · Vraan $0.62 · Markov Baron $0.36 | Scryfall, 2026-11-02 04:59 UTC |
| Edgar inclusion | Markov Baron 49.3% (25,855) · Preacher 19.8% (10,376) · Vraan 8.0% (4,192) · Elas not listed | EDHREC |
| Combos | 0 new / 0 near for all four (baseline 2) | Commander Spellbook |
| Static Vampire anthems | 5 | `cards.json` |
| "Whenever you gain life" payoffs | 2 (Vito, Marauding Blight-Priest) | `cards.json` |
