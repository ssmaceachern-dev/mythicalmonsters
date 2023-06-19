# The Natural World
The purpose of this section is to explain portions of the natural world in relation to the game itself.

## Natural Damage

Natural Damage represents the range of natural damage types that can be found in the Natural World. Unlike Physical Damage, which comprises Slashing, Piercing, and Bludgeoning, Natural Damage inflicts wounds and conditions.

**Fire** - Creatures that take Fire damage receive wounds equal to the level of Fire produced and gain the Burning condition equal to the level of Fire.

**Cold** - Creatures that take Cold damage receive wounds equal to the level of Cold applied and receive the Freezing condition equal to the level of Cold.

**Acid** - Creatures that take Acid damage receive wounds equal to the level of Acid applied. If the level of Acid is more than a creature’s Armor Set’s Natural Resistance, then the creature selects a piece of the Armor Set and reduces its quality equal to the difference.


## Vision

Light in Mythmaker is either illuminating or hindering depending on the creatures interacting with it. Fully Hindered indicates that any Test made during Daylight or Night for a given creature is hindered by 6. Torchlight or any light source that casts a radiance allows a creature with Common or Far Sight to act normally as long as they stay within the zones illuminated by the light.

Actions made within an unlit zone are hindered by six. However, Actions made against creatures or objects within a lit zone do not suffer the same penalities as long as the creature performing them can influence the zone such as with ranged weapons or supernatural effects.

| Vision       | Daylight       | Night          |
| ------------ | -------------- | -------------- |
| Common Sight | --             | Fully Hindered |
| Dark Sight   | Fully Hindered | --             |
| Far Sight    | --             | Fully Hindered |


### Land

In the world of Mythmakers, there are fifteen types of terrains: **Open, Canyons, Forests, Tundra, Hills, Jungles, Deserts, Oasis, Mountains, Marshes, Swamps, Rivers, Valleys, Urban, or Underground.**

In each Land is a variety of obstacles that can obstruct movement, restrict vision, or even test one’s fortitude in the form of its climate.


## Falling

Falling is one of the most common hazards associated with Perils. When a creature falls, the scene immediately transitions into an Engagement.

Because Falling is a result of a natural force, any movement from falling takes place during the World’s Turn upon which they descend one zone's worth of movement. If the creature descends into a zone with a floor, then they will receive physical pressure equal to the number of zones they moved between multiplied by their Size rating.

An able creature can attempt to resist some of the physical pressure by making a **Finesse Test**. If the physical pressure exerted is enough to surpass the falling creature's Health rating and remove all vigor afterwards immediately dies from the impact.


## Stealth 

Stealth in Mythmaker is a developing contest between the creatures in stealth and their quarry. For the purposes of describing how Stealth works, the creature in stealth will be referred to as a Rogue and the creature on the other side will be referred to as an Observer.

A Rogue begins Stealth by making a Finesse Test. The result of this Test acts as the creature's Stealth rating as they move around a location and shift between areas. During Stealth, a creature uses their Move Actions to shift from one location to another as if they were using Local Actions. 

For example, the tavern below would serve as a Location that contains multiple areas within it.

>A target the party is after has been discovered to be hiding somewhere within a tavern. A member of the party becomes a Rogue and makes a Finesse Test to begin stealth.



<div align="center">
<img src="images/engagement_map_example.png" width="100%">
</div>


If a Rogue enters a location that also contains other creatures, then their Stealth Test is measured against the flat Sense ratings of the creatures within the location.

An Observer begins Stealth in the state *oblivious*. They are unaware of the Rogue and go about their rountines as normal. A Rogue in this situation is *undetected* and gains the following abilities:
- An undetected Rogue gains the ability to start an Engagement and initiate a Surprise.
- An undetected Rogue gains enhancement on the first Contested action they take equal to their current Stealth rating.

A Rogue's actions while in stealth consume Move Actions. Recall that the Explore a Location action grants a character Move Actions equal to $Endurance + Size$. With these Move Actions you can perform the following Stealth Actions.

|Stealth Action|Description|
|-|-|
|Move into Adjacent Area|Spend a Move Action while in Stealth to move from one Area to an adjacent Area|
|Interact with Area|Spend a Move Action to Interact with an Object in the current Area. Make a new Stealth Test|
|Hide|Spend a Move Action to take cover or move into an available hiding spot. Make a new Stealth Test against an Observer's Sense Test. If you succeed, then you can spend a Local Action to reduce the level of detection from Wary to Oblivious or you can spend a World Action to reduce the level of detection from Alert to Wary|

### Stages of Detection
|Awareness|Description|
|-|-|
|Oblivious|A stealthing creature can start an Engagement with a surprise. Stealthing creatures can use their Stealth rating as Enhancement on their next action if they start an Engagement|
|Wary|A stealthing creature cannot start an Engagement with a surprise. The observing creatures are now aware of a potential presence nearby. Stealthing creatures can use their Stealth rating as Enhancement on their next action if they start an Engagement. The observing creatures can start a Detect Contest. The stealthing creature must invoke their Finesse rating while the observing creatures invoke their Sense rating. If the observing creatures succeed the Contest, they learn which zone|
|Alert|A stealthing creature cannot start an Engagement with a surprise. Stealthing creatures cannot use their Stealth rating as Enhancement on their next action if they start an Engagement.|

If multiple creatures are in stealth together, then all creatures must make a Finesse Test. The creature with the lowest result represents the group as the group moves around a location. If a Detect Contest is started, every creature in the group needs to make a Finesse Test with the lowest acting as the result against the Sense Tests of each member of the observing group.