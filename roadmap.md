# Roadmap

## Version 1.0.0.6

### Features

* UI: Treasure screen with PgUp and PgDown rather than long list
* UI: Progress bar shows for long-lasting spells and for torch or lantern
* Combat: Thrown weapon if damaged it will not return to the player
* Game: Item lore ability shows condition of items in your inventory
* UI: Multiple light sources
* Game: Player Spell Settings for combat to define spells a player may want to use in AUTO-mode (MANA Menu)
* Combat: Thieves may loot a downed player
* Game: New spells and spell books
* Combat: New monster sizes VeryTall, VeryLong, VeryBig
* Combat: New sizes for spells: large (3x3) and very large (3x3x3) area of effect
* Game: new Level up and training sounds
* Combat: Spells can fail and even backfire
* Game: USE magic item (scroll, potion etc)
* Game: Scroll can be memorized - allowing a non-magic class to learn to use a spell
* Game: Player statistics: Hits, Misses, Kills, Spells cast, failed, backfired, Ability uses count
* Game: Spell Defences (Defence, Protection, Immunity and Benefit) for various "force" types
* Combat: New monsters: Bear, Rats, Brownie, Goblins, Bugbear, Orcs, Kobolds, Gnoll...
* Combat: Illusionary monster spells and new Orb of Fear spell
* Combat: Arena animated messages
* Combat: Added animation to special attacks


