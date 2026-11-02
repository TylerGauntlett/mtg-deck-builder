# Congregate (2026-11-02): NO

Moxfield list last updated 2026-11-02T17:52:50.333Z (sync exit 0, 100 cards).

## Verdict

**NO.** It's one burst of life, and the deck's lifegain payoffs reward many separate gains. The one thing it uniquely does, triggering the end-step Angel makers on an opponent's turn, is already done by cards that repeat. It does nothing on an empty board and little in the early game.

## Verified text

> Congregate {3}{W} — Instant
> Target player gains 2 life for each creature on the battlefield.

Ruling (2022-12-08): the creatures are counted as it resolves.
Colour identity W, Commander legal, not a Game Changer. Commander Spellbook: completes 0 combos and brings 0 within reach.

**Scope:** it counts **every** creature, including opponents'. **You** choose the target player, so it always goes to you. It's an instant, so you can cast it on any turn.

## Best case

Cast on an opponent's turn, before their end step, with 3+ creatures out (6+ life). It turns on all three "each end step" token makers that turn:
- Resplendent Angel: "if you gained 5 or more life this turn"
- Valkyrie Harbinger: "if you gained 4 or more life this turn"
- Ob Nixilis, the Ascended: "if you gained life this turn"

It also jumps life-total thresholds in one go:
- Righteous Valkyrie's +2/+2 anthem: "at least 7 life more than your starting life total"
- Angel of Vitality: "25 or more life"
- Angel of Destiny's win at "at least 15 life more than your starting life total". With 8+ creatures out, cast after combat damage, it's 16+ life by itself.

And it's a pseudo-fog against a ground alpha strike: a crowded board means a lot of life.

## Tests

**Effect × frequency × duration.** It's one lifegain event, once. Look at how the deck's payoffs are scored:

| Payoff | Clause | Congregate gives |
|---|---|---|
| Archangel of Thune | "Whenever you gain life, put a +1/+1 counter on each creature" | 1 trigger |
| Lyra, Archangel of Dawn | "Whenever you gain life, put a +1/+1 counter on each Angel" | 1 trigger |
| Exemplar of Light | "Whenever you gain life…" | 1 trigger |
| Dawn of Hope | "Whenever you gain life, you may pay {2}…" | 1 trigger |
| Angel of Vitality | "+1 instead" | +1 |

Four of the five payoffs count **events**, not amount. Congregate is the worst kind of lifegain for them. Bishop of Wings (4 per Angel entering), Righteous Valkyrie (toughness per Angel/Cleric entering), Seraph Sanctuary, and lifelink combat damage (from Lyra Dawnbringer, which gives "Other Angels … lifelink") each make an event per creature, every turn.

**Redundancy: the off-turn end-step role.** These permanents already gain life at instant speed or on opponents' turns, and they repeat:
- Luminarch Ascension: {1}{W} 4/4 Angel at instant speed. With Bishop and Righteous Valkyrie out, each one is 8+ life.
- Herald of Eternal Dawn: flash Angel, so Bishop and Valkyrie trigger.
- The Wandering Emperor: flash, and her −2 gains 2 life, which is enough for Ob Nixilis.
- Authority of the Consuls: "Whenever a creature an opponent controls enters, you gain 1 life", on their turn, which is enough for Ob Nixilis.

These cover what Congregate would add. They're engines that stay on the battlefield; Congregate is a single shot.

**Density / worst case.** It scales with the number of creatures out, so it's weakest exactly when the deck is losing:
- **After a wipe** (Farewell, Kindred Judgment, or an opponent's), both sides are empty, so it gains roughly nothing.
- **Turn-4 opening hand**, with ~3 creatures on the table: 6 life for 4 mana and a card.
- **Turn 12 with an empty board**: dead.
- It's only good when there's already a big board, which is when the deck is ahead. **That's win-more.** This doesn't depend on how fast games go: it's about board state, not the clock.

**Defence against the ground.** The pod's recorded loss mode is ground attacks. Congregate softens one attack and leaves the attackers on the battlefield. The deck already handles this layer with permanents: Ghostly Prison, Archangel of Tithes, Magus of the Moat ("Creatures without flying can't attack"). It also has instant-speed protection: Flawless Maneuver, Clever Concealment, Akroma's Will (lifelink + indestructible) and Herald of Eternal Dawn ("You can't lose the game"). That's eight cards before Congregate.

**Angel of Destiny line.** This is real, but it only works when one specific creature has survived to the end step after attacking. Angel of Destiny already makes its own life: "you and that player each gain that much life" on every combat hit. Congregate speeds that up by maybe a turn, in games where you already have the most creatures. That's win-more again.

**Cost of entry.** 4 MV with one pip. The deck's 4-drop slot is already crowded with must-play cards (Gisela, Field Marshal, Tithes, Battle Angels, Exemplar, Court of Grace, Serra, Wandering Emperor, Thraben Watcher, Magus). It's an Instant, not an Angel, so Giada's mana, Starnheim Aspirant, Urza's Incubator, Herald's Horn and Folk Hero do nothing for it.

**Disagreement check.** EDHREC: **1.5% of Giada decks (584 / 39,085).** Its homes are Hope Estheim (49%), The Archimandrite (47%) and Treebeard (30%). Those decks either convert life *amount* directly into an effect, or go very wide. Giada's payoffs count life events and Angels entering. I agree with the community, and for a reason of my own: the event-vs-amount table above.

**Price:** $0.18, fetched 2026-11-02 18:27 UTC. **This rejection would be the same if the card were free.** Price played no part in it.

## Cut

None. The card didn't survive the tests.

## Counter-proposal

None. The role it's aimed at (burst lifegain to hit thresholds and turn on the end-step makers) isn't a gap. Luminarch Ascension, which was just added, already does it repeatedly at instant speed. If the end-step makers aren't triggering in practice, the fix is more repeatable per-Angel gain, not a one-shot spell.

## What would change the verdict

- The deck adds payoffs that scale with the **amount** of life gained in one event, e.g. "whenever you gain life, create X tokens where X is the amount". It runs none today.
- Your games regularly end with you dying to a single huge ground swing that one big lifegain would have survived, *and* none of the eight defensive cards above were available. Tell me if that's what you're seeing.
