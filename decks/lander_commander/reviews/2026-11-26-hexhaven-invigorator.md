# Hexhaven Invigorator: ADD IF (revised from NO)

- Deck: lander_commander (Aesi, Tyrant of Gyre Strait), bracket 3
- Moxfield list last updated 2026-11-12T14:12:30.447Z (synced 2026-11-26, exit 0)
- Price: $18.57 (foil $17.94), fetched 2026-11-26 18:13 UTC. Under the $40 cap
- Legal in Commander, colour identity G, not a Game Changer
- Commander Spellbook: 0 new combos, 0 near-misses (baseline 12)
- EDHREC: overall rank 6556. On the Aesi page it's the top "not in the deck" card: 10.2% (305/2997), synergy +0.08. Its top homes are Wayta, Trainer Prodigy (52.5%, 923/1758), Hearthhull (9.6%) and Ghalta, Primal Hunger (13.9%)
- Pod premise used: games run turns 9–12 (from the 2026-08-31 audit, not re-asked here). The verdict doesn't rest on speed

## The card (Scryfall, 2026-11-26)

> {G}{G}{G}{G} Creature — Chimera Horror, 6/6. Vigilance.
> Whenever this creature is dealt damage, you may search your library for up to that many land cards, put them onto the battlefield tapped, then shuffle.

Scope: the trigger is on damage dealt **to this creature**, from any source. It fetches **any** land cards, not just basics. It isn't a landfall card itself, but every land it fetches is a landfall trigger for the rest of the deck.

## Steel-man

When it fires, it's the strongest landfall multiplier the deck could run. Taking 4 damage puts 4 lands onto the battlefield at once. With Aesi that's 4 cards. Each land also triggers Tatyova, Rampaging Baloths, Greensleeves, Scute Swarm, Zendikar's Roil, Lotus Cobra, Tireless Provisioner, Avenger of Zendikar, Mossborn Hydra and Nissa, and Ancient Greenwarden doubles all of those triggers. A single trigger can be worth more than a whole turn. It's also a cheap 6/6 vigilance body at MV 4, which the curve is short on.

## Why it fails

1. **Nothing in the 99 damages it (density: 0).** I grepped cards.json for damage and fight text. The only hit was Yavimaya Coast, which damages *you*, not a creature. The deck runs no fight spells, no pingers and no damage sweepers. Wayta (its top commander at 52.5%) is a fight commander, and Ghalta and Hearthhull lists run the fight package. This deck runs none of it.
2. **That leaves the opponents in charge of the trigger.** It only fires if someone blocks it, attacks into it, or casts a damage-based removal spell or sweeper. A 6/6 that ramps when it takes damage is exactly the creature people stop blocking. After the first time, it's a vanilla 6/6 for GGGG.
3. **In the deck's own terms it's a vanilla 6/6.** The deck already has 11+ finisher-type bodies (see the Kalonian Hydra review). Without an enabler, it adds to the deepest category the deck has, and it carries no land text, which is the deck's tiebreaker.
4. **It doesn't touch the games the deck loses.** The audit's gaps are instant-speed interaction, artifact/enchantment answers, sweepers and graveyard hate. A body that opponents decline to damage addresses none of them.

The NO doesn't depend on price; it would still be a NO if the card were free.

## Community check

The 10.2% Aesi inclusion is the strongest point in its favour. Here is where this deck differs: those lists play Hexhaven alongside fight or self-damage effects, and this list has zero. A 0-enabler copy is a different card from the one EDHREC is counting.

## The honest ADD IF

**ADD IF the deck picks up at least 3 fight effects for its interaction slots.** That isn't a made-up condition. Fight spells are creature removal, and removal is the deck's documented gap. With Hexhaven as the fighter, each fight spell becomes removal plus a burst of lands. Candidates verified 2026-11-26:

- **Khalni Ambush // Khalni Territory** ($0.49): an instant fight on the front and a tapped Forest-mana land on the back. It can replace a land without costing a spell slot. It's worth considering on its own, Hexhaven or not.
- **Bushwhack** ($0.28): {G} sorcery that either fetches a basic land to hand or fights. It's never dead.

With 1–2 fight spells, Hexhaven still fires too rarely to beat a card already in the list. Build the fight package first and evaluate Hexhaven again after that.

## Cut, for reference only

If you add it anyway: **Zendikar's Roil** (5-mana token engine, smallest bodies, the audit's long-standing first cut), then Jin-Gitaxias, Progress Tyrant (MV 7, no land text).

## What would change this

- Three or more fight or self-damage effects in the list (see above).
- Evidence that the pod regularly blocks big creatures or plays damage sweepers like Blasphemous Act, which would trigger it on the way out.

---

## Revision (same session): the deterrent argument

The user suggested a second way to judge the card: as a **deterrent body**, meaning it's worth the slot even if the trigger never fires. That holds up, and my first pass missed it. Point 2 above treated "nobody damages it" as the card failing. For a deterrent, nobody damaging it means it's working.

On this axis:
- **Rate.** A 6/6 with vigilance for MV 4 attacks every turn and still blocks. The deck has three MV-4 spells (Arixmethes, Oracle of Mul Daya, Nissa), and the audit wanted more MV-4 plays. Script check: the only other anti-attack card is Propaganda, and the list has no vigilance creatures.
- **The trigger punishes every way of getting rid of it in combat or with damage.** Trading with it, double-blocking it or casting a damage sweeper all hand you lands equal to the damage dealt. That count can be more than 6. The trigger resolves even when the damage kills it.

There are two limits:
1. **"The worst case is losing it for 6 lands" isn't right.** The worst case is destroy, exile, bounce or sacrifice removal, which gives you nothing. The pod uses destroy-based removal (Kalonian Hydra review). Combat is actually its best case.
2. **One blocker doesn't stop a wide attack.** The audit lists go-wide combat as a pod threat. Against a wide board it stops one attacker, and Propaganda (already in) does more. It only really deters a few large attackers, such as Voltron or big stompy decks.

**Verdict: ADD IF most of the attacks you take come from a few big creatures, not wide boards.** In that case, cut **Zendikar's Roil**. Against a go-wide opponent, Roil's stream of 2/2 blockers does that job better, and the answer stays NO. The fight-package path above still applies on top of this.
