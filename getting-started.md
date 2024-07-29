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

## Starting a game

Once the game starts you can create some characters. I don't have any limit on how many characters you can
add to your party, but I've been usually playing with 4.

Once you begin you'll find yourself in the wilderness. There's a sign nearby where an old man 
says something. If you head south you'll find the town.  While at level 0 you won't get any 
random monster encounters.  

Once in the town you can find a general store to your left along the south side. Pick up a compass 
and a map of the town to help you navigate around. There are many shops and places to visit here. 

Wander around to find the guilds to train up to level 1.  You may want to learn basic cartography and 
a weapon skill matching your startup weapon.




Movement

In the 3d view use the normal keys to move around. I have a new feature to allow angle movements as well but not everywhere since it's just an idea for a new feature. 
In combat all the directions are supported.

Leveling
Currently I use 4 core classes: Fighter, Thief, Cleric and Mage. Characters start at level 0 (with gold and some equipment) and can freely choose any combinations when leveling (up to 20 levels total available).

Each of these classes has a guild for training and leveling. Characters can use any guild for common ability training. The Cleric guild is the temple.
Some abilities depend on others so you need to decide. The guild shows you what's required when you try training.

Fighters gain attacks every 3 levels, clerics and thieves every 4 and Mage every 5. (you get *2 when you are enlarged or hasted)
Shops
Fighter Guild - where to train fighter abilities.

Thief Guild - where to train thief abilities.

Mage Guild - where to train mage abilities. Also can recharge mana points for money.

Temple - where to train cleric abilities. Also can heal players for money.
Armory - buy and sell equipment.

Blacksmith - buy, sell and repair equipment which usually is not 100% best condition.
General Store - buy and sell some general items (all will be useful eventually but some are not yet useful).

Taylor - buy, sell and repair cloaks, robes and leather items.

Tavern - place to hear rumors and recruit new NPC characters to join your party if you wish.

Inn - place to rest (health and mana slowly restored for 1 gold per day).

Jeweler - buy and sell gems and jewels.

Bank - store money and items. Also, you can take loans if you're strapped for cash.
Spells

Currently, spells "work" but the magic system is not completed.  Any character can cast any spell as long as they have mana points. This is in-progress.

How I want it to work (let me know what you think):

Mage

Mage class can train for any 4 basic magic classes Conjurer, Magician, Enchanter, Illusionist.

Once they have those they can train on the higher level magic classes: Wizard, Sorcerer.

Finally, once they have that and are at level 20 they can train on Necromancer.
Each would have separate spells in their "spell book".

Cleric
Clerics gain spells at temples if they are "worthy". Still to think about...

Current spell list:

duration in minutes
<pre>
Code    Range      Duration     Spell

fiba    6.0        0            Fireball
heal    6.0        0            Healing
suwo    6.0        0            Summon Wolf
enla    6.0        0            Enlarge
mami    6.0        0            Magic Missle
feeb    4.0        10           Feeble mind
stcl    6.0        60           Stinking Cloud
hast    1.0        720          Haste
poss    6.0        30           Possession
subd    6.0        0            Summon Black Dragon
sudf    6.0        0            Summon Giant Gold Dragon Fly
tepo    8.0        0            Teleport
fear    1.0        20           Fear
refe    6.0        0            Remove Fear
stre    1.0        720          Strength
disp    6.0        0            Dispossess
</pre>

Combat

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

Characters automatically guard when they end their turn as long as they haven't casted a spell or are using a ranged weapon.
This means they will get a *single* melee attack if an enemy moves within their melee range.
Training this ability means the character will continue guarding even after doing that attack.
In addition the the melee attack will only use 1 move point rather than the usual 2 points.


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
of grabbing items/money from monsters when the character does a melee attack.


##### Looting

Thieves learning the art of looting may collect items/money from dead monsters in combat.

##### Disguise

Thieves learning the art of disguise may opt to disguise as dead monsters in combat. Disguised characters
are ignored by enemy monsters. The disguise is lost when doing a melee attack.


##### Infiltration

High level thieves may study the skill of infiltration. Infiltration is an advanced form of disguise
allowing the character to disguise as any monster type or size. In addition the character
will have a higher chance of maintaining this disguise even when doing a melee attack.

##### Back stab

Thieves learning the art of back stabbing will double their melee attack damage when striking an opponent from behind.




