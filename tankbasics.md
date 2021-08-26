---
layout: default
---

The job of the tank is to take the big hits that others can't. That sounds pretty straightforward, and on easier content it is, but doing as good as possible at this job still takes _some_ effort and shouldn't be flagrantly disrespected.

The tank role has two sub-roles when in 8-man content: Main Tank (MT) and Off-Tank (OT). The only difference is that Main Tank is the one who currently has the boss's attention. Some mechanics force you to swap, but not all fights will require this, in which case MT can potentially stay MT the entire time.

### Helpful UI

**Party List and Enmity Order**

On your party list, there will be numbers next to the icons for each person. These numbers vary from 1-8, and one of them (typically the 1) will be replaced by an A. This is the order of everyone's enmity for your current target. 1 has the most enmity, 8 has the least. Typically enemies target the person with the most, so the 1 is usually replaced with the A, which indicates the enemy's current primary target. There are rare cases where enemies will decide primary target separate from enmity.

As a tank your goal is to be #1 (in 4-man content) or #1/2 (in 8-man content). In 24-man content you can only see numbers for your team, so you can be #1 on your team (and should be) without being the main target. 

In 8-man, enemies often will target both #1 and #2 with big hits somewhere in the fight, so it's important to be at least #2 in threat. Even if they don't, being #2 means that if the current tank dies for any reason the boss immediately turns to the other tank rather than a squishy healer or DPS. Not all boss abiliies meant to target both tanks will use #1/#2 aggro. Some will use #1 and "any living tank that isn't #1". If no such person exists the second target is chosen randomly.

As a rule of thumb, avoid taking threat from another tank on accident. If they have #1 enmity and are handling the boss, and the fight isn't forcing otherwise, you should just let them keep it. 

**Enemy List**

Usually below the party list, a separate UI element will list all enemies you are currently in combat with, as well as their health and a little colored symbol. That colored symbol indicates your enmity on that target. A red square means the enemy has you as their primary target, and this is typically desirable. A green dot meants you're nowhere near their top priority. Orange means you're close to taking threat, but don't have it. Yellow means you have noticeable threat, but aren't particularly close to the highest. Note that these are %-based, so for the first 1-2 attacks in a fight the colors can be a bit chaotic.

You can use the enemy list in dungeons to determine quickly if an enemy has decided to attack a teammate instead of you. If you're focusing on AoE this shouldn't typically happen, but you can use a ranged attack or provoke to bring that enemy back to you. Ideally the person being targeted should drag the enemy into the group so you hit them while doing your aoe, but that won't always happen.

### The Toolkit

**Tank Stance**:

The name of this ability varies between tanks. Current ones are Iron Will, Defiance, Grit, and Royal Guard. When active, all enmity you generate is multiplied by 10, making it very easy to keep the attention of enemies focused on you. The only person who can reasonably take threat from you is the other tank. You _do_ have to deal damage still, though! 0 times 10 is still 0. So make sure you're hitting every enemy to keep them on you.

Avoid taking threat from the other tank on accident. There will be planned times to take over, which is what Provoke is for.

**Provoke**:

