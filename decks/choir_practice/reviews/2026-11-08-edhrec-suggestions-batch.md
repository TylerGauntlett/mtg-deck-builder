# EDHREC suggestion batch (2026-11-08): eight NO, one ADD IF

Proposed by the user as a screenshot of Giada's EDHREC page. The nine cards in it: Herald of War, Youthful Valkyrie, Firemane Commando, Bruna, the Fading Light, Emeria Shepherd, The Book of Exalted Deeds, Linvala, Keeper of Silence, Angel of Jubilation and Austere Command. None of them is in the current list.

Moxfield list last updated **2026-11-07T20:42:00.927Z** (sync exit 0, 100 cards, 74 distinct). The card list is unchanged from the 2026-11-05 sync. **Tome of Legends is still in it.**
Prices: Scryfall, fetched 2026-11-08 01:00 UTC. EDHREC: Giada page, 39,365 decks. Spellbook: `combos.py` with all nine added gives 0 new combos and 1 near-combo (The Book of Exalted Deeds + Transcendence, a draw. Transcendence isn't in the deck and isn't wanted).

Session note: the Default cloud environment blocked Scryfall and Moxfield. A personal `mtg-deck-builder` environment was created that allows only the four script hosts, and every fact below was fetched live after that.

## Verdicts

| Card | EDHREC (Giada) | Price | Verdict |
|---|---|---|---|
| Herald of War | 77.3% | $1.85 | **NO.** 3rd rejection, nothing changed |
| Youthful Valkyrie | 79.0% | $0.23 | **NO.** You cut it on 2026-11-01 based on how it played |
| Firemane Commando | 57.1% | $0.68 | **ADD IF** combat aimed at you is still the problem. Cut Tome of Legends |
| Bruna, the Fading Light | 55.5% | $4.33 | **NO.** Changed fact (Angel of the Ruins gone), same verdict |
| Emeria Shepherd | 58.1% | $1.94 | **NO** |
| The Book of Exalted Deeds | 46.1% | $9.32 | **NO.** Third copy of an effect the deck already has two of |
| Linvala, Keeper of Silence | 43.5% | $21.34 | **NO.** Unchanged from 2026-10-30 |
| Angel of Jubilation | 40.7% | $10.44 | **NO.** Eighth anthem, and it turns off War Room |
| Austere Command | 43.6% | $0.80 | **NO.** The gap is real but this card is the wrong fix. Counter-propose March of Otherworldly Light |

The high EDHREC numbers come largely from the Calling All Angels precon: Herald of War, Youthful Valkyrie and Firemane are precon cards, and this list has upgraded away from them. Popularity is not a reason here, and every verdict below would be the same at any price.

## Deck model used (verified this session)

- Curve (nonland, 63): 1:6, 2:14, 3:14, **4:12**, 5:8, 6:2, 7:6, 8:1. 4-drops are still the widest slot. There are 7 cards at MV 7–8: Elesh Norn, Emeria's Call, Herald of Eternal Dawn, Kindred Judgment, Ob Nixilis, Sephara, Avacyn.
- Angel-cost reducers: Giada's Angel mana, Starnheim Aspirant, Urza's Incubator, Herald's Horn, Pearl Medallion. All five are still in the list.
- Creature recursion: **1**, Emeria, the Sky Ruin ("if you control seven or more Plains … return target creature card from your graveyard to the battlefield").
- Static anthems: 7. Angel of Invention ("Other creatures"), Elesh Norn (+2/+2 others), Lyra Dawnbringer (Angels), Patchwork Banner and Vanquisher's Banner (chosen type), Thraben Watcher (nontoken), Righteous Valkyrie (conditional +2/+2).
- Artifact answers: Generous Gift, Grasp of Fate, Farewell. That's **3**, and only Farewell is mass removal. Both Austere Command (2026-10-24) and Angel of the Ruins (2026-10-28) have left since the 2026-10-02 counts.

## Per card

### Herald of War: NO
"Angel spells and Human spells you cast cost {1} less to cast for each +1/+1 counter on this creature." The 2026-10-02 and 2026-10-28 rejections still stand word for word: it's a 5-mana reducer arriving after the five reducers above, in the deck's deepest support category. Nothing about the list has changed in its favour.

### Youthful Valkyrie: NO
On 2026-11-01 you cut it for Luminarch Ascension because it rarely triggered in your games and each trigger grows one creature. That was play evidence, and the screenshot doesn't add any new evidence. It's the same card at the same rate.

### Firemane Commando: ADD IF combat aimed at you is still the problem; cut Tome of Legends
Verified: "Whenever you attack with two or more creatures, draw a card. Whenever another player attacks with two or more creatures, they draw a card if none of those creatures attacked you."

**What changed.** The 2026-10-30 ADD IF was "if it replaces Seraph of the Sword." You've since cut Seraph for Authority of the Consuls, and that addendum warned that big non-trampling ground attackers reaching you was the risk to watch. That makes the case for a combat deflector stronger. The case for Seraph specifically is gone.

**For it** (three verified pieces): Ghostly Prison, Archangel of Tithes and Magus of the Moat already tax or stop attacks. Firemane adds a reward for attacking someone else. It's also an Angel, so all five reducers and Giada's counters apply.

