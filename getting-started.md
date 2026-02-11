# Getting started

Note about D&D rules

Early on I decided that I don't want to be committed to D&D rules, although I do reference some
of it for monster levels etc.. Monsters may surprise you though as they have other abilities.  
I'm using 100 based numbers rather than 18. 100 is max human level for your reference when
rolling.


## Game User Interface

Goldchest keeps to the old skool keyboard user interface. Use left and right arrow keys to 
navigate the menus, press `<enter>` to select the option. Use the up and down arrow keys to 
highlight different players in your party or to highlight items in your inventory or items from 
stores etc... You can also press the highlighted letter in the menu to select that menu option.

Mouse wheel is also supported for scrolling if needed. 

A numeric keypad is recommended for combat to move at angles, although you can use following keys
as well:


    Q W E   U I O
    A   D   J   L
    Z X C   M , .

## Creating Characters

Specify the charcter Name, Sex and Race. You can Roll as many times as you want until you find attributes you like.

Chose some startup items and update your character icon and then save the character.

Characters start at level 0 and have no profession.

Once you have a set of characters you like, add them to the party and begin the game. 

### Character Attributes
      
Attributes are random between 10 (really bad) and 100 (max human). 

#### Strengh

Primary attribute for fighters. 
Higher strengh means doing more damage in combat and allows the character to carry more items. 
It also helps with other areas of the game like bashing locked doors.  

#### Agility

Primary attribute for thieves.
High agility means more combat moves and a better chance to move earlier. 
It also helps with other areas of the game like disarming traps, pick pocketing, etc.    

#### Intelligence

Primary attribute for mages. 
High intelligence gives the character more mana per level and increases the chance of success with spell casting.

#### Wisdom

Primary attribute for clerics.
High wisdom gives the character more mana per level and increases the chance of success with cleric spell casting, healing and turning undead.

#### Constitution

Constitution gives the character more hit points per level and provides some resistance to magic and other negative affects.

#### Charisma

Charisma affects how other NPC characters interact with the character.  Higher charisma lowers prices at various shops. 

### Character Races

#### Human

Stock standard human. No additional bonuses when rolling.                   

#### Elf

Fairer and taller than humans, elves tend to be smarter and more agile. 

#### Half-Elf

Nice combo of humans and elves.

#### Halfling
               
Small in stature, strong in heart. 

#### Gnome
                                   
Like halflings but somewhat more chaotic. 

#### Dwarf

Short and stout. Dwarves get bonus strenght and constitution.

## Starting a game

Once the game starts you can create some characters. You may have up to 9 characters in your party, 
but you might want less than that since you can recruit level 7 NPC characters when visiting taverns and have other NPCs join the party.

Once you begin you'll find yourself in the wilderness. There's a sign nearby where an old man 
says something. If you head south you'll find the town.  While at level 0 you won't get any 
random monster encounters.  

Once in the town you can find a general store to your left along the south side. Pick up a compass 
and a map of the town to help you navigate around. There are many shops and places to visit here. 

Wander around to find the guilds to train up to level 1. The character should also learn basic weapon proficiency for their preferred weapon.  

For mages the character should also pick up a spell codex. Conjurer or Magician are availble to start with.

For clerics they should pray to get cleric spells from the temple. 

While you're at the guild someone in the party might want to learn basic cartography which helps with reading the maps and gives you your current coordinate in the area.

#### Movement

In the 3d view use the normal keys to move around. I have a new feature to allow angle movements as well but not everywhere since it's just an idea for a new feature. 
In combat all the directions are supported.

#### Leveling

Currently I use 4 core classes: Fighter, Thief, Cleric and Mage. Characters start at level 0 (with gold and some equipment) and can freely choose any combinations when leveling (up to 20 levels total available).

Each of these classes has a guild for training and leveling. Characters can use any guild for common ability training. The Cleric guild is the temple.
Some abilities depend on others so you need to decide. The guild shows you what's required when you try training.

Fighters gain attacks every 3 levels, clerics and thieves every 4 and Mage every 5. (you get *2 when you are enlarged or hasted)

### Shop Types
              
The game features various places to visit where you can buy/sell various items, interact, etc. 

#### Fighter Guild
Where to train fighter abilities.

#### Thief Guild 
Where to train thief abilities.

#### Mage Guild 
Where to train mage abilities. Also, players can recharge mana points for money.

#### Temple
Were to train cleric abilities and learn cleric spells if you're worthy. Also, players can be healed for money.

#### Armory
Buy, sell and identify equipment.

#### Blacksmith 
Buy, sell and repair equipment which usually is not 100% best condition.

#### General Store
Buy and sell some general items.

#### Taylor 
Buy, sell and repair cloaks, robes and leather items.

