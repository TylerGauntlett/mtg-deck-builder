# Kalonian Hydra: NO

- Deck: lander_commander (Aesi, Tyrant of Gyre Strait), bracket 3
- Moxfield list last updated 2026-11-12T14:12:30.447Z (synced 2026-11-19, exit 0)
- Price: $6.88, fetched 2026-11-19 17:44 UTC. Under the $40 cap
- Legal in Commander, colour identity G, not a Game Changer. The deck holds 3 of 3 (Cyclonic Rift, Mystical Tutor, Rhystic Study). `meta.json` still says "currently 2", which is stale
- Commander Spellbook: 0 new combos, 0 near-misses (baseline 12)
- EDHREC: overall rank 1149. Its top homes are +1/+1-counter commanders (Gargos 82.9%, 7639/9214; Vorinclex, Monstrous Raider 54.1%, 2460/4546). It isn't in any of the Aesi page sections the script printed (new, top, high-lift)
- Pod premise used: games run turns 9–12; threats are combo/spell kills, go-wide combat, mill and aristocrats (asked in the 2026-09-01 audit, not re-asked here). The verdict doesn't rest on speed

## The card (Scryfall, 2026-11-19)

> {3}{G}{G} Creature — Hydra, 0/0. Trample.
> This creature enters with four +1/+1 counters on it.
> Whenever this creature attacks, double the number of +1/+1 counters on each creature you control.

Scope: "each creature **you control**". It triggers on attack only, so it needs haste or a turn cycle.

## Steel-man

It's a multiplier, which the rubric favours. It's a 4/4 trampler that becomes 8/8 on its first attack and 16/16 on its second. It also doubles every other creature with counters. In this deck those are:
- **Mossborn Hydra**: "enters with a +1/+1 counter" and "Landfall — double the number of +1/+1 counters". The two hydras multiply each other.
- **Avenger of Zendikar**: "put a +1/+1 counter on each Plant creature you control". The Hydra doubles a whole plant army.
- **Turntimber Symbiosis**: "enters with three additional +1/+1 counters" on a creature with MV 3 or less.
- Copies of the Hydra from **Springheart Nantuko** also enter with four counters. **Swiftfoot Boots** gives it haste, so it attacks the turn it lands.

## Why it fails

1. **Only three cards in the 99 put +1/+1 counters on anything:** Avenger, Mossborn Hydra and Turntimber Symbiosis (script grep of cards.json). The deck's token makers make plain bodies with no counters: Rampaging Baloths, Greensleeves, Scute Swarm, Zendikar's Roil and Verdant Kraken. Most of the time, then, the Hydra doubles only itself. The density test fails: 3 enablers against the roughly third of the deck a payoff needs.
2. **Finishers are the deck's most crowded role.** It already has Craterhoof Behemoth, Overwhelming Stampede, Finale of Devastation (X ≥ 10), Avenger, Rampaging Baloths, Greensleeves, Scute Swarm, Koma, Verdant Kraken, Cultivator Colossus and Mossborn Hydra. The Hydra's best line, doubling Avenger's plants, comes from a board that has already won. That makes it win-more.
3. **It doesn't touch the games this deck loses.** The audit's losses are to combo, go-wide, mill and aristocrats. Its gaps are instant-speed interaction, artifact/enchantment answers, sweepers and graveyard hate. A sorcery-speed beater answers none of them. Against aristocrats, the destroy-based removal the pod uses kills it and gets value from the death.
4. **No land text** (the deck's tiebreaker). It's the same objection the audit used to cut Goldvein Hydra and Ghalta, and both have since left the list. Adding a third non-landfall beater reverses that decision.

The NO doesn't depend on price; it would still be a NO if the card were free.

## Community check

Kalonian Hydra is popular in decks built around +1/+1 counters. This deck has three counter cards, and its token engines make bodies without counters. That difference explains why it isn't on Aesi's page.

## Counter-proposal

The role isn't real: the deck isn't short on finishers. The open gap is still interaction. The 2026-09-01 audit's swaps Krosan Grip, Reality Shift, An Offer You Can't Refuse and Aetherize are not in the current list. That's where a slot should go.

## Cut, for reference only

If you add it anyway: **Zendikar's Roil** (the same-role cut: a 5-mana finisher-engine whose 2/2s carry no counters), then Jin-Gitaxias, Progress Tyrant (MV7, no land text). Roil was the audit's own cut for Scavenging Ooze, and Jin-Gitaxias was its cut for Splendid Reclamation. Spending either slot on the Hydra uses up a cut the interaction plan needed.

## What would change this

If you add a counters package (Hardened Scales, Branching Evolution or similar) so that at least 6–8 cards put counters on your board, re-run this. That's a different deck, though.
