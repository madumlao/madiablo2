# Items
## Drop Rates
### Nodrops
A "nodrop" is a treasure class that drops no treasure. Each monster, chest, etc that has been assigned a "nodrop" has a percentage chance that it does not drop anything. Most bosses and chests actually "drop" multiple items, however, some of those drops are "nodrops" and so they don't always drop the maximum number of items.

Nodrops have been removed from chests.

Nodrops have been removed from superunique monsters.

Nodrop ratio has been reduced in ordinary monsters from 100 to 64.

### Item Ratios
Adjusted item ratios to make Uniques, Rares, and Set items significantly more common.

### Gems
Gems are used in a lot of recipes, and in and of themselves as equipment buffs. But not only are gems themselves rare, but you can hardly get the right one.

Gems drop rates have been significantly increased by adding them to the "junk" class of tresure (that spawns scrolls, keys, arrows, and bolts). In Act 1, gems will drop at about 1/4 the rate of arrows and bolts. From Act 2 onwards, they drop at roughly 5/8 the rate.

From Act 2 onwards, 2 kinds of gems drop: one of lower quality and one of higher quality (one grade above the current). The lower quality gem drops 80% of the time, the rest is the higher quality gem. In Act 2 this is chipped and flawed. In Act 3 it's flawed and normal. In Act 4 it's normal and flawless. Then in Act 5 and all higher difficulties, it's flawless and perfect.

### Runes
Runewords are one of the few ways of getting higher-level gear that the player has any agency over. However that agency is largely overshadowed by how difficult it is to even get a rune, much less the right ones.

Runes are very rare drops in the original game, so I increased their drop rate. Runes now spawn from "good" drops (usually higher level chests or monsters) at a comparable rate to rings, amulets, and charms, taking the place of gems being dropped.

Furthermore, rune drop rate has been adjusted. Runes used to drop in 2 classes (like gems above), with the lower class rune dropping much more than the higher class rune. HOWEVER, the probability gap between the two increases exponentially with the higher rune levels. At the highest rune levels, the disparity between the 2 classes is so huge (the highest one dropping at less than 1/10000) that the only way to get higher level runes is to trade for them.

Here the probabilities have been adjusted to saner levels. The higher level runes are still harder to find, but in probabilities like 1:6 or 2:7.

### Superuniques
Superunique monsters (such as Act bosses, quest bosses) no longer drop magic items. Instead they only drop Rare or higher.

## Weapons
### Necro Daggers
Daggers will now spawn with necro autoskills, to give incentive to use "poison dagger" on daggers. Daggers may now also spawn with +skilltabs for necromancers.

### Necro Scythes
Scythes have been made into a subtype of polearm. Scythes will now spawn with necro autoskills. Scythes may now also spawn with +skilltabs for necromancers.

### Necro Wands
Wands are meant to be used magically, as opposed to physically. Thus Necromancers can inflict pain using a wand from afar. Wand range has been increased to 20, allowing a necromancer to swing from behind his meat shields.

While wand damage is likely to be weak and attack rating is likely to be low, a Necromancer's attack is augmented by any enchantments, charms, etc that work on the wand. For instance, wands that have a chance of triggering magic, or that deliver cold damage, will be significantly more useful. Furthermore, the meager poison damage that comes from Necromancer heads can be applied to multiple creatures, and bonuses such as life and mana drain will be applied on the attack.

Strength does not affect wand damage. This discourages other characters from buying / using wands and rewards a wand-using necromancer for truly focusing on magic. Instead, wand damage is controlled by automods that affect damage / level and attack rating per level.

TODO: do the same thing for Sorceresss wands, only that they deal higher damage

### Polearms
All polearms, long spears, and staves have been given automods that increase defense. Traditionally, such weapons have often been used defensively, with the body of the staff being used for deflecting attacks. This is reflected in the defense increase with using a polearm, although a shield will still give better defense and additionally, a chance to block.

## Potions
### Full Healing / Full Mana
Full health and full mana potions now drop, although rarely. They can also be created from the Horadric cube - they are cheaper to create than a full rejuvenation potion.

## Horadric Cube Recipes
### Rejuvenation potion
3 health potions + 3 mana potions = 1 rejuvenation potion (gem no longer needed).

### Full Rejuvenation potion
6 health potions + 6 mana potions = 1 full rejuvenation potion (replaces the 3 health, 3 mana + normal gem).

### Full Health Potion
3 health potions + 1 mana potion = 1 full healing potion.

