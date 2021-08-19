---
layout: default
---

The number one most important thing is, of course, to read your ability tooltips. There's a lot of good info in there.

## Uptime, etc.

Everyone has the instinct that tells them that pressing buttons faster must mean more damage. And while that can be true, this game does a few things to limit how fast you can press those buttons. This section is to talk about the weird nuances of those limitations and how to work within them to maximize how much you can get done.

The game has four core limitations to your button pressing speed, all of which happen concurrently (at the same time):
* Animation Lock - A time after each ability activation in which you are unable to use any other action. You can still move. (Sprint count as an action.)
* Cooldowns - After being used, this ability cannot be used again for a set time. Example: No Mercy has a 60s cooldown. After using it, you must wait 60s before you can use it again.
* Global Cooldown (GCD) - Global cooldown is like a cooldown, but one that is dramatically shorter and shared among many abilities. Typically anything labeled Weaponskill or Spell will be "On The GCD". So hitting any GCD ability will put all of them on a very short cooldown (typically 2.5s or faster).
* Cast Times - Any ability with a cast time naturally prevents you from activating any other ability until that cast timer is finished.

This game does have queueing. This means that if you hit the button for an ability when any of the above prevent you from using it, the game will put it in a queue for about a half second. If you become able to use it before that time is up, it will activate at the earliest instant the game's rules allow (which means low ping players don't end up doing tons more damage for free). Because of this, you are encouraged to get used to hitting your buttons just before they would be able to activate so that the system can nail the perfect timing for you. (Only one ability can be queued at a time; if you hit another one it replaces the previous one.)

_WARNING_: Any ability activated via a macro _does not queue_. For this reason it is not advised to use macros for most abilities. More on macros later.

### Animation Lock
This is pretty straightforward. Any ability you activate will cause a short animation lock that prevents anything else from being activated, no matter what. For most abilities this is about 0.7s. 

Some abilities will have longer or shorter animation locks, on a case by case basis. Dragoon Jumps are typically longer. Ninja's mudras and Dancer's steps are shorter (since they are only meant to be 0.5s apart). Item usage is about twice the normal animation lock. Red Mage's displacement is also almost twice the normal animation lock. I don't have the exactly values for any of these, but as you'll see later that rarely matters due to how things round out.

Unfortunately, as of this writing, animation lock is slightly ping dependent. If you have a very high ping (150ms or more) you may experience animation locks +0.1s or so longer than normal. This can make some rotations difficult or impossible to perfectly execute.

