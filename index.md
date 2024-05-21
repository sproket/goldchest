# Goldchest

So goldchest... Where do I begin?
I started to think that it would be cool to have some kind of Pool of Radiance type game but modernize it with 3d graphics etc.. Also I want to implement ideas I've seen in other old era games where it makes sense (some Bard's Tale concepts see below for example).
So currently you'll see that in the 1st person view it's 3d with support for lighting, sky textures, animation and even 3d models! Some of this is not implemented yet but it can be. Also I have positional sound working so you'll hear shops in the distance.

## Installing

There's no installer required for this game. Just download the ZIP appropriate for win or mac then unzip. There will be a goldchest folder and .exe or .app to run.

The game creates the data files in your home folder/goldchest - you can look at the CSV files there if you want to right now. The actual data is stored in a local database.

Also I log any errors to your home folder/logs/goldchest.log (hopefully you won't have any!).

## Status

* What works
* What Doesn't work
* What needs work
  


## Getting Started

Once the game starts you can create some characters. I don't have any limit on how many characters you can add to your party but I've been usually playing with 4.
Once you begin you'll find yourself in the wilderness. There's a sign nearby where an old man says something. If you head south you'll find the town.  While at level 0 you won't get any random monster encounters.  Once in the town you can view the map (which doesn't show much yet). Wander around to find the guilds to train up to level 1.
D&D

Early on I decided that I don't want to be committed to D&D rules although I do reference some of it for monster levels etc.. Monsters may surprise you though as they have other abilities.  I'm using 100 based numbers rather than 18. 100 is max human level for your reference when rolling.

Movement

In the 3d view use the normal keys to move around. I have a new feature to allow angle movements as well but not everywhere since it's just an idea for a new feature. In combat all the directions are supported.

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

Tavern - place to hear rumors.

Inn - place to rest (health and mana slowly restored for 1 gold per day).

Jeweler - buy and sell gems and jewels.

Bank - store money and items. Also you can take loans if you're strapped for cash.
Spells

Currently spells "work" but the magic system is not completed.  Any character can cast any spell as long as they have mana points. This is in-progress.

How I want it to work (let me know what you think):

Mage

Mage class can train for any 4 basic magic classes Conjurer, Magician, Enchanter, Illusionist.

One they have those they can train on the higher level magic classes: Wizard, Sorcerer.

Finally once they have that and are at level 20 they can train on Necromancer.
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

There are a variety of pre-fab combat encounters that once you find, you can go back to as they reset when you enter the same area again (for now). For now you can always exit combat and "win" by choosing "END" in the combat menu. (easier for leveling up testing)
There also random encounters which are tuned to your number of players and average level so combat will always be challenging.
This game is currently "ALPHA" so it works but there's a lot left to do!
Here's the link to discord:

https://discord.gg/ghH4Xax9

Here's the link to my google drive for the game.

https://drive.google.com/drive/folders/1yCDbpk-SzlknAbJb_u4BQY_NWQScRyPT

