== CREDITS ==
ACE Team for their original & unique BATMAN DOOM
Evil Space Tomato for his Batman Doom Patch v0.4 for ZDoom/SkullTag
DC Comics for their logo, Batman & all of his characters
Rocksteady Studios & Warner Bros Interactive for "Batman: Arkham City" jpegs (see BDOzyAdd*.pk3)
20th Century Fox for 1966's "Batman: Television Series"
iD Software for their logo, Doom II & Quake III underwater sounds
Monolith Software for burning sprites & player sounds from Blood
Gremlin Interactive for food sprites from Normality
Rogue Entertainment & Velocity for the pickup sound from Strife
Human Head Studios for heartbeat sound
Tormentor667 for HUD weapons/pickups/player sprites editing + revealing me what to fix
Sergeant Mark IV for destroyable stuff from ArmageDoom (cars, trashcans, garbages, trees)
Xaser for the smoke sprite from CryoBow weapon
Captain Toenail for the morbid-smokey cloud sprites from Rot Wraith
Nash for his NashGore system and its sprites/sounds
Mav3rick for his preciously inspired playtesting
Ed The Bat for CVARINFO and general useful code aid
MovieSoundsClip.net for various voice acts (see below)

Onomatopoeia sprites & decorate by Ozymandias81

1966 TV Movie Sounds at http://www.bat-mania.co.uk/multi/sounds/&#41
"I'm Batman" http://www.moviesoundclips.net/download.php?id=1926&ft=ogg
"Kill The Batman!" http://www.moviesoundclips.net/download.php?id=2618&ft=ogg
"Where are you!??" http://www.moviesoundclips.net/download.php?id=1945&ft=ogg
"Do you feel in charge?" http://www.moviesoundclips.net/download.php?id=4074&ft=ogg

== CHANGELOG ==
-Version 0.4.6-
Added onomatopoeias for Smoke Bombs;
Added new CVARs for onomatopoeias: now they're deactivatable through menues;
Added new intermission graphic: Kills (FOES);
Fixed Startup1 console messages (LANGUAGE);
Fixed some starting warnings;

-Version 0.4.5-
Added new breakable cars: THEY EXPLODE NOW!;
Some minor libraries code repolishments (changed to named scripts);

-Version 0.4.4-
Added DECALDEF & sprites for gore effects & projectile decals;
Added new heartbeat sounds + ACS script libraries;
Added new onomatopoeias effects like '66 TV Movie series!;
Added new taunt sound & bindings;
Replaced old health bonus with random food spawner;
Fixed end intermission with a new one, cycling through all foes with their names!;
Fixed rain effect switch: now sounds turns off properly;
Fixed weapons pickup sound: now it's the Strife one;

-Version 0.4.3-
Added some warping liquids through ANIMDEFS;
Added CVARINFO + MENUDEF + ACS for more customizable in-gaming experience;
Added ScareCrow poisonus smoke for PopUp special spawning (as seen on Gore);
Added some effects + 3dfloors from map16 till map29;
Removed map warnings & replaced berserk bonuses from map16 till map29;
Repolished / revamped all BatCaverns from map02 till map29;

-Version 0.4.2-
Added underwater sounds effects, used through ACS (as heared on Gore);
Minor buildings/textures repolishment/realignements from map05 till map14;
Killer Croc is fixed now;
Removed floating objects: this wasn't coherent/faithful to original BD;
Removed map warnings & replaced berserk bonuses from map05 till map14;

-Version 0.4.1 (yes, IMOH it contains only some slighlty but significant modifications)-
Added some properly sounds for pickups & player;
Added new rain effects: DENum from 10008 to 10011 (32x32 to 128x128 circle area);
Added new SNDINFO for different actors;
Added new EMPTY1 graphic for depleted hp;
Fixed ACS problems with Penguin & KillerCroc healthbars;
Fixed enemy counts display during INTERPICS;
Fixed map03: fixed final exit place, fixed some 3d floors, fixed BatmanSphere secret: it was inaccessible (unless jumping), added a step for it;
Fixed map04: added rain, berserk bonuses, 3d floors & fixed the secret inside yellow key room (see drawers);
No more warnings on MAP04;
Redefined Ninjakus anymore;
Some minor repolishment for ACS code;

