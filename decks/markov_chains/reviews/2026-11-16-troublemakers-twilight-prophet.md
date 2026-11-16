# markov_chains: Crossway Troublemakers, Twilight Prophet

| Card | Price (Scryfall, 2026-11-16 16:43 UTC) | EDHREC (Edgar Markov) | Verdict |
|---|---|---|---|
| **Twilight Prophet** | $4.00 | 45.8% (24,163 / 52,791) | **ADD**, cut **Malakir Bloodwitch** |
| Crossway Troublemakers | $0.33 | 29.0% (15,314 / 52,791) | **NO**. Its combat half is already Vault of the Archangel's job. Its draw half would be a third draw add, past the ceiling the 10-09 review set |

Moxfield list synced 2026-11-16 (Moxfield last updated 2026-11-09T14:08:42.433Z,
100 cards, sync exit 0). The list hasn't changed since this morning's Strefan
review. Commander Spellbook finds **0 new combos and 0 newly near** for either card.
Neither is a Game Changer. Both are mono-black, legal and inside the colour identity.

## Twilight Prophet: ADD

**Text:** `{2}{B}{B}`, Vampire Cleric, 2/4, flying, ascend. "At the beginning of your
upkeep, if you have the city's blessing, reveal the top card of your library and put
it into your hand. Each opponent loses X life and you gain X life, where X is that
card's mana value." Rulings: once you have the city's blessing, you keep it for the
rest of the game. Tokens and lands count toward the ten permanents. Lands reveal for
X = 0.

**Best case.** It's an engine: one extra card and a drain **every upkeep**, as long
as it lives. Neither half needs creatures to die or attack. Three verified cards in
the deck multiply the drain:
- **Bloodletter of Aclazotz:** "If an opponent would lose life during **your turn**,
  they lose twice that much". Your upkeep is your turn, so the drain is doubled.
- **Vito, Thorn of the Dusk Rose:** "Whenever you gain life, target opponent loses
  that much life". This turns the X life you gain into a second hit of X.
- **Marauding Blight-Priest:** "Whenever you gain life, each opponent loses 1 life".

Expected X: the deck's 100 cards average **1.94 mana value**, counting lands as 0.
So the baseline is about 2 to each opponent per upkeep, plus one card. With
Bloodletter it's about 4 to each opponent. With Vito out too, one opponent takes
about 6.

**Tests:**
- **Redundancy, as effect × frequency × duration.** The deck's other upkeep card
  engines are Black Market Connections (pay life to draw) and Herald's Horn (only
  hits Vampire creatures on top). No other card gives a card *and* drains every
  turn. The closest drain card is Malakir Bloodwitch: once, when it enters. That's
  a one-shot against an engine, so the two aren't redundant.
- **Ascend (10 permanents).** You control lands, mana rocks, creatures and Edgar's
  eminence tokens (every Vampire spell makes one, and **36** cards are Vampires).
  Ten permanents should come by turn 5 most games. The 10-02 goldfish checklist
  asked to confirm this; it's still worth watching. The blessing stays after a wipe.
- **Density.** Prophet needs only permanents on the battlefield, not a sub-theme.
- **Cost of entry.** `{B}{B}` is easy for a base built around 64 black pips. Prophet
  is a Vampire, so casting it makes an eminence token.
- **Worst case.** Early, or with no board, it's a 4-mana 2/4 flier until ascend. Not
  embarrassing, but it does nothing on turn 4.
- **Batch ceiling.** The 10-09 review said: *"if you also take Twilight Prophet, that
  is two card-advantage adds… Don't go past two."* Recollector was the first add, so
  Prophet is the second. That's at the ceiling, not past it.
- **Community:** 45.8%. I agree, for the reason above: card plus drain every turn,
  multiplied by three cards already in the deck.

### The cut: Malakir Bloodwitch

Bloodwitch's drain happens once, when it enters. Prophet's happens every upkeep. That
makes it a same-role swap (drain payoff), and it moves a 5-drop down to a 4-drop.
The 10-09 review already named Bloodwitch as the cut for exactly this card. Its old
case (protection from white against a white pod) went away with that pod premise on
2026-09-07. Vampire count is unchanged at 36.

**Runners-up, spared:**
- **Sanctum Seeker.** Spared this morning because it drains per attacking Vampire,
  so it scales with your board. That reason still holds.
- **Henrika Domnathi.** Her edict makes you sacrifice a creature too, which triggers
  Grave Pact and the death payoffs. Spared on the same reasoning as this morning.
- **Anowon, the Ruin Sage.** Spared on 11-02; nothing has changed.

## Crossway Troublemakers: NO

**Text:** `{5}{B}`, Vampire, 5/5. "Attacking Vampires you control have deathtouch
and lifelink." "Whenever a Vampire you control dies, you may pay 2 life. If you do,
draw a card." (Ruling: one payment and one draw per Vampire that dies.)

**Best case.** The draw half is a strong rate: one card per Vampire death, including
Edgar's tokens, for no mana. High-Society Hunter only draws on *nontoken* deaths, and
Baron costs `{1}{B}` per card. Troublemakers would link the go-wide plan to the
sacrifice plan: tokens become cards. Lifelink on every attacker also triggers Vito
and Blight-Priest once per creature that deals damage.

**Why no:**
1. **The combat half duplicates Vault of the Archangel.** Vault reads: "{2}{W}{B},
   {T}: Creatures you control gain deathtouch and lifelink until end of turn". It's
   the same pair of keywords, it covers *all* your creatures rather than attacking
   Vampires, and it takes up a land slot instead of a spell slot. Vito's
   `{3}{B}{B}` lifelink and Akroma's Will cover the same job.
2. **The draw half would be the third draw add.** That's past the ceiling, and the
   category is already about 13 deep: Skullclamp, Black Market Connections,
   Necropotence, Idol, Welcoming Vampire, High-Society Hunter, Baron, Gourmand,
   Recollector, War Room, Voldaren Estate, Henrika and Herald's Horn. Each draw also
   costs 2 life, in a deck already paying life to Necropotence and Black Market
   Connections.
3. **The 6-slot has no cut.** The 6-drops are Edgar, Vein Ripper and Patron of the
   Vein. Vein Ripper: "Whenever a creature dies, target opponent loses 2 life", the
   deck's strongest any-creature payoff. Patron of the Vein: it destroys a creature
   when it enters, and puts counters on each Vampire when opponents' creatures die,
   which happens with Grave Pact. A third 6-drop on top of a 6-mana commander makes
   the top of the curve worse.

**If the card were free:** it's $0.33, so price doesn't matter. The NO stands either
way.

**Troublemakers instead of Prophet?** No. Prophet costs two mana less, draws without
anything dying, drains, and fills a gap. Troublemakers' best half competes with
cards you already run.

## Open question (not decisive)

Do games still run long? This has been unanswered since 11-02. Prophet is a value
engine, so short games would weaken it. They wouldn't flip the verdict, though: it
replaces Bloodwitch, which is also a 5-mana drain, and it costs less.

## Figures recorded

- Twilight Prophet $4.00, Crossway Troublemakers $0.33 (Scryfall, 2026-11-16 16:43 UTC)
- EDHREC Edgar Markov: Prophet 45.8% (24,163/52,791); Troublemakers 29.0% (15,314/52,791)
- Commander Spellbook: 0 new, 0 near for each
- Deck average mana value over all 100 cards (lands = 0): 1.94; Vampires: 36
- Moxfield last updated 2026-11-09T14:08:42.433Z
