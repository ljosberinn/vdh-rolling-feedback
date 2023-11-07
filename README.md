# Vengeance Demon Hunter - Rolling Feedback

## Tier 1

Tier 1 feedback items are critical/major discussion points.

- Soul Cleave is capped at 5 targets. This means that we cannot hit every target on a >= 6 target pull and has implications for defensive use (Frailty) and aggro; it ultimately mandates that we take `Spirit Bomb`.
  - Requested solution: remove the hard cap at 5 targets. It can be reduced damage after 5 targets if need be.
- Talents like `Fiery Demise`/`Burning Blood` nudge you towards holding `Fel Devastation` until `Fiery Brand` has spread enough or `Frailty` was stacked, which is counterintuitive because you can't do that in challenging content.
- Whenever we have to kite or cannot spend for a longer time we're suspectible to synced autohits nearly or entirely oneshotting us when going back in because our debuffs fall off. `Frailty` is too short-lived and takes too long to build again if you go back, you'd need e.g. `Fel Devastation` again, to be able to be tanky enough to build resources.
  - Requested solution: split `Frailty` into two parts - damage reduction buff that goes on the player with `Void Reaver` and damage multiplier debuff with `Vulnerability`. Each `Frailty` applying event would apply 1 stack of the `Frailty` buff to the player and 1 stack of the `Frailty` debuff to the target (e.g., `Soul Cleave` hits 5 targets and applies 1 stack to the player and 1 stack to each target hit). Some mechanism for maintaining the `Frailty` buff on the player without having to be in melee range would also be appreciated (such as no/delayed decay while out of combat).
  - Alternative solution: An ability similar to Unholy DK's `Unholy Blight` that applies `Frailty` to nearby targets every tick instead of Virulent Plague. This would resolve a few DR issues with starting into a new pack or re-entering an existing pack after kiting.
- This leads to also the requirement of having to pool resources at the end of a previous pull to not just fall over at the start of the next pull, something no other tank has to do except Blood DK, but they have quite a couple more tools available for smoothing incoming damage and can guarantee having `Bone Shield` at the start of the pull, while we cannot guarantee having `Demon Spikes` because we cannot have 100% `Demon Spikes` uptime.
- We'd propose making at the very least `Fiery Brand` a buff on the player, allowing us to prebrand ourselves before a dangerous pull. I can also see moving `Frailty` towards more of something like `Bone Shield` is; a long lived stacking buff on the player granting you more benefits at higher stacks.
  - This would have implications with things like `Fiery Demise`. We propose the same thing here that we proposed with `Frailty`: split `Fiery Brand` into a buff and a debuff.
  - We can also see a world where a set of talents exist that turn `Fiery Brand` into a selfcast buff with reduced CD and DR - maybe 30s CD and 20% DR - while the default behavior remains the same.
