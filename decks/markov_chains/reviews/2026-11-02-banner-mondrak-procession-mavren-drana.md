# markov_chains — five-card batch (2026-11-02)

Vanquisher's Banner · Mondrak, Glory Dominus · Anointed Procession · Mavren Fein,
Dusk Apostle · Drana and Linvala

List synced from Moxfield (deck updated 2026-10-31T03:20:30Z): 100 cards, 34 lands,
average non-land MV 2.92, curve 1:10 · 2:16 · 3:20 · 4:12 · 5:5 · 6:3. Bracket 3,
Game Changers 2/3 (Necropotence, Teferi's Protection), $40/card cap.

## Verdicts

| Card | Price (Scryfall, 2026-11-02 04:36 UTC) | Edgar decks (EDHREC) | Verdict |
|---|---|---|---|
| **Anointed Procession** | $59.23 — **over cap** | 26.7% (13,990 / 52,441) | **ADD IF** you waive the $40 cap for it. Cut **Henrika Domnathi** |
| Mondrak, Glory Dominus | $43.12 — **over cap** | not in its top-24 commanders | **NO** — the worse of the two doublers, and the deck has room for one |
| Mavren Fein, Dusk Apostle | $0.34 | 42.9% (22,497 / 52,441) | **NO** — good card, no cut for it in the 3-slot |
| Drana and Linvala | $6.20 | 22.9% (11,990 / 52,441) | **NO** — the 09-06 ADD IF no longer has a testable condition, and there's no cut |
| Vanquisher's Banner | $4.24 | EDHREC fetch failed (twice) | **NO** — unchanged from 2026-09-03 |

**The batch finding.** Five adds need five cuts. There aren't five. The 10-30 Idol
review already found the bottom of the list was all spared cards: Forerunner of the
Legion (you kept it as the only tutor), Henrika Domnathi, and the free sac outlet
that makes Grave Pact work (Bloodthrone then, Bartolomé del Presidio now). There's
room for one add at most, and the doubler is the one that earns it.

Commander Spellbook: **0 new combos** for all five. Procession and Mondrak each show
one *near* combo, with Tooth and Claw (not in the deck). No bracket issue.

---

## 1. Anointed Procession — ADD IF the cap is waived

> `{3}{W}` Enchantment — *If an effect would create one or more tokens under your
> control, it creates twice that many of those tokens instead.*

This was an ADD on merits on 2026-09-03. It was dropped only because of the $40 cap
(shape review, 10-02). I re-checked it against today's list rather than carrying
the old reasoning forward.

**Token sources it doubles (verified in today's `cards.json`): 10.**
Edgar Markov's eminence (*"whenever you cast another Vampire spell … create a 1/1"*,
works from the command zone, 36 Vampire cards), Edgar, Charmed Groom's Coffin
(upkeep), Bloodline Keeper (`{T}`), Elenda (on death), Clavileño (granted death
trigger), Charismatic Conqueror, Bastion of Remembrance, Black Market Connections
(Treasure and Mercenary), Idol of Oblivion's 10/10, and Baron Bertram Graywater.

*Correction to 09-03.* That review said Baron is "batched, not doubled". That was
wrong. Baron's *trigger* fires once a turn, but the token it makes is still
doubled: one trigger, two 1/1 lifelinkers.

**Payoffs that count each token:**
- **Impact Tremors** — *"Whenever a creature you control enters"*, 1 damage each.
- **Mirkwood Bats** — *"Whenever you create or sacrifice a token"*. It counts each
  token twice, once on creation and once on sacrifice.
- **Edgar's attack** — a counter on *each* Vampire.
- Every death payoff (Blood Artist, Cruel Celebrant, Bastion, Vein Ripper) gets
  twice the fodder.

**What it doesn't double:** Welcoming Vampire (*"one or more … triggers only once
each turn"*). Idol of Oblivion's draw (only needs one token).

**It serves both modes.** In the go-wide mode, more bodies attack. In the drain
mode, more fodder and more Bats triggers. That's the strongest kind of add.

**Weaknesses.** It does nothing the turn it lands, it's a blank after a wipe, and
exile-everything wipes take it too. The 09-03 ADD relied on the user's statement
that games here run long. Later reviews (10-31) still say that. If that has
changed, this verdict is the one that moves.

**Price, on its own line:** $59.23, $19.23 over the cap. This is the only thing
standing between it and a plain ADD.

### The cut: Henrika Domnathi

`{2}{B}{B}`. At the beginning of combat on your turn, she does one unused mode:
each player sacrifices a creature, you draw and lose 1 life, or she transforms
into a 3/4 deathtouch lifelink flier.

**Why I spared her before, and why that doesn't hold here.** On 10-30 the reason
was that she does *"three different jobs, none of them a copy of something already
in the deck."* That ruled out cutting her for a card that copies something.
Procession doesn't copy anything either. The deck has no token doubler. So this is
two unique cards head to head. Procession multiplies ten sources every turn for
the rest of the game. Henrika does three one-shot things across three turns. Her
edict job stays covered by Grave Pact, Anowon and Soul Shatter.

- Same MV (4 → 4). Pips: B −2, W +1.
- Eminence fuel drops 36 → 35 Vampire cards. That's a real cost, and smaller than
  doubling every one of the other 35.

**Runner-up: Forerunner of the Legion.** It's the better cut on card quality. You
kept it as the only tutor on 10-30, so I'm not reversing that for you.

**Spared:** Anowon. Cutting it was my first instinct, as on 09-03. But since then
the Recollector review (10-09) leaned on it as a "one card → 3+ deaths" enabler.
That reason still holds.

---

## 2. Mondrak, Glory Dominus — NO

> `{2}{W}{W}` Legendary Creature — Phyrexian Horror 4/4 — *If one or more tokens
> would be created under your control, twice that many of those tokens are created
> instead.* `{1}{W/P}{W/P}`, *Sacrifice two other artifacts and/or creatures: Put
> an indestructible counter on Mondrak.*

**Best case.** It's the same doubler as Procession, plus a 4/4 body and a sac
outlet that triggers the death payoffs.

**Why it loses to Procession. Each reason is about the card, not the price:**
1. **Your own Olivia's Wrath kills it.** *"Each non-Vampire creature gets -X/-X"*.
   X is your Vampire count, which is usually 4+. An indestructible counter doesn't
   stop -X/-X. Procession doesn't care.
2. **It's a non-Vampire creature.** So it's what Anowon makes *you* sacrifice when
   Carrion Feeder and Mirkwood Bats aren't out. It also doesn't trigger eminence.
3. **`{W}{W}`.** The deck's only other WW card is Clever Concealment. There are 16
   white sources. The 09-06 math put WW by turn 4 at about half the time.
4. **It's a creature**, so it dies to spot removal and creature wipes, and those are
   the most common answers.

The deck wants one doubler. A second would need a second cut, and there isn't one.
If you'd rather run Mondrak than Procession, the cost is the four points above. It's
a worse card, not an unplayable one.

**Price, on its own line:** $43.12, also over the cap. The NO still holds if it
were free, because Procession does the job better.

---

## 3. Mavren Fein, Dusk Apostle — NO

> `{2}{W}` Vampire Cleric 2/2 — *Whenever one or more nontoken Vampires you control
> attack, create a 1/1 white Vampire creature token with lifelink.*

**Best case.** It's on the Edgar page at 42.9% and makes one lifelinking token each
combat. The lifelink feeds Vito and Blight-Priest. It's a Vampire, so it triggers
eminence. It's cheap.

**Why it doesn't get in:**
- **One token per turn, and only when you attack.** It needs a *nontoken* Vampire
  to attack. Edgar, Charmed Groom already makes a lifelink 1/1 every upkeep with
  no condition. The shape review (10-02) set generators at "hold".
- **3 MV is the most crowded slot**, 20 cards.
- **No cut.** Its natural replacement is Forerunner, which you're keeping. The next
  3-drops are interaction (Oubliette, Soul Shatter, Anguished Unmaking), engines
  (Necropotence, BMC, Welcoming Vampire) or loop pieces (Vito, Blight-Priest).
  None of them is weaker.

**What would change it:** letting Forerunner go. Mavren beats Forerunner, but so
does Procession, and Procession is the better use of that slot.

---

## 4. Drana and Linvala — NO (was ADD IF on 2026-09-06)

> `{1}{W}{W}{B}` Vampire Angel 3/4, flying, vigilance — *Activated abilities of
> creatures your opponents control can't be activated. Drana and Linvala has all
> activated abilities of all creatures your opponents control.*

The 09-06 condition was "if one of the opponents' decks genuinely uses creature
activated abilities". That was written against a recorded three-deck pod.
`meta.json` now says the same three players rotate through 10+ decks, and cards are
judged on general usefulness. Under that framing, the condition becomes "some games
yes, some no". So the card's value is a 3/4 flying vigilance Vampire that sometimes
shuts off an opponent's creature abilities.

That's a fine card, but it's not enough. The 4-slot's 12 cards each carry an
engine. Like Mondrak, it's `{W}{W}`. And the cut that 09-06 named for it
(Forerunner) is no longer available.

**Price, on its own line:** $6.20. Not a factor.

---

## 5. Vanquisher's Banner — NO (unchanged from 2026-09-03)

> `{5}` Artifact — choose a creature type; *those creatures get +1/+1. Whenever you
> cast a creature spell of the chosen type, draw a card.*

**Best case.** Name Vampire and every later Vampire cast draws a card. In long games
that's a real engine.

**Why not:**
- The anthem half is another pump in the deck's deepest category. It's the same case
  as Door of Destinies (08-31) and Heraldic Banner (10-28). None of the drain
  payoffs read power.
- The draw half joins a draw category that has grown since 09-03: Necropotence,
  Black Market Connections, Skullclamp, Welcoming Vampire, High-Society Hunter,
  Bloodline Recollector, Vampire Gourmand, Idol of Oblivion, Baron, Clavileño and
  Henrika.
- 5 MV, and it draws nothing the turn it lands.
- No cut.

**Price, on its own line:** $4.24. Not a factor.

---

## Open questions

1. **Will you go over the $40 cap for Procession?** That's the only open decision
   in this batch.
2. **Do games still run long?** Procession's ADD partly depends on it. If games now
   end around turn 7–8, it drops to a weaker ADD IF, and the cut question gets
   harder.

## Figures recorded

| Item | Value | Source / time |
|---|---|---|
| Moxfield last updated | 2026-10-31T03:20:30Z | `build_card_details.py` |
| Prices | Procession $59.23 · Mondrak $43.12 · Drana and Linvala $6.20 · Vanquisher's Banner $4.24 · Mavren Fein $0.34 · Anowon $2.45 | Scryfall, 2026-11-02 04:36–04:39 UTC |
| Edgar inclusion | Procession 26.7% · Mavren 42.9% · Drana and Linvala 22.9% (n = 52,441) | EDHREC card pages |
| Mondrak | not in its top-24 commanders | EDHREC |
| Vanquisher's Banner | EDHREC request failed twice | — |
| Combos | 0 new for all five; Tooth and Claw near-combo for both doublers | Commander Spellbook |
| Token sources | 10 (all doubled; Welcoming Vampire's draw batched) | `cards.json` |
| Non-Vampire creatures | Carrion Feeder, Mirkwood Bats | `cards.json` |
| WW cards in deck | Clever Concealment | `cards.json` |
