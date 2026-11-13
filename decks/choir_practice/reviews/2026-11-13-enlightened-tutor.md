# Enlightened Tutor (2026-11-13): NO

Moxfield list last updated **2026-11-07T20:42:00.927Z** (sync exit 0, 100 cards, 74 distinct). Unchanged since the 2026-11-08 batch review.
Price: Scryfall, fetched 2026-11-13 18:20 UTC. EDHREC: card page. Spellbook: `combos.py --add "Enlightened Tutor" --near`.

## Verdict

**NO.** It would spend the deck's last Game Changer slot, plus a card, to find one more copy of an engine in a deck that has no single card it must find.

## The card (verified)

**Enlightened Tutor** {W}, Instant. "Search your library for an artifact or enchantment card, reveal it, then shuffle and put that card on top." Legal, colour identity W. **Game Changer: yes.** EDHREC rank 125. Ruling (2016-06-08): the shuffle and putting the card on top are a single action.

Price: **$37.10** (foil $39.20). That's under the $40 cap, but close to it. Price plays no part in the verdict below.

## Hard vetoes

- **Colour identity and legality:** pass.
- **Game Changers:** the current list has 2 (Drannith Magistrate and Farewell, per the `cards.md` summary). Enlightened Tutor would be the **3rd of 3**. That's allowed, but it uses up the last slot. See below.
- **No win line that depends on tutoring:** pass. `combos.py` shows a baseline of 0 combos. Adding the tutor completes 0 and brings 0 within reach, so there's nothing to assemble.
- **Budget:** $37.10 is under the per-card cap. I haven't recalculated how much of the ~$300 total is left. Check that before buying anything near the cap.

## Steel-man

The deck has **18 artifact or enchantment cards** it could find (`cards.json`, non-creature):

- **Engines and multipliers:** Cathars' Crusade, Court of Grace, Luminarch Ascension, Urza's Incubator, Herald's Horn, Vanquisher's Banner, Patchwork Banner
- **Mana:** Sol Ring, Arcane Signet, Pearl Medallion, Land Tax
- **Defence:** Ghostly Prison, Authority of the Consuls, Grasp of Fate
- **Protection and other:** Lightning Greaves, Swiftfoot Boots, Tome of Legends, Folk Hero

It costs 1 mana and it's an instant. You can cast it at the end of the previous player's turn and draw the card in your own draw step. It adapts to the game: Ghostly Prison when the pod's ground attacks are coming at you (the reported loss mode), Cathars' Crusade or Court of Grace when you're building a board, and Land Tax on turns 1–2. On a good day it's a second copy of Cathars' Crusade (the strongest multiplier here) for {W}.

## Attack

1. **It costs a card.** "Put that card on top" means it replaces your next draw rather than adding to it. You pay a card and {W} to choose that draw. Tutors pay for this in decks where one card is worth far more than the others: a combo piece, a lock, the only engine. Spellbook confirms this deck has **0 combos**. The 2026-10-02 ceiling review rejected this card for the same reason: the deck wins through redundancy, not one piece. Nothing in the list has changed that.
2. **Where it gets value, the deck already has backups.** Cathars' Crusade is the best thing it can find. The list also has other ways to grow the board, among them Archangel of Thune, Norn's Choirmaster and Giada herself. Those were verified in earlier reviews. I didn't re-quote them this session, so read this as supporting context, not a counted claim. The cost reducers it could find (Urza's Incubator, Herald's Horn, Pearl Medallion) are 3 of the 5 the 2026-11-08 review counted. That's the deck's deepest support category, as that review notes. A tutor adds most to a category that's thin, and the categories it can reach here are not thin.
3. **It closes off Game Changer #3.** Teferi's Protection has been the reserved ADD IF for that slot since 2026-10-02. It was restated on 10-14, 10-29 and 11-02 as the answer if wipes or alpha strikes start costing games. Enlightened Tutor would fill the slot with a card that shores up no weakness the table has shown. It only smooths draws.
4. **What can't be ruled out:** it's a strong card in the abstract, and 19.4% of Giada decks run it (7,691 of 39,601). Most of that comes from higher-power Giada lists. Popularity doesn't say the card beats anything in *this* 99.

**Would the NO hold if the card were free?** Yes. Reasons 1–3 have nothing to do with price.

## Cut (for reference only, not recommended)

If you add it anyway, the weakest card is still **Tome of Legends**. Tome is already the named cut for two other conditional adds (Firemane Commando on 11-08, Starnheim Unleashed on 11-04), so it can't take a third claim. After Tome, every possible cut is a card earlier reviews defended for a specific reason. That supports the NO.

## What would change this

- **You decide Game Changer #3 will never go to Teferi's Protection**, *and* you report games lost because the deck didn't find Cathars' Crusade or Court of Grace (stalled, low-impact boards rather than wipes or combat). In that case the slot is free and it's spent on what actually goes wrong. Then reopen this with a named cut.
- A combo or lock piece entering the list that the deck really needs to find. Even then, the house rule bans win lines that depend on tutors.

## Bracket and totals

| | Before | After (if added) |
|---|---|---|
| Game Changers | 2 | 3 of 3 |
| Combos | 0 | 0 |