- Which is another issue; all other tanks can maintain 100% mitigation. We still cannot, even with `Feed the Demon` and `Extended Spikes`.
- We are extremely dependant on `Demonic` because of that. Without `Demonic`, the spec is close to unplayable in highkeys/challenging content
- Half of our spec tree is dead to the degree of never even remotely thinking about picking it. the two far right columns see zero play. in particular, these are especially problematic in their current form:
  - `Fel Flame Fortification` is one of the worst shadowlands legendaries, providing not only unreliable but also little mitigation (frequently providing <1% mitigation across an entire M+ dungeon).
  - `Sigil of Chains`, a signature spell, gated behind not only 2 talents of very little value, but also in a direction where you currently do not want to invest any further, making it too expensive.
  - `Bulk Extraction`, a talent that never saw any tuning and was copied over from the old talents, where it already had 0 play. not only does it do insignificant damage, its cooldown is also obscene. heavily suggest removing it entirely.
  - `Soul Barrier`, another talent just copied over. We've proposed multiple times to return to the (deleted) Legion version which basically worked like the aegis trinket from SoD. Currently, the shield is simply too small to warrant ever using souls for it when you could just `Spirit Bomb` instead. Bringing back the `Hour of Reaping` azerite trait would be a great replacement here.
  - `Revel in Pain` does not work with `Burning Alive`. the shield is also rather tiny without `Fiery Demise` buffing it, but at least those talents are close together. This talent currently sees some amount of play but will likely not be played again once the T30 set is no longer relevant.
  - `Chains of Anger`: 2 yards is .. not much. don't see how this talent is possibly salveagable, I see no scenario in which you want more radius unless its gating something you actually want (please don't)
  - `Cycle of Binding`: is not applying per target. Would be too strong currently if it did, but could be useful if cdr is applied per target hit, e.g. 0.5s
  - There's no non-pvp reason to ever pick `Meteoric Strikes` but its gating the entire right side despite there being no interaction to any connected ability. We'd suggest making it a PvP talent
  - `Retaliation` is undertuned. even a 300% buff would not make it interesting enough, as it counteracts design wise with `Demon Spikes` in general. I'd suggest tying it to the reverse scenario: parrying (possibly regardless of `Demon Spikes` being up? or both in `Demon Spikes` and `Metamorphosis` being up) cause the attacker to take physical damage. the threat modifier is irrelevant, both now and in the future, we don't have threat issues and you need to have threat for this talent to take effect anyways.
  - `Ruinous Bulwark` is counteracting `Demonic`. I understand it's probably also there because `Demonic` is not baseline and Bulwark is better without `Demonic`, but everybody plays `Demonic`.
  - `Roaring Fire` is the same as `Ruinous Bulwark`. suggesting to either just remove `Roaring Fire` or to merge them. unless `Demonic` changes, these will never be picked outside of raid encounters where you don't need silence and rather have a talent with minimal impact than a talent with zero impact.
  - `Soulmonger` has and is counteracting all other sources of heal we have. It does nothing when you're struggling to survive and when you don't, you don't need 10% additional hp anyways.
    - Requested solution: revert `Soulmonger` to the azerite trait version, shielding per soul fragment consumed. remove the overheal requirement
- A lot of talents from the class/spec tree in general feel like "filler talents". For example, we need to spend five points to get the entire value of `Frailty` while the "main frailty generator" (`Soul Cleave`) is target capped at 5. That feels extremely unsatisfying.
- An 8 minutes cooldown on `Last Resort` with 0 cooldown reduction tied to it feels anachronistic.
  - `Battle-Scarred Veteran` is 3 minutes, no cdr, but not a full cheat
  - `Ardent Defender` has 2 minutes cooldown but is not passive, and can be further empowered + has cooldown reduction
  - `Gift of the Golden Valk'yr` is a secondary cheat similar to BSV but has only 45s cd, while also adding cooldown reduction to `Guardian of Ancient Kings`
  - `Divine Shield` is a literal immunity on top
  - monk has `Stagger` permanently
  - `Purgatory` is an actual cheat with 4 minutes and no cdr
  - Requested solution: add some form of cooldown reduction to `Last Resort`, e.g. based on souls or fury consumed -- or simply lower the cooldown

## Tier 2

Tier 2 feedback items are significant but not make-or-break.