**Against it**, unchanged from earlier reviews: while Magus of the Moat is out the reward rarely fires, it hands the table cards, its own draw clause overlaps Minas Tirith ("Activate only if you attacked with two or more creatures this turn"), and myriad tokens aren't declared attackers.

**The cut is Tome of Legends** ("Whenever your commander enters or attacks, put a page counter … {1}, {T}, Remove a page counter: Draw a card"). Both are attack-conditioned draw. Tome needs Giada, a 2/2, to attack, while Firemane needs any two creatures. Firemane is also an Angel and a 4/3 flier. On the deck's own terms Firemane is the better draw card, before you count the politics.

**Conflict to resolve:** Tome is also the named cut for Starnheim Unleashed (ADD IF, 2026-11-04). Only one card can take it. If you're losing to attacks, take Firemane. If you're losing to being out-rebuilt after wipes, take Starnheim. If neither is true, keep Tome.

### Bruna, the Fading Light: NO
**Changed fact:** the 2026-10-02 review weighed Bruna against Angel of the Ruins, and called it "close". Ruins has since left for Herald of the Host, so Bruna is no longer a like-for-like swap. It's now an extra 7-drop that needs its own cut. That makes it a harder fit, not an easier one: 7–8 drops would go from 7 to 8.

What's still true: recursion is thin (1 card), and the cast trigger ("return target Angel or Human creature card from your graveyard to the battlefield") is a real 2-for-1. The revisit condition set on 2026-10-02 was evidence of Angels piling up in the graveyard in long games, and you haven't reported that. **What would change this:** that evidence, plus a 7-drop you'd cut for it. Ob Nixilis or Emeria's Call would be the ones I'd look at first.

### Emeria Shepherd: NO
A 7-mana 4/4 whose recursion needs a land drop after it resolves. It's the weaker of the two 7-drop recursion bodies: Bruna's return happens on cast, so it survives a removal spell, and Bruna is a 5/7 vigilant flier. If you ever add 7-drop recursion, add Bruna, not this.

### The Book of Exalted Deeds: NO
"At the beginning of your end step, if you gained 3 or more life this turn, create a 3/3 white Angel creature token with flying." The list already has two cards that do this. Resplendent Angel ("if you gained 5 or more life this turn, create a 4/4 … flying and vigilance") and Valkyrie Harbinger ("4 or more life … 4/4"), and both are Angels themselves with bigger tokens. The Book is a non-Angel artifact at {W}{W}{W}, so no Angel reducer touches it, and its token is smaller. The 2026-10-02 rejection stands. Its second ability ("can't lose the game") hangs on one removable Angel and doesn't advance any plan the deck has.

### Linvala, Keeper of Silence: NO
Same as 2026-10-30. It only does anything against creature activated abilities in a pod that rotates 10+ unknown decks, and it would be another 4-drop in the widest slot. You haven't told me the pod's creature-combo or mana-dork density, which is the condition that would reopen it.

### Angel of Jubilation: NO
- "Other nonblack creatures you control get +1/+1." That's the 8th static anthem. Elesh Norn and Angel of Invention already cover "other creatures", and Lyra Dawnbringer covers Angels. Additive, in a deep category.
- "Players can't pay life or sacrifice creatures to cast spells or activate abilities." It's symmetric, and it **turns off your own War Room** ("Pay life equal to the number of colors in your commanders' color identity": 1 life in mono-W). Against opponents it only does something if they run sacrifice outlets, which is the same pod-dependence that rejected Linvala.
- {1}{W}{W}{W} at 4 MV, in the widest slot.

### Austere Command: NO. Counter-propose March of Otherworldly Light
**The role is real.** With Austere and Angel of the Ruins both gone, the deck has 3 artifact answers, and only Farewell is a sweeper.

**The card is wrong for this list.** The artifact and enchantment modes are symmetric, and this deck has 10 artifacts (Sol Ring, Arcane Signet, Pearl Medallion, Urza's Incubator, Herald's Horn, both Banners, both boots, Tome). It also has key enchantments: Cathars' Crusade, Ghostly Prison, Court of Grace, Luminarch Ascension, Authority of the Consuls, and Grasp of Fate, which hands back whatever it exiled when it dies. Kindred Judgment already replaced its creature modes. Re-adding it reverses a 2026-10-24 verdict with no new evidence.

**Counter-proposal (not a recommendation to add yet):** if a resolved artifact (an equipment, a rock engine, a combo piece) has actually beaten you, a cheap instant answer fits the gap better. March of Otherworldly Light: "{X}{W} Instant … Exile target artifact, creature, or enchantment with mana value X or less." It also hits creatures, so it's never dead. $1.06. Tell me if artifacts have been the problem and I'll run it through the full rubric against a named cut.

## Aggregate
Of nine cards, one has a conditional case, and its one cut (Tome of Legends) is already claimed by another conditional add. No second genuinely cuttable card exists for this batch. That's the finding: **at most one of these can go in, and only Firemane has a case.**

## Questions that would move verdicts
1. Since cutting Seraph of the Sword, are opponents still attacking you more than each other? (Firemane)
2. Has a resolved artifact beaten you recently? (March / Austere's role)
3. Are Angels piling up in your graveyard in long games? (Bruna)