#### Tavern 
A place to hear rumors and recruit new NPC characters to join your party if you wish.

#### Inn
A place to rest (health and mana slowly restored for 1 gold per day). 
At the Inn you can also add new characters to the party. 

#### Jeweler
Buy and sell gems and jewels.

#### Bank 
Store money and items. Also, you can take loans if you're strapped for cash.


## Magic Systems

The game features to distinct "magic" systems. One for Mages and one for Clerics.

### Mage

Mage class can train for any 4 basic magic classes Conjurer, Magician, Enchanter, Illusionist.

Once they have those they can train on the higher level magic classes: Wizard, Sorcerer.

Finally, once they have that and are at level 20 they can train on Necromancer.
Each would have separate spells in their "spell book".

### Cleric

Clerics gain spells at temples if they are "worthy".  

Current spell list:

duration in minutes
<pre>
Conjurer
Code	Level	Range	Duration	Mana	Type	Spell
fiba	7	6.0	0	20	Fire	Fire ball
fibo	3	6.0	0	7	Fire	Fire bolt
sudf	3	6.0	0	12	Earth	Summon Giant Gold Dragon Fly
suwo	5	6.0	0	10	Earth	Summon Wolf
emel	3	0.0	0	7	Skill	Emergency light
---
Enchanter
Code	Level	Range	Duration	Mana	Type	Spell
enla	5	0.0	0	10	Magic	Enlarge
hast	3	0.0	1440	20	Magic	Haste
itom	2	3.0	0	20	Skill	Immunity from magic
prom	2	3.0	720	20	Skill	Protection from magic
stre	3	1.5	1440	20	Magic	Strength
engl	4	1.0	1440	10	Magic	Enchanted glow
---
Illusionist
Code	Level	Range	Duration	Mana	Type	Spell
fear	4	1.5	25	20	Mind	Fear
feeb	8	4.0	60	20	Mind	Feeble mind
refe	6	6.0	0	40	Mind	Remove Fear
ilwo	7	6.0	0	20	Illusion	Illusionary Wolf
---
Magician
Code	Level	Range	Duration	Mana	Type	Spell
mami	1	6.0	0	10	Magic	Magic Missile
shgr	4	1.5	0	15	Magic	Shocking Grasp
stcl	5	6.0	100	20	Air	Stinking Cloud
sual	1	2.0	0	2	Earth	Summon Horned Rabbit
tepo	7	8.0	0	30	Magic	Teleport
orbl	1	1.0	720	7	Magic	Orb of light
---
Sorcerer
Code	Level	Range	Duration	Mana	Type	Spell
deil	12	0.0	0	60	Mind	Destroy Illusions
ilbd	12	6.0	0	30	Illusion	Illusionary Black Dragon
mafe	8	6.0	60	40	Mind	Mass Fear
glob	7	3.0	720	60	Magic	Minor globe of invulnerability
orfe	6	6.0	60	20	Mind	Orb of Fear
stup	8	4.0	0	40	Mind	Stupify
terr	12	1.5	50	40	Mind	Terrify
mifs	5	6.0	0	7	Mind	Mind Fist
---
Wizard
Code	Level	Range	Duration	Mana	Type	Spell
disp	10	6.0	0	30	Mind	Dispossess
fibl	8	8.0	0	30	Fire	Fire blast
fist	10	8.0	0	40	Fire	Fire storm
poss	12	6.0	720	30	Mind	Possession
stst	8	6.0	200	40	Air	Stink Storm
subd	12	6.0	0	60	Earth	Summon Black Dragon
subl	12	8.0	0	80	Earth	Summon Blue Dragon
sugs	7	6.0	0	20	Earth	Summon Giant Skeleton
icbl	8	8.0	0	30	Cold	Ice blast
---
Necromancer
Code	Level	Range	Duration	Mana	Type	Spell
susg	16	12.0	0	100	Air	Summon Cloud Genie

</pre>

## Combat

There are a variety of pre-fab combat encounters that once you find, you can go 
back to as they reset when you enter the same area again (for now). For now,
you can always exit combat and "win" by choosing "EXIT" in the combat menu. (easier for leveling up testing)
There also random encounters which are tuned to your number of players and average level so combat will always be challenging.
This game is currently "ALPHA" so it works but there's a lot or work left to do!

Spells work like Bards Tale use the CAST menu and type one of the codes in.
Some can be cast outside combat like heal and strength, the others are combat only.

For races there are adjustments to the rolling attributes. Check in your home folder\goldchest\races.csv file. Race may have other effects later on.

To rest, go to an Inn. REST menu will rest characters and restore mana and hp.

Classes are chosen by going to one of the guilds and using the LEVEL menu. You can mix classes in any combination.