-Version 0.4-
Added new recolored sprite actors for HUD weapons, pickups & player (thankx t667!)
All actors are DB ready, but inheritances are still not changed;
Fixed a glitch with Burn & Crush states to special TerroristKey actor;
Fixed Berserk glitch: added new BatmanBerserk powerup (DENum 10000);
Fixed many stuff on MAP01, MAP02, MAP03 (now has 3d Legacy floors);
No more warnings on MAP01 & MAP03;
Redefined Ninjakus a bit (lesser hard to beat);
Replaced berserk bonuses inside first 3 maps;

-Version 0.3-
Added burning sprites animations + GLDefs;
Added Burn & Crush states to many actors;
Added FLOATBOB properties to many pickups/powerups;
Added GLDefs to ZekeMolotov;
Added properly decorate translations for all pickups/powerups;
Blackie Slade sprite remaps for BatmanPlayer & his weapons;
Classified sprites inside properly folders;
Converted all sprites to PNG paletted format (Doom2);
Fixed an height problem with Zekes throwing sprites;
Moved out all new hi-res graphics / new songs to an external pk3: now it's up to you to use them or not;
Ninjas attacks are REALLY threatening now, added also personalized jump attack (like maulerdemons);

-Version 0.2-
Added creepy GLDefs to Scarecrow Shots;
Added GLDefs to Joker, PenguinCopter & keys;
Added new music title theme from original "Batman" TV Movies;

-Version 0.1 (what's the difference between this and BDP+07.pk3 patch?)-
PK3'ed all the original BATMAN DOOM WAD: you don't need the wad now;
Added GLDefs for Penguin Robots, Terrorists, Shotgun/GangWar Thieves, RocketMan;
Fixed "invalid state range, DEH support data not loaded" warning: while using original DEHACKED & my BD+ patches, CrocRock (CacodemonBall) actor was unrecognizable and not loaded (also entire DEHACKED);
Fixed DEHACKED max amount of ammos for SmokeBombs (now they're at max 100 not 960);
Fixed GLDefs for BatDoomChandelier (now fits very well), added for WallLamp;
Fixed Flamemen & Sniper GLDefs, now they're directly inherited via DECORATE;
Fixed BatmanPlayer & many monsters collision using Scale properties through DECORATE scripting, now you can REALLY play without using crouch\noclip;
Fixed LANGUAGE lump, now clusterdefs are faithful to originals;
Added new TITLEPIC, CONBACK, INTERPICS & CLUSTERPICS;

== TODO ==
Personal considerations:
Add a titlemap like Urban Brawl style;
Replace all actors with DENum's newer ones;
Zeke rotating sprites are really odd: sometimes molotov on the right hand, then on the left now
Bane needs some effects like Hexen bishops & minotaur, earthquakes and Venom power (must see what's meant for, don't know exactly this character);

Mav3rick playtesting:
==FIXED==
*1) I notice that in the map there is no enemies count to display but can see how many secrets
*2) the batarang still keep activating enemies
*5) the health pick ups maybe will be better if they have a batman air and the blue health potions too, they seem to be out of place on gotham
*7) batman still make doomguy sounds
*8) the ninja at the begining have a funny jumping attack that kill you almost instantly
*9) when fighting killer croc if you let him pick up a boulder and you hit it, it will vanish from his hands and also from the map giving space
*10) ninja fight 8/10 that killer jump is hard
*11) croc 6/10 because that little glich with the rocks getting vanished, he is no too aggresive
*13) the pick up ammo for the smoke bomb and weapons in general is the shotgun one :P
*16) will be tell more as i do more progress, oh and the Tally Man was not hard, maybe if you wanna make him move faster will be a hard enemy
==TOFIX==
3) also will be cool a new sprite for the batarang i will try to see if find one ;) and also make it more faster after all they suppoce to move silent and deadly
4) since he is batman and have a bat belt, maybe he should have in his inventory a night vision goggles or bat vision for those dark places ;) a portable medkit with 100 health since levels give almost no health and is very annoying, i guess you can grab the goggles and medkit from blood 1 and use them for those items :)
6) the armor pick up as the health pick up is very rare and poor on levels, maybe raising their value to 10 or 5 to give some edge
12) well i have played some more and i notice that the chinese enemies the one that throw you stars, when they hit u with their claws it make a matalic sound hit, maybe if the sound will be a ripping or tearing clothes will be more accurate and also the big guy with knife too ;)
14) maybe adding some "its batman" to the enemies may give some live the moment since they seems to never know with who they are fighting, even will be cool also give some lines to the bosses ;)
15) so far im a little stuck in the mission of the gas with the penguin, since as i told you before the health is low and that level there is plenty of zones that hurt the player, will play and see if there is a secret with health or something to let me progress :)

