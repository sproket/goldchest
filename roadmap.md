# Roadmap

Version 1.0.0.4

* New UI uplift! Cleaned up user interface styles in various screens.
* Refresh Player character Icons supporting a gazillion combinations
* Added new options for player icon definition - size, colors, clothes
* Fixed various icon related bugs
* Changed Spell teamOnly to allow monsters to cast spells like heal on teammates
* Added some new Monster sounds
* Added Mass Heal spell (area same as fireball)
* Added special attack to Abilities (allows for critical hit etc...)
* Added Shocking Grasp spell
* On Windows the Game will properly restart on everyone dead (Mac todo) 
 
Version 1.0.0.3

* Update to Java 22 and JavaFX 22
* New Preferences screen to save Spell selecting (or typing code) and Combat Speed
* New "Death" graphics and animations. Tall and Normal size fall over, Big and Long sizes squish slightly 
* Cleaned up Abilities to use simple expressions for dependencies
* Added Extra keys for combat moves for users without numeric key pads
* Cleaned up combat menu to be less confusing.
* Fixed lost teleport feature where you tp inside a block or wall. Need to kill and set the character to team 0 so they can't be healed. SAME WITH SUMMON
* Fixed spells that fail due to death enlarge into a monster or wall or teleport into wall leave the player magic tile showing and once they are revived they don't show using weapon
* Fixed dead players at start of combat should be sideways
* Fixed dead players should be sideways in player screen
* Fixed tall monster falls on another player/monster - they may take damage when we roll against agility. Prevent death if damage > hp then set hp to 1.
* Fixed dead player revived needs to rotate properly up. Same with All Sizes.
* Fixed What happens if heal target is revived while other living monster/players are standing on them? They will be healed to 0 HP and remain down with a message "cannot be revived"
* Fixed Shield to use Resource image the same way as other Items
* Fixed disguise as monster we should then change it to skull image and set team 0, so it can't be revived at this point. (This is to prevent revive on a stolen monster corpse and to indicate that they can't disguise from this corpse again)

Version 1.0.0.2

Changes 

* Fixed errors with Character creation
* Fix Guarding
* Set monsters with range weapon to use it at start
* Added disguise and loot to the combat menu to see if we like it
* Change startup to reset data.
* Fix player getting scared when moving and continuing their attack rather than fleeing
* Added Preferences for AnimationRate Press + to speed up, - to slow down
* Replaced data section in terrain maps to use Tiled tmj files to make it easier to add new terrain areas
* Added REST in Camp - Rest requires rations for players to heal and restore mana, If a player has Hunting ability they'll get rations added to their items automatically
* Allow/disallow camping in regions 
* Initiative checks - Monsters may surprise the party, party may surprise monsters
* Thief can Trade items in combat only up to a certain distance apart
* Rename Invoke to Cast
* Camp added Honing stone usage. If you have one it will restore some HP to your melee weapon until it wears out.
* New WorldBuilder for designing maps 
* Randomized coins found after combat
* Defined combat round to constant of 20 minutes.