### Full Mana Potion
3 mana potions + 1 health potion = 1 full mana potion

### Full health + Full mana
1 full health + 1 full mana potion = 1 full rejuvenation potion.

## Shops
### Autoskill items
Wand, staff, and scepter prices are completely ridiculous for single player, easily jumping to the 100K mark just because a couple high-level skills get +3. All skill 'cost adds' are reduced to 1/8. Wands and the like are _still_ expensive, but dramaticlly less so.

### Rings and Amulets
Rings and Amulets have huge fixed prices when gambling. This price was reduced to 1/5.


# Rebalancing
## Amazon
### Poison Javelin / Plague Javelin
Poison and Plague Javelin are highly similar to each other. Thus, players will tend to only use the one that deals the most damage.

This mod mixes up the two so that they have different purposes:

1. Poison Javelin is a direct attack spell and an alternative to lightning bolt. It's meant to deliver a large amount of poison damage in a small amount of time.
2. Plague Javelin is a support crowd control spell. It's meant to poison a large number of enemies in a single application. The poison will deal some damage over a long period of time.

Thus the following changes were made:

1. Poison Javelin deals .375 to 0.5625 damage per frame (9.375 to 14/sec) and lasts 2 seconds. At level 1, this counts for 18-28 damage.
2. Plague Javelin deals .3125 to 0.5 damage per frame (7.8125 to 12.5/sec) but lasts 8 seconds and has a larger area. At level 1, this counts for 62-100 damage.
3. Poison Javelin recast delay removed. It is now an alternative to lightning bolt.

Plague Javelin is weaker in damage per second, but it hits more enemies with poison and lasts longer, thus dealing more damage over time. Poison Javelin, on the other hand, is a direct combat spell, so it does more damage per second, although it lasts shorter.

## Necromancer
Although Necromancers are still meant to be powerful zoners, their melee game has improved signicantly, taking cues from the Heroes of the Storm necromancer, Xul, who is a melee specialist.

Necros had the second slowest attack speed (19 frames) after the Sorceress (20 frames) 2 dead end skills (teeth and poison dagger) that would otherwise be powerful up close. Furthermore, as necros are already heavily skill dependent, their choices of weapons are poor due to their dependence on wands for skill boosts.

Necro attack speed has been lowered to 17 frames, on par with the Paladin, and their teeth skill now serves as a powerful up close shotgun. Furthermore, their poison dagger skill can now be used with a variety of blades, including the Necromancer's signature Scythe.

### Skeleton Mage (aka necromage)
Poison Necromages used to a do a ridiculous "1 dmg every 10 seconds" crap, and levelling them up increased the duration by a further 10 seconds. This is insane. Basically if you spawn a poison necromage, despawn it immediately and replace it with fire.

Poison Necromage has been updated to be comparable to other necromages. It now does 4.875 damage per second for 1 second, compared to cold (1-4), fire (2-6), lightning (1-7). Higher levels increase the damage by about 1.5 per second, but also increases the poison duration by 1/5 of a second each, compared to the other elements which increase average damage by 2, or cold by 1. This makes poison _slightly_ stronger than the other elements, but it takes slightly longer to deal its damage.

### Poison Dagger
Poison Dagger is almost universally recognized to be an underwhelming skill, in part because daggers are underwhelming. In Blizzard's "Heroes of the Storm", however, the Diablo2 necromancer is represented as a melee specialist. Thus, according to canon, the necro's melee game should be dramatically better. Poison dagger has been made to reflect this.

Poison dagger can now be used with swords (no different than daggers) and polearms (to match the HotS necro that uses a scythe) and should probably get a name change to "Poison blade".

TODO: update the name and description to "Poison blade".

TODO: necros can dual-wield scythe and dagger.

Poison dagger mana cost reduced by half (from 3 to 1.5). Since poison dagger is a "direct combat spell", damage has been increased and duration decreased. This makes poison dagger dramatically stronger.

At level 1, poison dagger now does 9-18 poison damage per second over 1 second (up from 3.5-7.5 per second per 2 seconds). At level 2, 12-21 per second, at level 3, 15-25 and so on. At the same time, poison duration increases by .2 seconds per level, which makes the damage progression increase quickly. Actually, it now uses the same damage calculations of poison explosion, only that the poison duration is shorter (as PD is intended to be inflicted multiple times on the same enemy).

