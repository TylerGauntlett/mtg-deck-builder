# markov_chains: Strefan, Maurer Progenitor

**Verdict: NO.** Strefan's output is Blood tokens, which are artifacts. Only 5 cards
in the 99 use them, and none of the 11 death payoffs that run the deck do. There's
also no honest cut among the 12 cards at 4 mana.

Moxfield list synced 2026-11-16 (Moxfield last updated 2026-11-09T14:08:42.433Z,
100 cards, sync exit 0).

## Card (Scryfall, fetched 2026-11-16 16:41 UTC)

Strefan, Maurer Progenitor `{2}{B}{R}`, Legendary Creature — Vampire Noble, 3/2.
- Flying
- "At the beginning of your end step, create a Blood token for each player who lost
  life this turn."
- "Whenever Strefan attacks, you may sacrifice two Blood tokens. If you do, you may
  put a Vampire card from your hand onto the battlefield tapped and attacking. It
  gains indestructible until end of turn."

Colour identity BR, inside Edgar's identity. Legal in Commander. Not a Game Changer.
Ruling (2021-11-19): a player counts as having lost life even if they also gained
that much or more.

**Price:** $0.65 (foil $0.57), fetched 2026-11-16 16:41 UTC. Under the cap, and it
plays no part in the verdict.

## Best case

This deck drains every opponent most turns, and you pay life yourself (Necropotence,
Black Market Connections, talismans, painlands, shocks, Voldaren Estate). So Strefan
should usually make 3 to 4 Blood tokens at each of your end steps. Those tokens feed
5 verified cards:

| Card | Clause | What a Blood token does |
|---|---|---|
| Mirkwood Bats | "Whenever you **create or sacrifice** a token, each opponent loses 1 life" | each opponent loses 1 when a Blood is made and 1 when it's sacrificed. Strefan's tokens arrive during your turn, so Bloodletter doubles the creation half |
| Baron Bertram Graywater | "one or more tokens you control enter… **only once each turn**"; "{1}{B}, Sacrifice another creature **or artifact**: Draw a card" | sac fodder that keeps your creatures on board. Edgar's eminence has usually used up the once-per-turn trigger already |
| Bartolomé del Presidio | "Sacrifice another creature **or artifact**" | free +1/+1 counters |
| Carmen, Cruel Skymarcher | "Whenever a player sacrifices a **permanent**" | counter and 1 life (which then feeds Vito and Blight-Priest) |
| Idol of Oblivion | "Activate only if you created a token this turn" | lets Idol draw on turns you cast no Vampire |

The attack trigger can also put Vein Ripper, Patron of the Vein or Malakir Bloodwitch
onto the battlefield without paying for them. Their enter-the-battlefield abilities
still work.

That clears the three-card synergy bar, so the synergy is real. The tests below are
about whether there's enough of it.

## Tests

**Density: fails.** The engine runs on creatures dying. These 11 cards trigger on
deaths, grouped by whose creatures count:

- *Any creature* (6): Blood Artist, Blade of the Bloodchief, Vein Ripper, Cordial
  Vampire, Elenda, High-Society Hunter (nontoken only)
- *Creatures you control* (4): Grave Pact, Cruel Celebrant, Bastion of Remembrance,
  Edgar, Ancient Bloodlord
- *Equipped creature* (1): Skullclamp

A Blood token isn't a creature, so it triggers **none of these 11**. It only turns
on 5 cards, which is about 5% of the deck. Without those 5, each token is a rummage
that costs `{1}` and a discard. That only filters your draws; it doesn't add cards
to your hand.

**Redundancy, as effect × frequency × duration.** Strefan makes 3 to 4 noncreature
tokens per turn, every turn, while it lives. The cap is the number of players, not
the size of your board. Compare Sanctum Seeker, the same-slot Vampire 4-drop: 1 drain
per attacking Vampire, every turn. That scales with how wide you are, which is what
the deck's plan builds. Strefan **adds** a fixed amount where Seeker **multiplies**.
The rubric's closing filter favours the multiplier.

**Cost of entry.** There are already 12 nonland cards at 4 mana: Akroma's Will, Baron
Bertram, Bloodletter, Bloodline Keeper, Clever Concealment, Edgar Charmed Groom,
Elenda, Grave Pact, Henrika, Mirkwood Bats, New Blood, Sanctum Seeker. The `{R}` is
not a problem, since the deck has plenty of red sources. The real problem is how
crowded the 4-slot is.

**Marginal impact.** Strefan doesn't fix the games you lose. Against a creature wipe
it dies too, and the leftover Blood tokens are just rummages. When you're out of
gas, rummaging needs cards in hand to discard. The attack trigger needs Strefan to
survive a full turn cycle, two Blood tokens and a Vampire in hand. By the turn all
that lines up, you usually have the mana to cast the Vampire anyway.

**Anti-synergy.** A Vampire put in by Strefan's attack trigger isn't cast, so it
gets no eminence token. That's minor.

**Combos:** Commander Spellbook finds 0 new combos and 0 newly near.

**Community:** EDHREC shows 9.7% of Edgar Markov decks run it (5,140 of 52,791). It
has 51% inclusion under Olivia, Crimson Bride and 70% under Anje, Maid of Dishonor,
both Blood or madness shells. My NO agrees with Edgar players, for my own reason:
Edgar decks win on creature deaths, and Blood tokens aren't creatures.

## The cut, if it were an add

Same role and slot: a 4-mana Vampire creature. Neither candidate is worse than
Strefan:
- **Sanctum Seeker.** It scales with board width (see above).
- **Henrika Domnathi.** This was the named cut on 11-02, then spared in favour of
  Bastion. Her edict mode makes *you* sacrifice a creature too, which triggers Grave
  Pact and the death payoffs. She feeds the core engine; Strefan doesn't.

I wouldn't cut any other 4-drop for Strefan either: they are lords, Grave Pact,
protection, or Bloodletter.

## Would the answer change if…

- **…the card were free?** No. It's $0.65, and price was never the reason.
- **…games run long?** That's still an open question from 11-02. Longer games give
  Strefan more end steps, so he gets closer. But the problem is density, not speed:
  Blood tokens still feed 5 cards, not the 11 death payoffs. The verdict doesn't
  depend on game speed.
- **…the deck added more artifact and token payoffs?** Then the density changes. But
  that would mean rebuilding toward a Blood shell, which isn't this deck's plan.

## Counter-proposal

None. The roles Strefan would fill, card flow and token fuel, are already deep:
Skullclamp, Black Market Connections, Necropotence, Idol, Welcoming Vampire,
High-Society Hunter, Baron, Gourmand and Recollector. Edgar's eminence is the deck's
token engine, and it makes creatures.

## Figures recorded

- Price $0.65 (Scryfall, 2026-11-16 16:41 UTC)
- EDHREC: 9.7% of Edgar Markov decks (5,140 / 52,791)
- Commander Spellbook: baseline 2 combos; +Strefan 0 new, 0 near
- Moxfield last updated 2026-11-09T14:08:42.433Z
