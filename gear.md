---
layout: default
---

This game has a system for overwriting gear appearances with other appearances called Glamours. Because of this you should never equip an item for its appearance and instead use glamours to change appearances of the good gear. This page only covers the practical side of gear.

### Stat Explanations

* Item Level (ilvl) - A rough gauge of the power of an item. And a pretty good one, though Normal Quality gear (e.g. vendor gear) will have lower stats than normal for its ilvl. Most gear you use (dungeon drops, raid drops, etc) will all have the same amount of stats at the same ilvl.
* Weapon Damage - Shown as Physical Damage or Magical Damage in the top-left of your weapon's tooltip. This is the single most important stat on your sheet for both damage and healing.
* Strength, Intelligence, Mind, and Dexterity (collectively known as "main stat") - Each job uses exactly one of these to scale both damage and healing. Healers use mind. Tanks and melee (other than Ninja) use strength. Ninja and ranged physical use dexterity. All caster dps jobs use intelligence. There is only one case of scaling anything with a separate stat, and that is SMN: their physik heal scales with Mind instead of Intelligence, so it becomes worthless _way_ before max level.
* Vitality - Determines your maximum HP. Tanks will have more HP than most, followed by physical dps which all have about the same, then casters and healers which have a touch less than physical dps (but more magic defense to make up for it).
* Defense and Magic Defense - Converts into a % resistance to physical and magical damage respectively. The conversion ratio is based on your level. Only tanks worry about this stat, and even then the amount you get is standardized so above level 50 you probably won't really think about it.
* Critical Hit (crit) - A substat. Scales critical hit chance, as well as how much bonus damage you get from a critical. Base chance is 5%, base multiplier is 1.4x (or +40%). Heals can critically hit. 
* Direct Hit (DH) - A substat. Scales direct hit chance, which is a chance to deal 25% bonus damage. If the attack is also a critical the floating text changes to show multiple exclamation marks at the end. Direct hits and criticals stack multiplicatively (e.g. 1.25 * 1.4 = 1.75x damage). Heals _cannot_ direct hit.
* Determination (det) - A substat. Scales damage and healing across the board by a percentage. Does not affect %-based abilities like The Blackest Night or Benediction.
* Tenacity (ten) - A substat. Functions like determination, only slightly weaker. It also reduces damage taken very slightly, but not enough to be worth it on those merits. Only functional when on a tanking job. On other jobs it won't even give the damage or healing benefits.
* Piety (pie) - A substat. Increases the amount of MP gained passively when in combat. Does not affect out-of-combat MP recovery, or any other MP recovery mechanism (e.g. Lucid Dreaming). Only functional when on a healing job.
* Skill Speed (sks) - A substat. Reduces the time you must wait between GCD usages on weaponskills. Has no effect on spells. 
* Spell Speed (sps)- As skill speed, but affects only Spells.
* Rarity - The color of the item's icon indicates its rarity, but ironically this is (mostly) not useful information on its own so most people ignore it. White items, and some crafted green items, can be normal quality.
* Others - There are other stats that can appear on gear, but they either only apply to non-combat classes, or only function very specific niche content.