Thief guild is at 4,4, Fighter guild is at 13,3, Mage guild is at 13,15, Temple is at 6,12. (I use ROW,COL) I think originally it was COL,ROW which I can fix later.

To get the coordinate of where you are to appear, have someone train for Basic Cartography.

To get the compass to appear buy one at the General Store.

Yeah, at first you have to move around kind of blindly in the town to find things. :)

## Weapons

There are various weapons in the game which have associated abilities (see [Abilities](#abilities)). 
The associated abilities provide bonuses to-hit chance for the player. Once a player has acquired all 
abilities associated with a Melee weapon, that weapon will be treated as though it's a 1 handed weapon
even if it normally is a 2 handed weapon.


## Abilities

### Ability Types

#### Profession

Used to distinguish levels from other abilities.

#### Melee

Used to indicate that this ability may happen when doing a melee attack.
Will include Spell (Special Attack) and Special Attack chance fields.
These do drain some mana. Generally it should be a lower number or zero is OK
because they won't get this special attack if they don't have enough mana.

#### Combat, Other, Skill, Subclass etc...

Not used yet...

#### Special abilities

##### Guarding

Characters automatically guard when they end their turn as long as they haven't cast a spell or are using a ranged weapon.
This means they will get a *single* melee attack if an enemy moves within their melee range.
Training this ability means the character will continue guarding even after doing that attack.
In addition, the melee attack will only use 1 move point rather than the usual 2 points.


##### Botany

Characters trained on botany will be able to identify plants while in combat
since some of those plants may have effects on the character when they stand
on them.

##### Basic cartography

Characters trained on basic cartography will give the party a coordinate while in indoor areas.
Additionally, if an area has a map purchased from a general store, the party will be able to see
extra details on the map like locations of shops and other interesting areas. If the area doesn't
have a map, basic cartography will allow the party to see a small surrounding region of the map.

##### Advanced cartography

Characters trained on advanced cartography will be able to auto-map areas that don't have maps.

##### Advanced throwing .... (missing some for dagger and axe)

In addition to giving some damage and chance to hit bonuses, advanced throwing adds
a possibility of doing a critical hit.

##### Tactics

Higher level fighters can train on tactics. This ability gives the player the
option of seeing an area map of the combat arena.

##### Pick pocket

Thieves may opt to learn the art of pick pocketing. This skill gives a chance
of grabbing items/money from opponents when the character does a melee attack.


##### Looting

Thieves learning the art of looting may collect items/money from dead opponents in combat.

##### Disguise

Thieves learning the art of disguise may opt to disguise as dead monsters in combat. Disguised characters
are ignored by enemy monsters. The disguise is lost when doing a melee attack.


##### Infiltration

High level thieves may study the skill of infiltration. Infiltration is an advanced form of disguise
allowing the character to disguise as any monster type or size. In addition, the character
will have a higher chance of maintaining this disguise even when doing a melee attack.

##### Backstab

Thieves learning the art of backstabbing will double their melee attack damage when striking an opponent from behind.

##### TODO MORE later

## Magic Items

Various magic items can be found throughout the game including weapons, armor, shields, etc. 
These are other common types of items that can be found and how they work.

Some may have negative effects or may be cursed (not able to drop or unequip).

Items appear usually in an unidentified state. You may check a variety of shops to see if they can identify for you.

Characters with certain abilities may identify items automatically.

### Potions

Potions are single use with a variety of spell effects. Some can be used in camp as well as combat. 
They can only be used on yourself.

### Wands

Wands may have multiple uses and require hands to use. You may use them as a melee weapon as well if you're desperate. 

### Scrolls

Scrolls are single use with a variety of spell effects. Some can be used in camp as well as combat. 
Scrolls can also be memorized by players, so they can cast the spell even if they have no magic or spell books.    


### Rings

Rings have a variety of effects that happen when you equip them.

## Cursed items

Items may be cursed. Cursed items have the following characteristics:

* If equipped they cannot be unequipped.  The curse will need to be removed at a temple or by cleric with remove curse spell.
* If unequipped they can be identified and dropped - but they cannot be traded, sold or deposited.
* Usually they will have negative consequences to the character while they are in the character's possession.
* Magic cursed items will usually have a negative consequence if used.
* They do not wear out over time due to use or damage. They can only be removed at a temple.
* Cursed scrolls if memorized will remove spells from your spell books and drain intelligence. The effects will revert once you remove the cursed item.
* Players who are cursed cannot equip any item.
* Cursed weapons will make the character worse on attacks.
* Cursed armor (Armor, Boots, Bracers, Clothes, Gloves, Helm, Shield) will give the character low protection even though it appears the character has protection.

*Note: Items may become cursed if shoplifted.*