A role action that increases your enmity on the target to be 1 higher than the current highest, then adds extra enmity as though you hit them with an extremely heavy attack (I believe it's equivalent to 2000 potency?) This extra enmity is also multiplied by tank stance. Basically ensures you have the enemy's attention, and gives you some buffer so you don't immediately lose it.

**Shirk**

Gives 25% of the enmity you have with all enemies over to the target. Usually used when the other tank provokes to give them a comfortable enmity lead over you so that you don't accidentally take the top spot back before you plan to.

**Ranged Attack**:

The name varies between tanks, but it's always a 15y ranged attack that interrupts your combo. Usually not advised to use this except as a first hit to initiate the fight. Generates large bonus enmity which is also multiplied by tank stance.

**Mitigation**:

The bread and butter of being a tank. These abilities reduce the damage you take even further and are crucial for doing your job, as harder fights will hit so hard that you'll instantly die without them.

Mitigation stacks multiplicatively. That is, if you have two 10% mitigation effects up, it does not mitigate 20% but instead mitigates 10%, then mitigates 10% of what's left, which puts you at taking 81% of the damage, for a net of 19% mitigation. This means stacking mitigation is best avoided, though some effects will hit hard enough to require it.

Every attack that hits you has a point called a snapshot. This is the time when it checks what mitigation you have up, and typically occurs a couple seconds before the damage actually shows up. No matter how much mitigaiton you use, if it isn't on your buff bar (or their debuff bar) before that snapshot, then it does nothing. Common snapshots include end of cast bar for the ability, as well as when colored markers disappear. As a general rule try to have your mitigation active and visible on your buff bar at least 2 seconds before the damage numbers would appear.

* Rampart - 20% mitigation for 20s. Easy to use, easy to understand.
* (Name Varies) - A 30% mitigation for 15s. Each tank has their own name for it, but they all work the same.
* Fast Mitigation - Each tank has a mitigation with a fast cooldown. Functionality varies, but it's in the neighborhood of 15-25% depending. Typically used as often as possible.
* Mitigate Other - Shares a cooldown with the fast mitigation (or is actually the same ability), but is meant to be used on someone else to help _them_ take less damage. Good when you're the off-tank and the main tank is about to get clobbered, but you're comfy.
* Invuln - A "don't die" ability with a very long cooldown and short duration. Paladin and Gunbreaker both have invulns that are good to use in dungeons, while the other two are best saved for raids.
* Tank-Specific Tools - Each tank has 1-2 other tools that are utterly unique to them. This includes self-healing (on WAR), mitigation only against magic (on DRK), etc.
* Reprisal - Makes every enemy within a short range deal 10% less damage for 10s. Not much, but it's something. And crucially, it affects raidwides, so you can help keep your team alive with it. The cooldown is short and both tanks have it, so in 8-man content you should alternate and use it frequently.
* Arm's Length - It doesn't look like a mitigation tool, does it? Well, surprise! While arm's length is active, basic enemies (_not bosses!_) will be slowed if they hit you. This slow reduces how fast they attack you, which means you take less damage. So use it in dungeons on trash packs.
* Party Mit - Every tank has at least one ability (PLD has two) that reduces the damage the team takes, rather than being focused on themselves. Typically reserved for raidwides to help the team survive rather than being used for yourself. WAR will sometimes use theirs for themselves in dungeons (Shake it Off) since there are no dangerous raidwides there.

Community convention: Despite mitigation stacking multiplicatively, people will still say things like "needs 40% mit and shields". This means using mitigation that would add up to 40% if you just read the tooltip numbers, and does not actually refer to needing to reduce the damage by 40%. In this case, two 10% reductions and a 20% reduction would be sufficient (for example).

### Doing Your Job

Your job consists of 3 priorities:

* Keep the enemy from attacking any non-tank, where possible.
* Make it as easy as possible for everyone else to do their job.
* Make keeping you alive as easy as possible (primarily via mitigation).

In harder content, work with your team for all of the above priorities. They can often help you figure out how to best fulfill these priorities, and may even be able to use the (minor) mitigation abilities they possess to help smooth over some rough spots.

Keeping the enemy on you is easy. Just have tank stance on and deal as much damage as possible. Since your enmity is multiplied by 10 with tank stance, and your damage potential is, at worst, half that of a DPS, you should easily be pushing 5 times as much enmity as any non-tank.

Helping others do their job is suprisingly simple. Keep the enemy as still as possible, and try to avoid facing them twoards the group (usually very easy). You keep them very still so that melee DPS can attack the enemy from specific angles, and you try to face them away so that any frontal attacks hit only you and not your entire party. Sometimes you'll want to position the boss in a very specific spot to make it easy to do other mechanics while hitting the boss. As long as your thought is "how do I make this as easy as possible for everyone else", you'll be fine.

The final topic is a bit harder to perfect, but the concept is simple enough. To make keeping you alive as easy as possible, your goal is to take the single most difficult part for your healer easier by using mitigation. For example, if a fight (on a 5-point scale) has three 5/5 difficulty parts, and four 4/5 difficulty parts, you should first get those 5/5s down to 4/5s with mitigation, then take the seven 4/5s you now have and spread the mitigation that's left between them as evenly as possible. If those all drop to 3/5 and you still have mitigation left, just use what's left wherever that won't interfere with those prior spots. If there are multiple very difficult parts back to back consider using your invulnerability to cover one of those spots, or swap with your other tank so that they can use their mitigation for part of it instead.

**Dungeon-Specific**

In dungeons the hard part is trash (the enemies between bosses). Prioritize using all your mitigation there, and try to space it out so that you only have one big mitigation (20% or higher) _or_ two smaller mitigations at a time. There's no perfect pattern here.

Most teams prefer that you pull together at least 2 packs, even in leveling dungeons. But if that proves too much for the team it's fine to drop it down. In endgame dungeons it's expected that you keep pulling enemies until the game makes you stop (usually 2-4 groups). 

Use sprint before you first enter combat if you're pulling multiple packs. The extra speed makes it possible to outrun the enemies so that they don't deal damage to you (or at least, deal a lot less) while you're running to the next group you plan to pull. You want to use it _before_ combat if you can, since doing so doubles its duration.

When fighting many enemies it is acceptable to move around a lot. Try to keep the enemies tightly packed, but don't worry as much about turning them around a lot. No DPS will lose damage in big pulls from enemies turning, but they will lose damage if the enemies spread out. Be careful, though: Every so often the devs like to put an enemy in a trash pack that actually cleaves. Once you figure out an enemy cleaves be more careful turning that specific one. 

### Misc. Tips and Community Conventions

* In casual 8-man content (i.e. not extreme, ultimate, or savage), whoever turns their tank stance on first is usually expected to tank the boss, probably for the whole fight (since such content doesn't require tank swaps). If that person isn't you, start with your stance off and avoid taking threat from the other tank unless strictly necessary.
* In dungeons, spamming AoE to keep threat is not just the way to go, it's also more overall damage. Use your ranged attack and/or provoke to pick up stray mobs when necessary.
* As a tank, you're expected to take the lead. People don't necessarily expect you to know where you're going, but they will expect to go first.
* Don't wiggle idly. Normally any boss movement is taken as a sign that you're going to move the boss on purpose for some reason, so random wiggles confuse people. Also, melee DPS have an easier time maximizing damage if the boss doesn't move or rotate at all.
* While your extra health and defense can make it possible to survive avoidable attacks that DPS cannot, avoid doing so on purpose. These attacks usually also come paired with a debuff that makes all _further_ attacks deal more, and sometimes even reduce your damage output dramatically. If your healer has to heal you more for you to get that extra hit in, then it's a team damage loss so don't do it.