### Cooldowns
Pretty straightforward. On the in-game UI many abilities will list a "Recast". This is their cooldown. You cannot use the ability again until that much time has gone by. Time spent stunned or in a cutscene or anything else always counts (though one fight does have a "time stop" mechanic that actually does pause them while it's active). 

Some cooldowns can be shared. Abilities will call this out in their tooltips. The exception is the Global Cooldown, which is not called out explicitly. An ability can both have its own cooldown _and_ be on the global cooldown, in which case it will only show its own cooldown. This happens with abilities like Drill or Gnashing Fang. 

Generally speaking you will try to use these abilities as often as possible. A good opener will line them up in a reasonable way, then after that you use them as soon as they are available.

### Global Cooldown (GCD)
Functions like a regular cooldown, except that it's shared. Different abilities can invoke longer or shorter cooldowns, but most have a base of 2.5s. Whatever time that ability has for its GCD, it puts all other GCD abilities on cooldown for that long regardless of if _they_ have longer or shorter GCDs. For example, a Machinist can use Heat Blast (a 1.5s GCD) then use Drill 1.5s later, even though drill invokes a 2.5s GCD.

Some abilities can both be on the GCD and have their own cooldown. In these cases, their personal cooldown will be all that's listed on the tooltip, and the ability almost certain uses the standard base GCD of 2.5s.

Your global cooldown is affected by Skill Speed (if you use a weaponskill) or Spell Speed (if you use a Spell). These substats will reduce how long the global cooldown takes. Other abilities, such as a Ninja's Huton, can also reduce this further. This applies to all GCDs, _but_ has a minimum of 1.5s. No GCD is allowed to invoke a less than 1.5s global cooldown.

All jobs are focused primarily on either spells or weaponskills, but some do have both. In those cases the one of the wrong type won't receive any speed increases from standard gear simply because your job's gear won't include it. You could meld it, but don't do that. There is always a better substat. As an example, a Red Mage is a caster so its gear will sometimes have Spell Speed, but will never have Skill Speed. Their melee abilities are not boosted by Spell Speed. They could meld Skill Speed via materia to make them go faster, but that is never in a million years the right choice for optimal damage. The reverse situation occurs with Paladin (who never melds Spell Speed despite having spells).

### Off-Globals
Any ability not on the global cooldown is called an off-global, or oGCD for short. These can and _should_ be used while your GCD abilities are on cooldown. Assuming they have standard animation lock, and the GCD you just used was of standard length, you can usually fit 2 oGCDs in without causing your next GCD to be delayed.

### Cast Times
An ability with a cast time will show a cast bar and not have its effect until that time has elapsed. You must stay still during this cast time until the timer goes under 0.4s remaining, at which point you are allowed to move without canceling it (this is called "slidecasting").

If an ability has both a cast timer and is on the GCD (very common) then the two timers occur concurrently. They also occur concurrently with animation lock. For example, if your spell has a 1.5s cast time and invokes a 2.5s GCD, then for the first 0.7s you will be animation locked, casting, and have your GCD ticking. For the next 0.8s you will not be animation locked but will be casting with your GCD ticking. From 1.1s-1.5s you're still casting but can slide to move. From 1.5s-2.5s your cast has finished and your GCD is still ticking, but you could use any off-GCD ability.

If the cast timer is longer than the GCD, then you're just stuck waiting for it to finish before using anything else. Such is life. This happens with Black Mage a lot and part of their challenge is finding places to smoothly use their off-globals (or minimizing loss from less smooth usage).

### Putting It All Together
Taking all of the above together with an example: You start with a 2.5s GCD, instant cast. This also animation locks you for 0.7s. After the animation lock ends this gives you another 1.8s to do other things that aren't a GCD before your next GCD can be used. Since off-GCDs typically animation lock for 0.7s, this gives you enough time to use two such abilities (and 0.4s to spare, which helps account for lag, also helps if you have faster than 2.5s GCD). 

This results in the following basic pattern:

* GCD
* Off-GCD Slot 1
* Off-GCD Slot 2
* (Next GCD)

Those off-gcd slots are also called weave windows, and using an off-gcd while your GCD is ticking is called weaving. Using two after a GCD is called double weaving. Some GCDs are too fast for two and you might only single weave. Triple weaving is reserved for very niche cases, and one spot in the Summoner rotation. Any oGCD that animation locks you for longer than normal, like items, dragoon jumps, or red mage's displacement, can be treated as 2 weave slots for simplicity.

The most important aspect of play is to use your GCD on time, every time. Do not allow your off-GCD usage to delay it unless you're really sure it has to be done. This consistency forms the foundation of optimizing fights for higher damage. If you know you will use a GCD at a very specific time, every time, then you can reliably adjust (or not adjust) to what the boss is doing at that moment, or even make micro adjustments to skill/spell speed for some top tier optimization.

There are classes that have to let their oGCDs cause their GCD to be delayed, but most classes don't and the ones that do only usually have 1-2 such instances. Summoners frequently use 3 offGCDs as part of summoning phoenix (oGCD 1, summon phoenix, oGCD 3) to force the summon to line up _just right_ with their GCDs.

There are some other patterns that can arise with different GCD timings and cast timings.

1.5s or faster cast time, 2.5s GCD:
* GCD
* Off-GCD Slot 1 (no long off-GCDs)
* (Next GCD)

2.5s cast time, 2.5s GCD:
* GCD
* (Next GCD)

Instant cast, 1.5s GCD:
* GCD
* Off-GCD Slot 1 (no long off-GCDs)
* (Next GCD)

**The Double Weave Ping Cutoff** - The exact GCD cutoff where people start to have trouble double weaving varies by ping. With godly ping you can double weave with a GCD as fast as 2.1s or so. With extremely poor ping you may have trouble even at 2.4s. You'll have to experiment to find the exact line for you. When you find it, you can estimate how long you are animation locked at your ping by taking that time and dividing by 3 (GCD animation lock, plus 2 oGCD animation locks).

**The Single Weave Ping Cutoff** - As above, this varies by ping. With good ping a 1.5s GCD (the fastest GCD allowed by the game) still allows a single weave. But those with moderate or poor ping may find this isn't the case, and adjustments to the rotation will have to be made to avoid weaving at those times.

## Other Topics

### Macros
FFXIV macros are fairly limited, and often not recommended. They can have up to 15 lines, and will execute one line per rendered frame. This means at 30fps it will take 0.5s to finish the macro, but at 150fps it will only take 0.1s. Yes, that's right, your GPU will affect how fast macros execute. In addition, any line that asks the game to use an ability (such as "/ac Shirk <2>" to use shirk on the 2nd person in your party list) will only execute if there is nothing blocking you _on that frame_. If you're in animation lock, even for just one more frame, the line will do nothing. It will not queue like a normal ability does. It will simply move on to the next line next frame (and flash an error on your screen).

In addition to the above limitation, Macros cannot pause between lines except on whole second increments (e.g. it can wait 1s or 2s, but not 1.5s), and only one macro can run at a time (activating another will cancel the previous).

Despite these limitations there are a few cases where macros are common/acceptable:
* **Sprint** - For whatever reason, this ability already lacks the ability to queue. As such there is no disadvantage to using a macro for it. A macro that has "/ac Sprint" 13 times will give you the same functionality as the normal sprint button, but will try for 13 frames instead of 1. The reason it's 13 instead of 15 is so that the last two lines can be used to turn off macro errors and change the icon to match Sprint.
* **Ground Targeted Abilities** - These abilities also cannot be queued, because when you first "use" them they instead open a targeting reticle for aiming them. This reticle will not appear if you are in any way unable to activate it (e.g. animation lock). As such people frequently macro these to either enemy target, or self-target (so that they drop at their own feet). Salted Earth is a good example. Fair warnign: If you use enemy target and the enemy is floating off the platform, the macro will fail. Keep the "real" version somewhere on your hotbars as backup.
* **Single Targeted Friendly Abilities** - This includes things like Shirk, or Nascent Flash. Mostly a tank thing. While it _is_ more optimal to quickly swap targets and use the ability the hard way, some may have trouble swapping quickly or smoothly enough to make it worth it, in which case using a macro to aim them at a specific teammate instead is potentially a better option. 
* **Crafting/RPing** - Not covered here. Crafters use macros extensively since crafting is not timing sensitive, but the reliability gains are huge. RPers also use macros for various things. But please don't be that guy that has an RP macro attached an ability. It just annoys people. You can use the /echo command to post messages to only your chat if you absolutely must.

Regardless, any time you use a macro you must be aware that you may not be able to weave as smoothly as you normally do. If you find you start delaying your GCD while using a macro, you should probably adjust to use only the one macro'd ability between two GCDs rather than going for the normal double weave.

The most common macro is formed as follows:

```
/merror off
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/ac Sprint
/micon Sprint
```

The first line disables errors so that you aren't spammed with nasty messages/sounds when /ac Sprint fails to activate. /ac Sprint attempts to activate the Sprint ability. /micon Sprint causes the icon of the macro to change to match Sprint's icon (purely for visual's sake).

For the other two cases you can use \<t>, \<ft>, or \<(a number)>  (e.g. \<2>) to target). 

Example shirk macro:

```
/merror off
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/ac Shirk <2>
/micon Sprint
```