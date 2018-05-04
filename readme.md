== CREDITS ==
20th Century Fox for 1966's "Batman: Television Series"
ACE Team for their original & unique BATMAN DOOM
Captain Toenail for the morbid-smokey cloud sprites from Rot Wraith
DC Comics for their logo, Batman & all of his characters
Ed The Bat for CVARINFO and general useful code aid
Evil Space Tomato for his Batman Doom Patch v0.4 for ZDoom/SkullTag
Gremlin Interactive for food sprites from Normality
Human Head Studios for heartbeat sound
Mav3rick for his preciously inspired playtesting
Monolith Software for burning sprites & player sounds from Blood
MovieSoundsClip.net for various voice acts (see below)
Nash for his NashGore system and its sprites/sounds
Rocksteady Studios & Warner Bros Interactive for "Batman: Arkham City" jpegs (see BDOzyAdd*.pk3)
Rogue Entertainment & Velocity for the pickup sound from Strife
Sergeant Mark IV for destroyable stuff from ArmageDoom (cars, trashcans, garbages, trees)
Tormentor667 for HUD weapons/pickups/player sprites editing + revealing me what to fix
Xaser for the smoke sprite from CryoBow weapon
iD Software for their logo, Doom II & Quake III underwater sounds

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