Note that even though the bonus appear huge for elemental attacks, this should still be smaller than elemental damage bonuses on most fighter classes, because fighter classes do instantaneous damage whereas poison goes through diablo's complicated poison stacking algorithm. In other words, 10 hits from 1-50 lightning damage will do an average of 255 damage. 10 hits from 1-50 poison damage over 2 seconds should do 255 poison damage, however, if stacked with different durations of poison may do more or less than the average damage.

### Teeth
Originally, teeth was a waste of skill points. It doesn't have to be that way.

First, let's compare it to the rest of the necromancer's missile spells. The necro already has a crowd control piercing technique for handling lines. He also already has a single target large damage attack.

While teeth appears to be a crowd control skill, it does too little damage to matter unless you dump all your skills into it. So we need to raise damage somewhat: teeth damage progression is increased significantly, starting from 2-5, and adding 1-2 damage per level. Furthermore, bone spell synergies are increased to 20%, so teeth gets somewhat more damage from higher level spells.

More interestingly, I removed the "Next hit timer" flag on teeth, which prevents an opponent from getting hit by multiple teeth at a time. This turns teeth into a "shotgun" type weapon, a mix between bonespear crowd control (from far away) and bone spirit heavy damage (from up close).

Teeth range and speed also been increased by half, allowing it to hit further.

## Paladin
### Offensive Elemental Auras
The offensive elemental auras do 2 things: splash damage, and attack damage.

For all of the elemental auras, the splash damage sucks tremendously. Holy fire, for example does 1-3 damage every 2seconds. Holy shock does 1-10 damage every 2 seconds. At higher levels, neither of these are strong enough to even hitstun enemies. Thus both tend to be used for the additional elemental damage to attack.

However, since the additional attack damage depends on the aura damage, the bonus still sucks. And as both fire and lightning tend to be used primarily for damage, there is no difference between either one save for the elemental boost. Heck, even with the elemental boost, holy fire is so far below holy shock that you'd probably still be better off with holy shock on lightning resistant enemies.

The offensive elemental auras are now rebalanced.

First, holy fire. Throughout the game, fire is often used for consistent area or splash damage. Thus, holy fire should trigger more often than holy shock - holy fire now triggers every second (instead of every 2) and starts off at an average of 10dps (4-16), increasing by 6 damage per second per level (exponentially increasing). Holy fire's attack damage modifier, however, is double its aura damage (20 dmg), since fire spells do more damage to their main target.

Next, holy shock. Unlike fire, lightning is often used to represent highly variable damage, with a chance of doing larger damage. Thus holy shock only triggers once every 3 seconds, but it does a wider range of damage, 1-36. This does an average of 6dps, increasing by about 6 damage per second per level (exponentially increasing). Holy shock adds its elemental damage to attacks unmodified (1-60), since lightning spells do the same damage to all targets, however, since the base damage is much larger, the bonus damage it deals to the paladin's main target is higher.

Then comes holy freeze. Holy freeze aura damage was simply multiplied by 5, so that the aura damage is equivalent to the previous bonus elemental damage, this means it starts off at 12.5 damage per second and 5.5 damage per second per level (exponentially increasing). Holy freeze adds its elemental aura damage to its attacks unmodified (10-15), since cold spells do the same damage to all targets.

With the damage gap between the elemental auras being significantly decreased, each aura now plays up the strategic value of its element and paladins are more free to choose elemental auras based on their effect rather than pure damage. Holy fire is best against larger groups of weaker enemies as it does steady splash damage to all - this is supposed to be the original intention of Fire Golem's aura, but since Holy Fire is so pathetic by the time it comes out, a lot of necromancers simply don't bother with the higher level golems. Holy shock is best against smaller groups of tougher enemies that holy fire don't drop, because at least holy shock has a chance of hitstunning several of them. And holy freeze is best used for even tougher enemies than the above, because at least you slow everyone.

But wait, there's more. It takes too many skill points in the offensive auras to make them "not useless", and you have to decide way too early. Thus all the elemental auras are made synergies of each other. After all, they're all similar to each other skill-wise. Thus a holy fire paladin can pivot to holy shock or holy freeze without too much regrets. They also get synergies from Vengeance (which adds elemental damage to attacks).

TODO: add synergies to vengeance based on holy auras




# Miscellaneous
## Shrines
Shrines make the game easier to fly through, but they last too short. All shrine durations (except the experience shrine) have been increased by 5 times, whereas their reset times were all set to 1 minute.

Resist boosts have been increased from 75% to 120% so that they give greater effect on Nightmare and Hell.