- Most of our talents seem to be taken from the artifact weapon and recent Shadowlands content, with a couple of azerite traits sprinkled on top (despite azerite traits getting mostly changed).
  - many other specs have multiple of their shadowlands legendaries as option. we have:
    - `Fel Flame Fortification` -- was not played at all
    - `Darkglare Boon`, modified and made more reliable (this is good and we like this)
    - `Collective Anguish` in the class tree, which was only rarely played as tank but is a welcome addition
  - many other specs have set bonuses available. we have:
    - a better T21 2pc as `Deflecting Spikes`
  - We'd suggest looking at the T21 4pc (parrying reduces Meta cd) in particular, since we currently have 0 cdr for a 3 minute cooldown, as well as the `Fiery Soul` and `Razelikh's Defilement` legendaries, both historically popular
  - Something like the T28 tier set reducing the CD on Fel Dev would also be great as once T30 goes away, we will likely be back to having Fel Dev as our only reliable way to have large amounts of survivability in pulls.
- The feedback cycle for Fury is currently near nonexistant. yes, gives you more `Frailty` stacks but the actual impact is near zero. if you check resource waste for top logged keys youll see anything between 10% and 40% -- some of that is attributable to `Volatile Flameblood` proccing at "unwanted" times, but it doesnt vary this much. You can waste as much as 40% Fury actively and still live just fine, which is extremely counterintuitive.
- Even when you try to waste a minimum of Fury (which is hard to get below ~8% depending on key level/affixes/pull size), you usually end up in a cycle of building Soul Fragments, spending with `Spirit Bomb` (in aoe) and then cleaving away remaining Fury with `Soul Cleave` -- a rotation that feels good. However, due to `Soul Cleave` being target capped and doing, generally speaking, not much damage, in many pulls this may already put you in a situation where you can drop dangerously low because it takes quite a lot of globals to build the next `Spirit Bomb` if its a ST situation or `Immolation Aura` (`Fallout`) is not available.
- `Metamorphosis` could be more impactful in regards to the actual gameplay. Currently it only increases the amount of souls and fury we get from `Fracture`. It would be great if some spells could get empowered like the Havoc version of `Metamorphosis` does. Empowering `Fracture` to hit several targets, making `Soul Cleave` deal fire damage or enhancing `Spirit Bomb` in a certain way
- `Fiery Brand` spread without T30 4pc will always suffer from a lack of brands, as `Down in Flames` is categorically worse than the Shadowlands legendary `Fiery Soul` which roughly achieves the same as current T30.
- The Class tree has several severe issues for Vengeance in particular.
  - We have to spend 2 points for `Erratic Felheart` (probably) because `Fel Rush` is good for Havoc even though VDHs dont even pick `Meteoric Strikes` (which has way more value/talent point spent). But we need `Erratic Felheart` due to `Colletive Anguish`´s passive damage and healing increase which is too big to miss out on.
  - `Demon Muzzle`'s value is really low and at best used in niche situations. `Demon Muzzle` was a conduit from SL that already never got picked.
  - `Darkness` has a way too long cooldown and is just not reliable/doesn't actually replace the usage of defensives because of the randomness (people pair it with `Spirit Link Totem` in Raid)
  - Left and Right "triangles" provide little to no value at all.
  - As mentioned above we are extremely dependant on `Demonic`. There is no actual choice betweem `First of the Illidari` and `Demonic`
  - In general the amount of 2 point nodes the class tree contains is massive.
- `Feast of Souls` never really got picked since BfA. The healing it provides doesnt scale well into more difficult types of content and sadly it doesnt stack several applications.
  - Requested solution: allow stacks and have healing scale with max health so it's not suddenly useless in `Metamorphosis` windows and continuously scales through power levels
- The spell queue changes in dungeons have made `Sigil of Silence` feel significantly worse to use; it was previously very useful for stopping an entire pack from casting their abilities and now it's very inconsistent in whether or not it works the way you'd intend it to be used.

## Tier 3

Tier 3 feedback items are minor or quality-of-life.

- Souls should spawn based on haste rating. above 25%ish haste, you press `Fracture` at 3 souls and the gcd is ready while the second soul is still spawning so you have to hold `Spirit Bomb` briefly before you can use it. Alternative solution suggestion is to make Soul Fragments function like a normal combo Point system from Rogues or Feral.
  - Requested solution: reduce delay to spawn soul fragments based on Haste rating
- `Fiery Brand` should not be able to spread to pets (e.g. `Fodder to the Flame` demons).
- `Fiery Brand` spread at 2 seconds and on a random target is another layer of unreliability because you dont know whether it´ll spread to the 2nd tankbuster mob you currently have in your pull or not.
- `Fiery Brand` should prioritize spreading to elite mobs.
- `Throw Glaive` does very little damage - this is mostly good as we don't particularly want to have `Throw Glaive` as a regular part of the rotation. It does result in `Throw Glaive` generating very little threat even with its massive threat modifiers.
  - One possible solution would be a talent that makes `Throw Glaive` do magic damage from a random school on every cast. This wouldn't incentivize fitting `Throw Glaive` into `Fiery Demise` windows and would result in `Throw Glaive` doing roughly 30% more damage, which would be a nice threat generation gain.
- `Flame Crash` is missed, especially with the upcoming T31 tier set. If this came with the removal of some talents reducing the cooldown of Infernal Strike, due to balancing issues, that would be understandable.
- `Soul Fragment` healing isn't increased by taking environmental damage, which makes fights where damage isn't appropriately sourced not much fun.
- Feeling forced into taking `Precise Sigils`/`Concentrated Sigils` due to the extra duration on Sigil of Flame increasing T31 procs does not feel good due to the massive loss of control this creates.

## Known Bugs

- Having `Precise Sigils` or `Concentrated Sigils` talented in Havoc can cause your Sigils in Vengeance to not work with a "Unknown Spell" or "Spell Not Learned" error.
- `Charred Flesh` only extends `Fiery Brand` for the first 9 seconds after casting `Fiery Brand`, this includes any other `Fiery Brand`s spread from `Burning Alive`. This is behaving like spell data but deviates from talent text.
- `Soulmonger` absorb is affected by Versatility (double-dips): https://github.com/SimCMinMax/WoW-BugTracker/issues/1084
- `Soul Furnace` tooltip is incorrect while building stacks - says it grants next `Soul Cleave` 40% increased damage, but not Spirit Bomb.
- `Immolation Aura` can’t be removed with /cancelaura or by right clicking due to `Ragefire` in the Havoc spec tree.
- `Fel Devastation` tooltip says 20 yard range but is actually 13 yards.
- `Soul Cleave` does not benefit from its own stack of `Frailty` applied through `Void Reaver` (is applied ~2 server ticks late).
- Soul Fragments spawned by `Fodder to the Flame` do not provide a stack of `Fires of Fel` from the T30 tier set.

## 10.2

- Burning Alive being uncapped feels _amazing_.
- Charred Flesh being uncapped feels _amazing_.
- Fel Flame Fortification gating Chains of Anger feels bad. It’s a talent that we would not take on its own merits and are only taking due to pathing requiring us to take it. Swapping Ascending Flame and Fel Flame Fortification would be a sensible change.
- Perfectly Balanced Glaive gating Spirit Bomb feels bad as we're not taking Perfectly Balanced Glaive on its own merits. If Spirit Bomb wasn't next to it, we'd never take the node.

### Bugs

Note that this is not a comprehensive list of all Vengeance Demon Hunter bugs, just ones introduced on the 10.2 PTR.

**THERE ARE NONE**

### Fixed Bugs

- ~~As of 10.2.0.51851, Ascending Flame causes the parry tooltip on Sigil of Flame from Illuminated Sigils to stack; the effect does not actually stack.~~
- ~~As of 10.2.0.51851, Ascending Flame causes the damage multiplier for overlapped Sigil of Flames to be incorrect, resulting in a large multiplier on the 2nd stack, 3rd stack is fine.~~
- ~~As of 10.2.0.51851, Ascending Flame causes all Sigil of Flame events to be attributed to the first VDH with Ascending Flame talented to have a currently active Sigil of Flame DoT on the target.~~
- ~~As of 10.2.0.51851, procs from the 4pc will all go onto the player's currently selected target in AoE.~~
- ~~As of 10.2.0.51790, Ascending Flame causes applying Sigil of Flame to refresh all existing Sigil of Flame DoTs on the target to full duration.~~
- ~~As of 10.2.0.51685, when 2 VDH have Sigil of Flame on the same target, only the VDH who applied the first Sigil of Flame DoT receives stacks from the T31 2pc AND will receive all stacks from both players for the duration~~
-~~ As of 10.2.0.51685, the T31 4pc does not provide CDR on Sigil of Flame when spending Fury~~
- ~~As of 10.2.0.51685, Ascending Flame causes the second charge of Sigil of Flame from Illuminated Sigils to not apply Frailty until ~9s after your previous SoF cast; this behaves like an ICD rather than a delayed application~~
- ~~As of 10.2.0.51685, Ascending Flame causes Sigil of Flame DoTs extended by Charred Flesh to drop off the target when the original duration would have expired~~
- ~~As of 10.2.0.51521, Immolation Aura is 30s for VDH and does not benefit from our Immo Aura CDR or haste~~
- ~~As of 10.2.0.51521, Illuminated Sigils' second charge goes away if talented into Precise Sigils or Concentrated Sigils~~
- ~~As of 10.2.0.51521, Illuminated Sigils is giving 20% parry per target hit with Sigil of Flame as opposed to 20% additional parry against targets affected by Sigil of Flame~~
- ~~As of 10.2.0.51521, Felblade costs 0 talent points~~
- ~~As of 10.2.0.51521, Precise/Concentrated Sigils cause Cycle of Binding to not apply Sigil CDR when affecting a target~~
- ~~As of 10.2.0.51521, Cycle of Binding does not give CDR to Elysian Decree, but casting Elysian Decree causes CDR on other Sigils~~
- ~~As of 10.2.0.51521, Improved Sigil of Misery does not reduce the cooldown of Sigil of Misery when talented into Precise/Concentrated Sigils~~
- ~~As of 10.2.0.51601, Illuminated Sigils’ tooltip is showing 30% parry instead of the 20% that it grants~~
