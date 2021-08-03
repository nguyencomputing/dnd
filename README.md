# Dungeons and Dragons with Python
## A text-based adventure game based on Dungeon and Dragons 5th Edition.
This game is my final project for the Coding 101 Summer Programme by Tufts University and the time constraint has led to most of the stats and abilities as well as game rules being tweaked to get an MVP (Minimal Viable Product) submitted on time but these will be reverted slowly as I spend more and more time working on this project. (**Warning:** Most of the input fields in the program are very susceptible to breaking if given invalid data so please follow the guidelines and hints provided!)

## Races:
### Aarakocra 🦅:
* **Flight** - Unimplemented
* **Talons** - Unimplemented
### Dwarf ⛰️:
* **Darkvision** - Unimplemented
* **Toughness** - Unaffected by movement speed debuffs caused by wearing heavy armour.
### Elf 🧝:
* **Darkvision** - Unimplemented
* **Trance** - Unimplemented
* **Fey Step** - Unimplemented
### Gnome 😁:
* **Darkvision** - Unimplemented
### Halfling 🍀:
* **Lucky** - Whenever you roll a 1 on an attack roll or death save, you have to reroll and keep the new roll.
### Half-Orc 😤:
* **Darkvision** - Unimplemented
* **Savage Attacks** - Unimplemented
* **Relentless Endurance** - Unimplemented
### Human 👨:
* **Extra Language** - Unimplemented
### Tiefling 😈:
* **Darkvision** - Unimplemented
* **Infernal Legacy** - Unimplemented
## Classes:
### Barbarian 😡:
* **Rage** -  You can enter a rage as a bonus action. When raging, you have advantage on Strength and Constitution saving throws, you gain a +2 bonus to melee damage rolls and you are resistant to bludgeoning, piercing and slashing damage. Your rage lasts for 3 turns and you can rage a maximum of 2 times before needing a long rest to rage again.
* **Unarmoured Defense** - While you are not wearing any armor, your Armour Class equals 10 + your Dexterity modifier + your Constitution modifier. You can use a shield and still gain this benefit.
### Bard 🎸:
* **Spellcasting** - You can cast spells. 
* **Bardic Inspiration** - Your targets will have disadvantage on saving throws when trying to resist your spells and cantrips. 
### Cleric ⛪:
* **Spellcasting** - You can cast spells.
* **Divine Domain** - Unimplemented
### Druid 🌱:
* **Spellcasting** - You can cast spells.
* **Power of Nature** - Your spells are *naturally*(pun intended) stronger.
### Fighter ⚔️:
* **Dueling** - You gain a +1 bonus to your Armour Class and a +1 bonus to all of your attack rolls.
* **Second Wind** - Unimplemented
### Monk 👊:
* **Martial Arts** - After making an attack with an Unarmed Strike or a monk weapon, you can make an extra Unarmed Strike as a bonus action.
* **Unarmoured Defense** - While you are not wearing any armor, your Armour Class equals 10 + your Dexterity modifier + your Constitution modifier. You can use a shield and still gain this benefit.
### Paladin 🛡️:
* **Divine Blessings** - You have a +1 bonus to your Armour Class
* **Lay On Hands** - You have a pool of healing power that replenishes when you take a long rest. With that pool, you can restore a total number of hit points equal to your paladin level × 6. As an action, you can touch a creature and restore a number of hit points to that creature, up to the maximum amount remaining in your pool.
### Wizard ⚡:
* **Spellcasting** - You can cast spells.
## Basic rules:
### Attacking:
Weapons are either ranged or melee, only ranged weapons can be used if the target is further than 0ft from you.  To attack, you must first roll an attack roll which has to be the same or higher than the enemy's Armour Class to 'hit' them, else you will miss. You will only roll the damage roll when your attack hits. 
#### Melee Weapons:
These weapons can only be used when the target is right next to you.
#### Ranged Weapons: 
These weapons can be used at any time regardless of the distance between you and the enemy but you will have disadvantage on your attack roll if your target is further from the *suggested* range of your weapon or your target is within melee range.
### Casting Spells:
Spells are divided into two categories: cantrips and 1st-level spells. There are two ways of determining if a target takes damage from a spell; the first requires the caster (you) to make an attack roll against the targets Armour Class and the second requires the target to make a saving throw against your spell to try and resist it. When the target is further than the range of the spell, either the caster (you) will have disadvantage on your attack roll or the target will have advantage on their saving throw against the spell depending on the nature of the spell. 
#### Cantrips:
These are less powerful spells which do not consume spell slots and can be casted as many times as you wish.
#### 1st-Level Spells:
These are more powerful spells which consume spells slots regardless if they hit or not and the spell slots (2) can be regained by taking long rests. 
### Moving:
On your turn you can move a distance up to movement speed in feet and can either move before or after taking your turn, you can also spend a **Dash** action to double your movement speed. However, you can only move travel distances that are a multiple of 5. (I am working on the option to break up their movement speed and allow them to move after taking their action if they still have movement speed left over!)
### Resting: 
There are two types of rests in the game, short rests and long rests.
#### Short Rests:
These rests do not require you to travel back home to rest and is when you can spend your hit dice to heal, some abilities will also reset after taking a short rest. 
#### Long Rests:
These rests require you to travel back home to rest and does not only heal you back up to full health, restore half of your spent hit dice, restore all of your spell slots but also reset all of your abilities. 