**Gear Limitations**
* All items of the same item level will have the same weapon damage and attribute bonuses, assuming they are High Quality (HQ) or equivalent.
* Normal Quality (NQ) items, where a HQ variant exists, have inferior stats for their item level. You can check if a High Quality version exists by holding Control while looking at the tooltip for an item. If it changes to show HQ stats, then the one you were looking at is NQ and thus inferior for its level.
* Aside from a small few rare cases, random drops from dungeons, raids, etc, will always be equivalent to HQ even if not stated.
* Once level 50 or higher, each item will have exactly one main stat (strength, intelligence, mind, or dexterity), vitality, and 2 substats.
* Each item will always have two substats on it (e.g. critical hit and determination). One will be higher than the other. The maximum amount of any one substat on the item will be equal to that higher substat (i.e. you can't use materia to go higher than that).

### Stat Priorities

A stat priority system is one where you focus first on maximimizing the stats high on the priority, picking up stats lower on the priority only when you can't get more of the higher ones, or if you would have to sacrifice lots of a slightly lower priority stat to gain only a small amount of the higher stat.

This game, due to stat breakpoints, does not _strictly_ follow a stat priorities system. That said, such a system is the most reasonable way to pick gear until you have a full best in slot set for a specific duty/instance.

The priority of even the highest substat is well below the priority of main stat. There are only a small handful of situations in any given raid tier where it's a damage gain to take a piece with less main stat to avoid poor substats, and it's usually on healers and/or rings. Unless you _know_ you should be taking the lower piece, use substats only as a tie-breaker.

**General Priorities (All Jobs)**:
* Weapon/Magic Damage - Easily the single most important stat for everyone, always.
* Main Stat - Strength, Dex, Int, or Mind (depending on job). 
* _Enough_ Skill/Spell Speed - For most jobs there's a very specific comfortable point they want to reach, and this is the priority for hitting that point. Anything beyond that is much lower priority. (You can safely ignore this entry in the priority list until max level.) 
* Critical Hit - The best substat for all jobs once you start stacking it. Because it scales exponentially, at very low critical hit values it can actually drop under determination in power, but realistically only BLM has any gearsets reach that threshold.
* Direct Hit - Scales _very slightly_ better than determination. Never appears on healer or tank gear, but they can still meld it.
* Determination - The baseline substat. Very reliable, but on average very slightly weaker than critical or direct hit.
* Tenacity - Tanks take this begrudgingly when they somehow lack a better option. Which does happen.
* Skill/Spell Speed - Specifically _extra_ speed beyond what you need for comfort. For jobs that have a comfort point that uses no skill/spell speed, this stat tends to be worth somewhere between 1/2 and 2/3 of determination, making it a large drop-off compared to the above substats.
* Piety - Varies between worthless and invaluable, depending on whether or not you are running out of MP, making it hard to rank properly. New healers should allow themselves to get way too much piety, then scale it back only after they find it unneeded.

**Exceptions**
* WAR - Always treats Direct Hit as bottom priority. Just don't use it. It's so bad for them. This is because they get lots of free direct hits already. Even tenacity is higher priority.
* MCH - Direct Hit and Determination end up tied in value for them. You usually still prioritize direct hit due to gear sharing with other ranged physical jobs.
* BLM - Treats Spell Speed as the same priority as Critical Hit, even once SpS hits comfort. BLM builds to either maximize crit, or maximize speed, as two variant Best In Slot options. Though when maximizing speed, DH and det often become higher priority than crit.

### Gear Sources

* Vendors - While you can buy gear from NPC vendors, this gear is sub-par for its item level and is usually only advised if you have a slot that's seriously out of date. The exception is the small handful of endgame vendors that sell the _really_ good stuff, but they don't sell it for gil.
* (Leveling) Dungeon Drops - Dungeons with a level requirement that doesn't end in a 0 will drop you one item meant for your class directly to your inventory at the end of a run, in addition to any lucky random drops. If it's higher ilvl, you may as well use it.
* (Endgame) Dungeon Drops - No guaranteed drops, but aside from the first couple of launch dungeons the gear from these is more of a catch-up mechanism for those coming in later.
* Tome Vendors - At any endgame level there will be vendors that sell tome gear. Each raid tier also has a corresponding set of tome gear that is of the same item level (except the weapon, for which the raid drop is very slightly better). Any from old expansions will cost Poetics, while current expansion stuff will require the current tomestones (which changes every raid tier). The latest tomestone stuff is used as part of best in slot sets! Current expansion tomestone stuff comes at a lower, unaugmented item level and must be augmented to match raid gear.
* Normal Raid Drops - Drops as a token that you trade for the gear you want. Not as high of an item level as the Savage drops, but good enough to get you _into_ savage if no slot is lower than what normal drops. Be aware that when a raid tier is new you can only win one token per boss per week (but you can keep running and passing on tokens you don't want until you get the token you _do_ want).
* Savage Raid Drops - Each boss will drop coffers and books. When a raid tier is new, having people in the group that have already cleared that week will reduce the number of coffers (possibly to 0!) but you will always get the book drop (once per week). You can trade books from a boss to get specific items that boss can drop.
* Extreme Primals - Usually these just drop weapons, but they're pretty decent weapons that are often good to use while you're working on getting the latest savage raid weapon (or possibly tome weapon). At expansion launch there is also a primal that instead drops decent accessories.
* Ultimate Weapons - Dropped from Ultimate fights, these weapons are exactly identical to the savage weapon you're expected to beat the fights with, save that they can meld one more materia and have a much cooler appearance. Realistically these weapons are _only_ farmed for the special appearance.
* Relic Weapons - A grindy catch-up weapon that most farm primarily for the appearance. It is never best in slot until well after most teams will be done with that content anyway. Nevertheless, it's technically the best weapon for all content for the last few months of an expansion. They take a _long_ time to grind out. Dozens of hours minimum.

### Full Detail Endgame Gear Acquisition

Every expansion has an endgame hub. For Shadowbringers this is Eulmore. All of the endgame gear that you buy or augment, whether with special currency or token drops, will be bought in this hub. _No best in slot gear is gil purchaseable_. I highly encourage you to poke around on vendors looking at items to see what's available.

The descriptions below are not necessarily how the game has _always_ worked, but it is how it works now, for the latest raid tiers, and the devs tend not to make drastic changes.

**Crafted Gear**

This gear is made by players and is 20 item levels behind what the savage raid drops, but releases at the same time. It is just good enough to be technically able to complete the entire raid tier if your entire team is _very_ good at the game, and is meant as a way for faster raid teams to go into the tier with the confidence that they are not limited by their gear.

These gear sets can be pentamelded, which means melding 5 materia into each item in spite of the normal materia limitations. This is very expensive as each materia past the guaranteed slots has only a small percent change of success, so it's typically only done by very hardcore teams.

Note that normal gear cannot be melded past the shown limits, so spending oodles of cash on melding is only a thing for crafted gear.

**Tome Gear**

Every raid tier a new type of tomestone is added, and you are limited in how much of this tomestone you can gain per week (usually 450/week until the very end of an expansion). These are used to buy the latest tome gear. You will want to farm that currency (to the extent it allows) as every best in slot set ever made uses at least a few pieces of tome gear, and its higher ilvl makes the other pieces useful while you're waiting to get the true best piece for that slot.

When initially purchased the newest tome gear will be 10 item levels behind what the savage raid drops. However, there are augmentation items that drop from savage to upgrade them to be equal to savage item level (except weapon). The second boss will drop the token needed to augment accessories, while the third will drop the token needed to augment armor. Once upgraded they are called "augmented". 

The tome weapon is special. You must acquire a tomestone item (not to be confused with the currencies) that drops from the third boss of savage, in conjuction with 1000 tomestones (the currency). You first buy 10 of a special token with those 1000 tomestones, then trade those 10 tokens and special tomestone for the weapon. Check the vendors to find the weapon you want and confirm which kinds of tokens and tomestones you need, as it changes with each raid tier. You can also get the special tomestone from beating the final normal fight for enough special tokens from there. It usually takes 7 kills, and they must each be on separate weeks as you can only get one of these tokens per week.

While the tome weapon is the same item level as the other tome pieces, it still is rarely best in slot as the savage weapon is always slightly higher item level than even the upgraded tome weapon.

**Normal Raid Gear**

This gear is 20 item levels behind what the savage raid drops, but still technically meets the minimum item level for the final savage boss from that same raid tier. 

Each time you beat a normal it will drop 8 tokens that everyone rolls on. When the raid is new, you can only _win_ one of these tokens per boss per week, but you can roll on as many as you want and keep rekilling the boss until you win the one you want. 

Each token type corresponds to one piece of gear, except accessories which are all bought with the same token. Chests and Legs require 4 tokens of their type (which is your _entire_ allotment for the week), smaller armor pieces cost 2 tokens, and accessories only cost 1.

Each boss drops the same tokens every kill, no exceptions.

The first time each week that you kill the final normal mode boss you will also receive a special drop straight to your inventory. This token is not used for normal raid gear, and is instead an alternative method to get an item you need for the tome weapon (see Tome Gear).

**Extreme Primal**

These typically drop weapons, and of an ilvl lower than the current tome or raid drops, but unlike those sources they are not weekly limited. This means you can keep killing the primal until you get every weapon you want without limitation. Most teams will expect their members to get primal weapons early in a raid tier since the primal that is added at the same time as the savage raid will drop a weapon higher in item level than the best crafted, and anything that could beat it will be unattainable for at least 3 weeks due to weekly lockouts.

Each kill of a primal also drops 1 or more tokens. You can trade 10 of these for a specific weapon of your choice. Alternatively, after the primal is no longer the newest one, you can trade 99 of these tokens (called "totems") to buy the rare mount that the primal can drop.

**Savage Raid Gear**

The best of the best gear, tied with augmented tome gear for item level (except on weapon, where Savage wins).

Each savage fight has a once per week limit on seeing drops. That's _seeing_ drops, not winning drops. Each boss will have 2 treasure chests to open if no-one is locked out for the week. If between 1 and 4 people are locked out on loot, only one chest (chosen randomly) will appear. If 5 or more are locked out then no treasure chests will appear. Anyone who is not locked out will get a book drop, regardless of how many others have cleared. Only those that are not locked out can roll on any loot that does drop. No second chances.

You can get locked out on a fight in one of two ways: Either beating the boss, or entering the instance for a later boss. For example, if you enter the instance for the 3rd boss, you are locked out on the 1st and 2nd bosses even if you hadn't yet killed them that week. Avoid skipping bosses unless you don't need any loot from them anymore.

Despite the term, you can still enter the instance for and kill a boss when "locked out", the term only refers to your eligibility for item drops.

Each floor drops very specific items, as below, in coffer form. These coffers can only be opened outside of an instance and will always give an item meant for the job you're on. For example, a Ring coffer will become a ring of healing if opened on a healer job, or a ring of aiming if opened on a ranged physical job or ninja. You cannot have two of the same coffer on your person at a time, so if e.g. 2 rings drop you cannot win both.

* First Floor: Accessories and Belt, 3 total, in any combination (*belts will no longer exist in Endwalker). You could get 3 rings, or 1 necklace and 2 belts, or any other combination.
* Second Floor: Helmet, Gloves, or Boots, 2 total, in any combination. Plus one token for upgrading tome accessories, and one token used as part of buying a tome weapon.
* Third Floor: One legs coffer, one randomly chosen coffer of helmet, gloves, or boots, one token for upgrading a tome weapon, and one token for upgrading a tome armor piece.
* Fourth Floor: One weapon coffer, one body armor coffer, one specific weapon chosen at random (e.g. the RDM rapier), a mount, and a minion (the same one that drops in normal mode). With luck your team could get 2 useful weapons every week, but sometimes the boss just keeps dropping the same weapon for that specific one.

In addition to the above is the books. Each time you clear a boss and are eligible for loot, you get a single "book" token, with each boss dropping a different token. With these you can buy items that the boss in question normally drops. Head, Gloves, and Boots are bought with the 2nd boss's tokens only, despite the third boss also dropping those items. Each item costs between 4 and 8 books. These tokens mean that even if you have very bad luck at winning the coffers that the boss drops, you will still slowly get the items you want over time.

### Materia Melding

Materia are a socketable item that you attach to a piece of gear to grant it additional stats. While more variety has existed in the past, these days only substats can be melded for effect. (Though you might still find old materia like Strength materia on the marketboard, it will provide no bonus.)

Each item will have a set number of sockets between 0 and 5, and may or may not allow "advanced melding" (called overmelding by the community).

The sockets shown have a 100% chance to accept any materia you attempt to meld, and you can use the NPC materia melders to do so. If advanced melding is allowed, then you can continue melding past that point up to a final maximum of 5 materia, but such melds will as low as a 5% chance to succeed. On failure the materia is broken, but the item is unmodified. Only players with sufficient crafter levels can overmeld, but thankfully you can ask another to overmeld for you without having to trade them the items.

As a general rule, only white and crafted items allow advanced melding. Raid drops, dungeon drops, tome equipment, etc do not. Items with 5 sockets are exceedingly unusual. Most will have only 1-2 sockets.

Each item has a set limit to how much it can accept on any given substat. This limit will be shown at the bottom of the melding window. It will allow you to meld (with warnings) even if it would push past this limit, but stats beyond that limit will not be counted. Because the limit is specific to each substat, you can just meld a different substat if your preferred one is already at/near its limit.

**Expectations**

People will not expect you to have melded your gear in most content. However, they _will_ expect it in extreme trials, savage raids, and ultimates that are at the current maximum level. Realistically people don't really check, but don't try to get away without melding in that content. Materia isn't too hard to come by anyway, and melding nothing is easily a 5% or more damage loss.

**Acquiring Materia**

Materia drops from chests in max level dungeons, and is purchaseable from hunt and beast tribe vendors, as well as possibly some other places. You can also get tokens that you can trade for a materia of your choice, usually gained as a roulette bonus (for matching the requested role in leveling or alliance roulettes) or as a drop from hunts. My preferred route is to do hunts as you get more tokens per hour that way than other methods.

You also get a slow supply by Extracting your gear. Certain activities grant spiritbond with your gear. When that reaches 100% it will trigger a sound effect and a chat message, and you can then right-click and "extract" materia to get a random free materia from the item (and reduce the gauge back to 1%). This used to destroy the item, but doesn't anymore, so it's just free. The option to extract is right next to "retrieve", so try not to confuse the two. Retrieve removes materia you have socketed instead.

### Item Level Sync

Some duties will sync your item level. When this happens, the way it modifies your gear is non-obvious, so it merits a quick explanation.

Item level sync is done on a _per item_ basis, not on your total stats. This means if you have only one item over the sync limit then it will still have its stats reduced even if your average is under the limit.

Once the game decides to sync an item down, it does the following the adjust its stats:

* Disables  the bonuses from all materia.
* Reduces weapon damage, main stat, and vitality to what a HQ item of that item level would give.
* Reduces each substat on the item so that no one substat is higher than the melding cap for a HQ item of that item level.

That last point on substats is the weird one. It looks at each substat one at a time rather than looking at them together, so even though a typical item would have only one substat at the cap and another that's lower, an item being synced down by a large amount can easily have both substats capped. And some special items, like relics, can potentially cap as many as _four_ substats simultaneously.

Although materia is disabled, the fact that substats cap individually means that when equipping items with high enough item level you can potentially be better off allowing the sync than trying to get an item of the appropriate ilvl. This is most notable in older ultimates.