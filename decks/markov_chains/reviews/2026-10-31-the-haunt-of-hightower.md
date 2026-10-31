# markov_chains — The Haunt of Hightower (2026-10-31)

**Verdict: NO.** It competes for the 6-drop slot with Vein Ripper and Patron of the
Vein, and it's worse than both at what this deck asks a 6-drop to do.

Deck state: synced from Moxfield (updated 2026-10-31T03:20:30.44Z), exit 0. 100
cards, 34 lands, avg non-land MV 2.92, pips B 63 / W 20 / R 4. Bracket 3, $40/card
cap, Game Changers 2/3 (Necropotence, Teferi's Protection).

## The card (Scryfall, fetched 2026-10-31 23:55 UTC)

> **The Haunt of Hightower** `{4}{B}{B}` — Legendary Creature — Vampire, 3/3
> Flying, lifelink
> Whenever The Haunt of Hightower attacks, defending player discards a card.
> Whenever a card is put into an opponent's graveyard from anywhere, put a +1/+1
> counter on The Haunt of Hightower.

Colour identity B, Commander legal, not a Game Changer.
Ruling [2019-01-25]: the counter trigger **does not fire when a token goes to an
opponent's graveyard.**

Price: **$1.91** (fetched 2026-10-31 23:55 UTC). This is not a factor. The
rejection would stand if the card were free.

## Steel-man

It's a black Vampire, so casting it makes an eminence token. It's an evasive
lifelink body, so every point of combat damage it deals is life gained. That
triggers **Vito** ("Whenever you gain life, target opponent loses that much life")
and **Marauding Blight-Priest** ("Whenever you gain life, each opponent loses 1
life"). The deck's opponent-side removal feeds its growth trigger:

- Grave Pact: "each other player sacrifices a creature of their choice"
- Soul Shatter: "Each opponent sacrifices a creature or planeswalker"
- Anowon: "each player sacrifices a non-Vampire creature"
- Patron of the Vein's ETB "destroy". Patron then exiles the creature with a
  separate trigger *after* it dies, so the card still reaches the graveyard first
  and this is not a nonbo.
- Olivia's Wrath
- Ruthless Lawbringer

Every instant or sorcery an opponent casts also grows it. The case is a flier that
grows every turn cycle and turns each hit into a drain.

## Where it fails

**Redundancy at 6 MV (effect × frequency × duration).** The deck's 6-drops,
besides the commander:

| Card | Arrives doing | Ongoing |
|---|---|---|
| Vein Ripper | 6/5 flier, ward (sacrifice a creature) | **every** creature death, either side: drain 2, gain 2 |
| Patron of the Vein | 4/4 flier + destroys a creature | +1/+1 counter on **each Vampire** whenever an opponent's creature dies |
| **Haunt** | 3/3 flier, nothing else | grows **only itself**; one discard per attack, from one defender |

Haunt's growth trigger and Patron's trigger both fire on the same events. Patron
puts a counter on the whole board and Haunt puts one on itself. Vein Ripper's
lifegain is per death, not per hit, and it already feeds Vito and Blight-Priest
harder than one lifelink attacker can. The two cards Haunt would compete with are
strictly better in this list at the same mana value.

**Lifelink isn't scarce.** The deck already has lifelink on Henrika, Qarsi
Revenant, Elenda and Indulgent Aristocrat. It also has lifelink tokens from Edgar,
Charmed Groom, Baron Bertram and Charismatic Conqueror. Akroma's Will, Vito's
`{3}{B}{B}`, Sorin Imperious Bloodlord's +1 and Vault of the Archangel can each
grant team-wide or targeted lifelink. Haunt's "evasive lifelink feeds Vito" angle
is something the deck already has more than ten ways to do.

**Evasion isn't scarce either.** There are 11 flying creatures (script count):
Patron, Bloodline Keeper, Henrika, Mirkwood Bats, Bloodletter, Vein Ripper,
Bloodthirsty Conqueror, Qarsi Revenant, Welcoming Vampire, Carmen and High-Society
Hunter.

**Density / trigger scope.** The growth trigger is *opponents'* cards only, and
**tokens don't count**. Edicts are the deck's main way to put opponents' cards in
the graveyard, and Grave Pact, Soul Shatter and Anowon all let the **opponent
choose** what to sacrifice (Soul Shatter only within the greatest-mana-value
restriction). Against any token-producing opponent, the opponent hands over a
token and Haunt gets nothing. Discard on attack is also the discarding player's
choice, and it's worth little in the long games this pod plays, where hands are
empty by the mid-game.

**Marginal impact / worst case.** Cast into an empty board after a wrath, it's a
6-mana 3/3 with no protection and no ETB beyond the eminence token. Vein Ripper
taxes removal with ward, and Patron gets value the moment it resolves. Haunt only
pays off if it survives several turn cycles, which makes it the 6-drop that's
best when you're already ahead. That isn't a game-speed argument: the deck's
own 6-drops beat it at any game length.

**Cost of entry.** It's another 6 at the top of a curve that already has two
6-drops plus a 6-mana commander. Its `{B}{B}` is easy for this mana base, so the
cost here is the slot, not the colours.

## Calibration

- EDHREC: **1.3%** of Edgar Markov decks (683 / 52,398). Its homes are discard and
  mill commanders (Tinybones, Phenax, Tergrid, Aclazotz), where the growth trigger
  fires several times a turn. The community agrees with this verdict, and the
  independent reason is the 6-slot comparison above.
- Commander Spellbook: with the card added, **0** new combos (baseline 2 already
  assembled).

## Counter-proposal

None. The roles Haunt offers here (evasive top end, lifelink into Vito, growth off
opponent deaths) are each already covered several times over, by Vein Ripper and
Patron of the Vein in particular. There's no gap to fill. Haunt would earn a
slot in a deck that mills or discards opponents' cards several times a turn, and
this isn't that deck.

## Cut

Not applicable (NO).