### Fixes
* Guarding updates (subtract only 1 on melee attack), Track player moves fixes, update for CloseProximityFormationStrategy, fix ability training reason messages, fixed AttributeCell when table scrolls, text panel scroooool again, update POM.
* Updates to some items hit points, Aim cost in AI mode, limit game to 9 players, Initial non scrolling treasure list, FIXED YesNoMenu CALL IN THE CORRECT ORDER.
* Pagination for Treasure screen, minor update to item displayName, unequip monster items at the end of combat.
* PageUp and PageDown implementation
* Thrown weapon if damaged it will not return to the player. Fixed YesNoMenu. Fixed Condition calc.
* Fix money canCarry check Added Item lore items colors for item HP and expiry.
* Progress bar for spell effects and torch, EffectsPanel refreshes for monsters in combat (showing if they have spells on them), added affected by spell list to text when looking at monsters in combat,
* handle multiple light sources
* Player spell settings for CombatAI (p1), fixed Enlarge casting and failing and casting again, pwned when looted, fixed ESC with NPC in combat.
* NPC and auto spells P2 (oneCastPerCombat), Fixed sort players in startup.
* Thieves can loot downed players. Fixed guarding when using ability, Added Firebolt spell, Fixed END turn removing moves.
* Interactive panel improvements.
* Remove levelMultiplier on Spell (since it's on SpellEffect instead)
* Fix items being used even if they were banked, hide background now before combat (use splash as background).
* Tidy up some texts for Table when empty.
* New sizes: VeryTall, VeryLong, VeryBig
* Large size spells.
* Show player attributes and max attributes on player panel.
* Fixed spell data, fixed width on player panel.
* Professions in table (1st pass)
* Professions in table. Fixed some abilities, Got rid of equals/hashcode requirements on Observable objects, made Mover generic, fixed repl spell, fixed abilities affecting armor class, Recruit using new table data.
* Spell Book.
* Make spell casting using known spells, Use First Aid.
* Cleric Spell Book.
* Level up and training sounds.
* world building new town. Fixed back stab should allow keeping disguise if you have back stab ability,
* Admin fixes, SpellResults fail and backfire (1st pass),
* SpellResult revert, spell fail test in rules, added onBeginCasting for better msg,  saved caster in SpellTile to know who casted afterward (stinking cloud type spells), sound with cast in camp,
* Backfire 3rd pass, fix targets, fix script logging, added spells to spell book.
* DB cleanup deprecated columns DexterityClass and Gender, Added Status to PlayerPanel, fixed Roller refresh.
* Arrow rotation can be precisely calculated rather than using a specific direction value
* Orb of Fear
* Fix scroll in select panels, Fix TextPanel replaced with ScrollPane.
* Replicate Item in dbAdmin, Fix disguise when you have back stab, Fixed Select panel + others for scrolling.
* Added spellId to Item, Fixed Targeting AGAIN, Confirm exiting treasure screen, Added Using magic item.
* Scroll item added, PlayerKnownSpells added.
* PlayerKnownSpells stats, clean up combat move CastSpell, Cleric spells, Clean up recruiting.
* Player spell stats and display of spell books.
* Ability stats, fix script menu context, Throw ability check.
* Smarter moves when area spells are in combat, implemented attribute increase when leveling up, Combat changed to 1 minute per turn (to play and experiment with it), RANDOM, Automatic signs for shops, fix exceed max combat rounds.
* Special drops for monsters, Fixed AI range, updates to run away rule, Handle Items not in shop, fixed SCROLLL MOREEEEE.
* Fix ArenaManager.canMove manual move, add max and summoningCount for wabbits, added PASS turn vs END turn, Added GROUP option in treasure list (disabled because still broken), smarter ai moves out of standing spells, refresh player spells based on changes to spellbooks.
* Prevent spells being referenced by more than 1 spell book, Added spellBookId to PlayerKnownSpell, Refresh player spells when spell book is changed.
* Spell Defence.
* Fixed TilePlacer BUG, Updated EffectsPanel to refresh in combat, cleanup common GameCharacter getSpellDefences method, ActiveSpell list in ManaPanel, REMOVED displayNameProperty from IdentifiableObject since it creates objects over and over,
* Spells memorized from Scrolls.
* World building: rename maze1 to grothlore added residential area, added Bear, Rats and Brownie monsters.
* World building: Goblins
* World building: Bugbear
* Spell casting mode to allow magic spell to be cast from an ability or item. Added Orcs.
* Fix up getSpellResultMessage, Fix spell panel selecting players and escaping (re-select initial player), Damage monster equipment, Fix spell manager isInCombat test, made PlayerKnownSpell observable, Fixed resetting player spells when spell books are edited.
* POOL and REDISTRIBUTE, Kobold and Gnoll.
* Gnomes.
* Clean up MENUs FINALLY. CombatManager just sticks to a current CombatMenu, FIXED Mana going into minus.
* fix show messages on revert
* Illusionary Monsters Phase I.
* Combat Messages, remove the possession on targetDown
* Fix ability stat for auto spell. Added animation to special attacks,



Version 1.0.0.5

* New Time of Day lighting and dark areas (dungeons) ready your torches and lanterns 
* Added NPC Player recruitment option at tavern
* New UI colorized texts in the player list panel
* Added Tactics ability in Fighter Guild which adds "AREA" menu in combat to see an overhead view
* Added swimming ability and areas to reach by swimming
* Added Throwing weapons which return!
* Updated Basic Cartography ability - additional features if a player has it and a map of their location
* ENLARGE for mini players is safe since they don't become "tall" (dwarf and hobbit size)
* Added RANDOM to Icon menu to randomize character appearance
* Added Range and Melee to AbilityType which act as special attacks (like critical hit)
* Updated Elfin bowmanship ability to give critical hit chance
* F1 opens web page with documentation
* F2 in combat puts all players in "auto" mode
* Added AI weapon throwing (will not do it if the weapon is not returnable)
* New Treasure chest pic
* Replaced grey lizard with crocodile
* Added Thieves with "Pick pocket" may snatch thrown weapons
* New spell effects graphics
* Improved text panel scrolling
* Enlarged window size slightly for more text and combat space
* Added message when players hone their weapons
* Added new sounds
* Adjusted camera in combat so Icons appear more clearly
* Fix teleport onto your thrown weapon to pick up 
* Put item tiles (for thrown weapons) above other tiles, so you can always see them
* Fix trade in combat changing selected character
* Fix game loading duplicating spell effects
* Fix goes down! message (wrong order)
* Fix WEAPON menu appears, but you can't change weapon because no ammo

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



