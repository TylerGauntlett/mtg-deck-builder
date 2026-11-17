# Shadowspear: which deck? (Choir Practice vs Markov Chains vs Lander Commander)

**Verdict: NO in all three.** If it goes anywhere, Choir Practice is the best home, but it doesn't beat a named card there either.

## Inputs

- Moxfield syncs (all succeeded, exit 0):
  - choir_practice updated 2026-11-16T22:56:16Z
  - markov_chains updated 2026-11-17T00:24:45Z
  - lander_commander updated 2026-11-12T14:12:30Z
- Shadowspear (Scryfall, fetched 2026-11-17 21:07 UTC): {1} legendary Equipment. "Equipped creature gets +1/+1 and has trample and lifelink. {1}: Permanents your opponents control lose hexproof and indestructible until end of turn. Equip {2}." Colourless, so legal in all three. Not a Game Changer.
- Price: **$31.12** (foil $41.12), fetched 2026-11-17 21:07 UTC. That's under the $40 per-card cap for every deck. I haven't recalculated Choir's ~$300 total budget.
- Commander Spellbook (`combos.py --add`): Shadowspear completes **0** new combos in each deck. Baselines are Choir 0, Markov 2, Lander 12.
- EDHREC: Shadowspear's overall rank is 306. Its top commanders are all Voltron or lifelink decks. It doesn't appear on the Giada, Edgar Markov or Aesi commander pages that `--diff` scanned.

## What the card actually offers

It's two cards in one, so I scored each half separately:

1. **The body: +1/+1, trample, lifelink on one creature.** Costs 3 mana to cast and equip, then 2 to move it.
2. **The answer: {1}, opponents' permanents lose hexproof and indestructible.** You can use it without equipping anything (2020-01-24 ruling). It only does something when you have a targeted or "destroy" answer to follow it with.

## Deck by deck

### Choir Practice (Giada): the best fit, still a no

- **The lifelink half lands in the deck's deepest category.** Six "whenever you gain life" or "if you gained life" payoffs: Archangel of Thune, Lyra Archangel of Dawn, Exemplar of Light, Resplendent Angel, Valkyrie Harbinger and Ob Nixilis the Ascended. That's what makes Choir the best home. But the deck already produces life all the time:
  - Lyra Dawnbringer gives every other Angel lifelink.
  - Gisela, Angel of Invention, Archangel of Thune and Valkyrie Harbinger have lifelink themselves.
  - Bishop of Wings gains 4 life whenever an Angel you control enters. Righteous Valkyrie gains life equal to a new Angel's or Cleric's toughness. Seraph Sanctuary gains 1 per Angel.
  - Angel of Destiny, Inspiring Overseer, Radiant Fountain and Authority of the Consuls also gain life.

  One more lifelink source is additive in a category that's already more than 15 deep. It doesn't multiply anything.
- **The trample half is close to nothing.** Almost every attacker in the deck flies. The pod note (most wins come through ground attacks) is about the opponents' plans, not something trample helps with.
- **The answer half is real but already covered.** Shadowspear would back up six targeted removal spells (Path, Swords, Generous Gift, Valorous Stance, Fateful Absence, Get Lost), plus Kindred Judgment and Ob Nixilis's destroy, against hexproof or indestructible. But Farewell (exile all, no targets) and Elesh Norn (-2/-2 to opponents' creatures) already get past both. That makes it a third out to a problem that comes up now and then, in a pod that rotates through 10+ decks.
- **Cut competition:** the weakest card is still Tome of Legends, and it's already the named cut for two conditional adds (Firemane Commando 11-08, Starnheim Unleashed 11-04). Past Tome, every card is one an earlier review defended for a specific reason. Shadowspear doesn't beat any of them. That's the same finding as the 11-13 Enlightened Tutor review.

### Markov Chains (Edgar Markov): second

- **Steel-man:** lifelink on an attacking Edgar Markov (4/4, first strike, haste, grows every attack) turns combat damage into drain through Vito ("whenever you gain life, target opponent loses that much life") and Marauding Blight-Priest. It does that every combat, so it's an engine, not a one-shot.
- **Attack:**
  - The deck already gains life constantly from death triggers and lifelinkers: Indulgent Aristocrat, Elenda, Qarsi Revenant, Vito's own activation, Vault of the Archangel and Sorin. Bloodthirsty Conqueror plus Vito is already a loop.
  - It competes for equip mana with Skullclamp, the deck's equipment card-draw engine.
  - The aggro plan goes wide with 1/1 tokens. Putting +1/+1 and trample on one of them does little.
- **The answer half is the least needed here.** Markov's interaction is mostly edicts that ignore hexproof and indestructible: Grave Pact, Soul Shatter, Anowon, Henrika's sacrifice mode.

### Lander Commander (Aesi): worst

- No lifegain payoffs in the deck.
- Trample is already covered for the finish by Overwhelming Stampede, Craterhoof Behemoth and Herd Heirloom.
- Cyclonic Rift's overload and Koma's tap/silence already handle hexproof threats.
- It contributes nothing to the deck's preferred axes: extra land drops, landfall, or turning lands into cards.

## Would a lower price change this?

No. Every rejection above holds even if the card were free. Price isn't part of the reasoning.

## What would change this

- **Choir:** you report losing games to hexproof or indestructible threats that Farewell and Elesh Norn couldn't reach in time. The answer half would then be filling a real gap. Tome of Legends would be the cut, if neither earlier conditional add has claimed it.
- **Markov:** the deck becomes Edgar-voltron, attacking with one big Edgar rather than going wide. That's a different deck.
