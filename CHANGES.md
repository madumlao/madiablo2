# Drop Rates
## Nodrops
A "nodrop" is a treasure class that drops no treasure. Each monster, chest, etc that has been assigned a "nodrop" has a percentage chance that it does not drop anything. Most bosses and chests actually "drop" multiple items, however, some of those drops are "nodrops" and so they don't always drop the maximum number of items.

Nodrops have been removed from chests.

Nodrops have been removed from superunique monsters.

Nodrop ratio has been reduced in ordinary monsters from 100 to 64.

## Item Ratios
Adjusted item ratios to make Uniques, Rares, and Set items significantly more common.

## Gems
Gems are used in a lot of recipes, and in and of themselves as equipment buffs. But not only are gems themselves rare, but you can hardly get the right one.

Gems drop rates have been significantly increased by adding them to the "junk" class of tresure (that spawns scrolls, keys, arrows, and bolts). In Act 1, gems will drop at about 1/4 the rate of arrows and bolts. From Act 2 onwards, they drop at roughly 5/8 the rate.

From Act 2 onwards, 2 kinds of gems drop: one of lower quality and one of higher quality (one grade above the current). The lower quality gem drops 80% of the time, the rest is the higher quality gem. In Act 2 this is chipped and flawed. In Act 3 it's flawed and normal. In Act 4 it's normal and flawless. Then in Act 5 and all higher difficulties, it's flawless and perfect.

## Runes
Runewords are one of the few ways of getting higher-level gear that the player has any agency over. However that agency is largely overshadowed by how difficult it is to even get a rune, much less the right ones.

Runes are very rare drops in the original game, so I increased their drop rate. Runes now spawn from "good" drops (usually higher level chests or monsters) at a comparable rate to rings, amulets, and charms, taking the place of gems being dropped.

Furthermore, rune drop rate has been adjusted. Runes used to drop in 2 classes (like gems above), with the lower class rune dropping much more than the higher class rune. HOWEVER, the probability gap between the two increases exponentially with the higher rune levels. At the highest rune levels, the disparity between the 2 classes is so huge (the highest one dropping at less than 1/10000) that the only way to get higher level runes is to trade for them.

Here the probabilities have been adjusted to saner levels. The higher level runes are still harder to find, but in probabilities like 1:6 or 2:7.

## Superuniques
Superunique monsters (such as Act bosses, quest bosses) no longer drop magic items. Instead they only drop Rare or higher.

# Horadric Cube Recipes
## Rejuvenation potion
3 health potions + 3 mana potions = 1 rejuvenation potion (gem no longer needed).

## Full Rejuvenation potion
6 health potions + 6 mana potions = 1 full rejuvenation potion (replaces the 3 health, 3 mana + normal gem).

# Skills
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

Plague Javelin is weaker in absolute damage, but it hits more enemies with poison and lasts longer. Poison Javelin

## Necromancer
### Skeleton Mage (aka necromage)
Poison Necromages used to a do a ridiculous "1 dmg every 10 seconds" crap, and levelling them up increased the duration by a further 10 seconds. This is insane. Basically if you spawn a poison necromage, despawn it immediately and replace it with fire.

Poison Necromage has been updated to be comparable to other necromages. It now does 4.875 damage per second for 1 second, compared to cold (1-4), fire (2-6), lightning (1-7). Higher levels increase the damage by about 1.5 per second, but also increases the poison duration by 1/5 of a second each, compared to the other elements which increase average damage by 2, or cold by 1. This makes poison _slightly_ stronger than the other elements, but it takes slightly longer to deal its damage.

## Poison Dagger
Poison Dagger is almost universally recognized to be an underwhelming skill, in part because daggers are underwhelming. In Blizzard's "Heroes of the Storm", however, the Diablo2 necromancer is represented as a melee specialist. Thus, according to canon, the necro's melee game should be dramatically better. Poison dagger has been made to reflect this.

Poison dagger can now be used with swords (no different than daggers) and polearms (to match the HotS necro that uses a scythe) and should probably get a name change to "Poison blade".

TODO: update the name and description to "Poison blade".

TODO: necros can dual-wield scythe and dagger.

TODO: scythes can auto-add necro skills.

Poison dagger mana cost reduced by half (from 3 to 1.5). Since poison dagger is a "direct combat spell", damage has been increased and duration decreased. This makes poison dagger dramatically stronger.

At level 1, poison dagger now does 9-18 poison damage per second over 1 second (up from 3.5-7.5 per second per 2 seconds). At level 2, 12-21 per second, at level 3, 15-25 and so on. At the same time, poison duration increases by .2 seconds per level, which makes the damage progression increase quickly. Actually, it now uses the same damage calculations of poison explosion, only that the poison duration is shorter (as PD is intended to be inflicted multiple times on the same enemy).

Note that even though the bonus appear huge for elemental attacks, this should still be smaller than elemental damage bonuses on most fighter classes, because fighter classes do instantaneous damage whereas poison goes through diablo's complicated poison stacking algorithm. In other words, 10 hits from 1-50 lightning damage will do an average of 255 damage. 10 hits from 1-50 poison damage over 2 seconds should do 255 poison damage, however, if stacked with different durations of poison may do more or less than the average damage.