In A.. there is a problem with the aim level on all weapons, the bullets hits the lower part of where the crosshair is, causing problem when shoting mines or enemies on weird places
B.. when u get aligned with the walls the bullets dont fly over and hit the enemies, they just hit the wall down, and i dont use auto aim, no idea why it happens, no matter the distance
C.. the bushes r rock solid 
D.. self explanatory
E.. there is a invisible hole and needed to noclip to get out of it
F.. those chains r rock solid as the bushes

also found out that the sound of the torches is not tourches but more a annoying ticking and when the flying enemy show there is also a annoying sound playing, maybe good idea check that with others to see if they have the same problem
all this happen on the level 24, 25 and 27 :) hope it help ^_^
see u around and hope all is well with u and the proyects ;)

i made my way to the penguin and damn, that guy is hard ¬¬ for a umbrella that shit hit hard and i mean it in few times he kill me very fast, the only problem i did have was to hit it, the sprite is close to the floor but it seem the hit spot is in the center or close, so i needed to make arcs with the smoke bomb to kill him
im working on the scarecrow levels and there some few things on the maps i will give u a description and pick for u to check ;)

here there is some sprite out of place
in all these sections there was a huge problem with sounds, maybe too much sounds runing at the same time??
here the fire dont sound at all like fire more like a bip bip bip very weird  :?

well i have played some more and i notice that the chinese enemies the one that throw you stars, when they hit u with their claws it make a matalic sound hit, maybe if the sound will be a ripping or tearing clothes will be more accurate and also the big guy with knife too ;)

the pick up ammo for the smoke bomb and weapons in general is the shotgun one :P
maybe adding some "its batman" to the enemies may give some live the moment since they seems to never know with who they are fighting, even will be cool also give some lines to the bosses ;)
so far im a little stuck in the mission of the gas with the penguin, since as i told you before the health is low and that level there is plenty of zones that hurt the player, will play and see if there is a secret with health or something to let me progress :)
will be tell more as i do more progress, oh and the Tally Man was not hard, maybe if you wanna make him move faster will be a hard enemy 

Tormentor667 suggestions:
*- Fuel Cans shouldn't glow green
*- Fuel Can explosions are missing GLDEFs
*- Fire objects need GLDEFs
*- Enhancement: What about choosing a better background for the intermission texts? (or even a better smallfont that fits the rest)
*- The Flamethrowerguys Idle GLDEFs are too large/bright and are glowing even when he's dead
*- Playerclass is too tall, you can't enter some areas anymore without crouching (suggestion: keep viewheight as it is, make player as large as normal doomguy)
*- Pistol Ganngsters firing are missing GLDEFs when firing
*- Ammo Maxamount for tossable bombs is definitely too high I guess... I am at MAP19 now and have collected about 960 pieces.
*- Exploding Penguins need GLDEFs
*- Collecting the Berserk Pack doesn't automatically switch to fist
*- Enhancement: What about replacing the doomguy sounds with better ones? (pain, death, etc)
*- Chinese Melee monsters (the one with the too blades) seem too slow to me compared to the original Batman Doom (2x faster)
*- Fire-tossing enemies need GLDEFs (also their projectiles)
- MAP31 isn't beatable anymore - maybe I did something wrong, but please anyone confirm this
- MAP32 has a HOM effect at the very start