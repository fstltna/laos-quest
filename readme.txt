 
    --================================================================================================--
  ========================================================================================================
  |||                                       Lao's Quest                                                |||
  ========================================================================================================
    --================================================================================================--

Copyright SCORPION SOFTWARE

Coding      : JRLS
Status      : Finished / Build 8.5.2013 
Ingame help : Press F1
Homepage    : http://www.jrxs.net

If bugs are found in this version, a new build will be released.

If you want to contact me (comments, bug reports, etc), drop me an email at:
jrlsx@hotmail.com



============
| Note (1) |
============

This is a retro game. It also means some people find it too difficult.
For these people, I added ingame savepoints, which are called TIMESTONES.
These timestones are very handy when you're struggling. You can save and load your game from here. 

A Timestone will save everything up till now, including the states of all the objects in this room. 
Timestones are activated if you set the level on EASY or NORMAL mode and lives to oo (infinity).
In EASY mode, more timestones are available in the game, making the game easier.



============
| Note (2) |
============

If you're running this game under Vista or Windows 7 AND you're experiencing stuttering 
gameplay (this may or may not be), you need to change some settings on the file:
Right-click on the .exe file, go to  "properties", then tab "Compatibility" and change 
the following settings:

* Tick box "Run this program in compatibility mode for", and choose "Windows XP 
  (Service Pack 2 or 3)". Service Pack 2 might work better than Service Pack 3.
* Tick box "Disable visual themes"
* Tick box "Disable desktop composition"
* Tick box "Disable display scaling on high DPI settings"

Then, click "OK", and start the .exe file. Now, everything should run smoothly... 



============
| Synopsis |
============

A puzzle platform game where you need to think on how to get to the next level! Jump, shoot, throw 
dynamite, blast walls and avoid spikes and loads of traps. 

This game is a mix of Rick Dangerous (Amiga) and Kings Valley II (MSX) and will make your head hurt! 
This game is hardcore stuff (if you played Rick Dangerous, you know what I mean).

The level design is ingenious! This can truely be called a "puzzle platformer". 
Explore temples with living stones, moving platforms, ingenious deadly traps and some tricky enemies. 
Collect keys, open doors, watch out for watertraps, use buttons to control moving walls and 
platforms! Move and stack blocks to reach higher places, use moving doors, find hidden spots, use 
hidden items and much more! 

This is Indiana Jones retro style!!
You can even play with Rick Dangerous!

---------------------------------------------
WARNING: This game is hard! -- retro style -- 
---------------------------------------------



===============
| Development |
===============

I started this game in 2007, programming it from scratch. No other code from someone else is used in 
this project. It's programmed entirely in GML. I arrange everything myself, but I have some 
playtesters that rigorously test my game.

All music is ripped from King's Valley II (an MSX2 game) as some sound effects.
Other sound effects are homemade, or downloaded from the internet and edited with a wave editor.

Most of the graphics I made myself, or heavily edited from other sources. In some case I just took an
idea an went from there. King's Valley II, Rick Dangerous (Amiga version), and Rick Dangerous Advance 
(GBA) where sources for my ideas. In somes cases you might recognize the source. 
Rick himself was taken from Rick Dangerous (Amiga version), and only slightly edited to fit him into 
the game. In some cases I combined graphics, for instance, Lao is a combination of the character from 
King's Valley (his head), and parts of the body of Rick Dangerous. His hat is edited, and so is his body 
(he's sleaker than Rick).

I used to make music with a tracker (Protracker) and made graphics, but due to the physical problems, 
I spend a minimum of time on music and graphics (because of the extensive use of the mouse in most 
graphical and tracker programs). Therefor the lack of 100% homemade graphics and music. I hope you 
understand :) My main focus is on gameplay anyway, which I want to program myself entirely.

If you feel you need credits for work you think you saw in this game (and I missed), just drop me an 
email and I see what I can do. If you believe a game can ONLY be called your own, if everything is 
one-hundred-procent homemade (like coding, music and graphics), just send me an email on
jrls@why.dont.you.suck.my.dick.com



===========
| Credits  |
===========
No game without credits!

Coding         : JRLS
Music          : Kings Valley II (MSX / KONAMI)
Graphics/SFX   : Some gfx/sfx ripped and edited from various sources, including: Rick Dangerous ADV, 
                 Rick Dangerous Amiga, Kings Valley II and some some free resources downloaded from
                 various places.
Game Testers   : JRLS
                 Frank V
                 Fulthrotle1966
                 Yuui
                 Dench
Greets         : Yuui
                 Rober.t
                 DAF
                 Frank V
                 Fulthrotle1966

Special thanks to Frank V for pointing out a lot of bugs and ideas to improve the game!
I already had a 'final' version out, but now I had to think again :)

Also special thanks to Fulthrotle1966 for the YouTube walkthrough videos and some bug reports!



==========================
| Ingame Keys (keyboard) |
==========================

This game can be controlled entirely by a keyboard:

  cursor keys : move character and browse through menus
  <space>     : jump and confirm choices in menus
  <escape>    : go back / exit game / cancel
  <c>         : activate a switch or use a key on a lock
  <x>         : use bullits or dynamite: 
                  Hold button <x> + up to shoot bullit
                  Hold button <x> + down to drop dynamite
                  Hold button <x> + left to slide dynamite to the left
                  Hold button <x> + right to slide dynamite to the right
  <f>         : use Eagle Eye item
  <z>         : swap keys between Lao and Rick
  <v>         : switch player
  F1          : help screen
  F2          : pause game and see some info. Use down+F2 or up+F2 to see a room map.
  F3          : achievements
  F4          : size the screen (full screen or windowed. When windowed it can be resized with the 
                mouse)
  F5          : kill yourself (if you're stuck)
  F7          : make a screenshot of current room


You can also use a gamepad to play the game. It's tested with a logitech wireless rumble controller, 
but in theory it should work with any controller that can be recognized by windows. 10 button gamepad 
recommended, but at least 7 buttons are needed for comfortable gameplay.

Mapping of gamepad:
--------------------------------------------
| Gamepad                  keyboard        |
| button                     key           |
--------------------------------------------
  dir pad              ->     arrow keys
  <1>                  ->     <c>
  <2>                  ->     <x>       
  <3>                  ->     <space>
  <4>                  ->     <f>
  <5>                  ->     <F2>
  <6>                  ->     <z>
  <7>                  ->     <v>
  <8>                  ->     <F3>
  <9>                  ->     <F5>
  <10>                 ->     <F1>
  <hold down> + <10>   ->     <escape> 
--------------------------------------------



=========================
| Debug Keys (keyboard) |
=========================

When game is put in debug mode * (using cheat or password), extra options are available:
  P   : show debug screen
  F9  : save game state (save current game at ANY point) **
  F10 : load game state **
  F11 : instant full ammo for all players
  F12 : make all traps and objects visible in the current room
  L   : instant life up
  O   : toggle Eagle Eye
  left mouse button : place Lao at mouse position
  right mouse button : place Rick at mouse position

*  debug mostly used by myself for testing (but I decided to leave it in the game)
** using saving and loading state (F9 and F10) is a powerful mechanism. Just before a difficult point, 
   use F9 to save. When just afterwards you die, hit F10 to get back to the exact point you saved, 
   including exact state of the room, including lives, ammo, etc. Extremely useful for testing levels.

Passwords revealed at end of game:
- Debug password
- Password to jump to end demo



================
| Game Options |
================

When choosing GAME in menu, you can choose to start a new game, to continue from that last game, or 
enter a password.

Choosing OPTION will bring you to an option screen, where you can choose with how many lives you want 
to start. There is also the option to change the difficulty level of the game to EASY, NORMAL and HARD. 
Option EASY will give you a lot of hints in the game, and some levels are _slighty_ altered for easier
gameplay. Option NORMAL will give you a fair amount of hints in the game, but not as many as in EASY mode.
Option HARD will only give you the necessary ones, like the keys for controls. This makes the game a 
lot harder, since you have to figure out everything yourself, and no clues to solve a level are given! 
(for hardcore players). Default, the game is in NORMAL mode.

Also, I added the use of TIMESTONES. These are objects in the game that function as checkpoints. You can
save and load your game from here. A Timestone will save everything up till now, including the states of
all the objects in this room. In EASY mode, more timestones are available to use, compared to NORMAL mode.
In HARD mode no timestones can be used. Timestones are activated when you set the lives to oo (infinity)
in OPTION and set difficulty to EASY or NORMAL.
If you saved a timestone, and you quit the game, then if you start it up again, the timestone will be 
empty! So, timestones are only useful to save in a particular room while still in the game. If you restart 
the game, you will start at the room you were last time, at the beginning of the room.



================
| Game Objects |
================

LAO
Lao can walk, jump and climb ladders. He can grab a ladder in mid-air, by jumping towards it, and 
holding up to grab it. He can also jump of a ladder while halfway holding onto it. He can hold up to 5 
bullits and 5 pieces of dynamite. Lao can drop a dynamite, but can also slide it to the right or left, 
to slide it into tight places or down a pit. Lao can only use one piece of ammo at a time. Lao can wade 
through shallow water, but if it's too deep, he will drown.

RICK 
He can do the same as Lao, with a few exceptions. Rick hates water and drowns in even shallow water. 
He can only hold 4 bullits and 4 dynamite. Rick can crawl however, to get him in tight places that Lao 
cannot reach and duck for some arrows. Also he can jump higher and further than Lao to get him to 
places that Lao cannot reach.

? BLOCKS
If Lao or ricks stands on a ? block, it will show a hint. Most of the time it's a bit cryptic.

TIMESTONES
Timestones are stones on the wall that are inscripted with 4 letters. If you stand in front of a 
timestone, you have 3 options:
  1) Save    : Save checkpoint
  2) Load    : Load checkpoint
  3) Restart : Restart room
When a player dies, the last checkpoint is loaded automatically (if a checkpoint was saved.)
When entering a new room, the timestone is emptied and cannot be loaded, until you save a checkpoint 
first in that room. Timestones are placed at strategic locations. Beware though, if you do a room the 
wrong way, and you save a timestone, the room cannot be solved. So, if it's possible to save a timestone
it does NOT mean you can still finish the room. In those cases you end up restarting the room, so that's 
why option (3) is there.

INSCRIPTION
If Lao or ricks stands in front of a inscription block, it will show a hint. 

AMMO BOX
There are two types of ammo boxes. One if filled with dynamite, and one is filled with bullits. It will 
fill up your ammo. It will provide Lao with 5 pieces of ammo each. Rick can only hold 4 pieces of ammo.

WOODEN PLATFORMS
Lao and rick can jump on (moving) wooden platforms and ride along. It's also possible to jump up through 
a platform from below, either if they are moving or still. A piece of dynamite can be place on a (moving) 
platform to ride along. Good to get a piece of dynamite some place.

BLOCK
A block can be used to jump on, to get to higher places. The block can also be moved by pushing it. The 
block is heavy, so pushing is a bit slow. A block falls down when places on a ladder or if there's 
nothing below. A block can also be put on a (moving) platform to get it to different places. If a block 
is pushed out of the room (or falls out of the room), it can either disappear, or reappear on the other 
side of the room, depending on the room you're in. Some blocks can also be moved by using dynamite. If 
you put a dynamite on the right of this block, and it explodes, the block will fly to the left. And 
vice versa. This way, you can blast blocks over holes or pits. The blocks that can be moved with 
dynamite look a bit different. Blocks can either be grey of brown and can float in water. When floating, 
it helps to get over larger stretches of water.

LIVINGSTONE
Behaves a bit like a block. It can be on platforms and can be used to get to higher places. If 
Livingstone is asleep, it wont move, and behaves like a normal block, but it cannot be pushed like a 
normal block. If it wakes up, it will look for an active player, and will roll towards him (either left 
or right). You can use this to lure Livingstone into a certain direction. You can stop Livingstone with 
a bullit as it falls asleep when hit. This way you get can it to stop at a certain place and use it 
there, for example as a way to reach a certain place. You can also blow up Livingstone with dynamite. 
It will disappear and will reappear where it started initially in the room. This way you can lure 
Livingstone to a position, use it, blow it up, and then use it somewhere else. Livingstone can float in 
water like a normal block. When in water it wont wake up again, so it cant move anymore, unless you blow 
it up, so it can reappear somewhere else.

ARROW HEAD
Some arrow heads fire a deadly arrow. It can be slow or fast, but are always deadly and will kill off 
other enemies too. If an arrow hits a block, the arrow is destroyed, so you can use blocks as a 
shield. Rick can duck, so that some arrows fly over him and dont hit him.

BRIDGE
A bridge looks like a platform, but if you pass a certain times over it, it will disappear. How many 
times you can cross a certain bridge before it disappears, depends on the bridge, so it's never random.

INDIGENOUS STRANGER
This enemy can stay still or move around. You can kill it with a bullit or dynamite. Some enemies cannot 
be killed by a bullit though (who knows why this is???) Most of the time the move around back and forth. 
In some cases they fall of a platform and end up below. 

BAT
It will fly a certain path and is deadly. Kill it with a bullit or dynamite. Its path is never random. 
Some bats fly to high or low to be killed by a bullit.

ROLLING BOULDER
Sometimes a big rolling boulder appears. It will roll a certain path, but in some levels it can follow 
a different path under different circumstances (e.g. if you create a hole by blowing up a block if will 
create a new path for the boulder to follow). It will kill anything in its way, like the player, bats 
and other enemies.

MINI SPIKES
These can be found anywhere in the temple. They are always visible from the start and are always deadly. 
If you want to pass large area of mini spikes, you can try to position a block on the mini spikes, so 
you can jump on it and safely pass the mini spikes.

WOODEN SPIKES
They are visible from the start, or will appear all of a sudden. If you hit by it, you're dead. 
If spikes have appeared on the floor, you can push a block over it (or a living stone), so it's save to 
pass using the block.

FALLING FENCE
Some fences fall down when you're under them or near them and will kill you. When fallen down, some of 
them will slowly move upwards to there initial positions. IF they do, it's possible they'll fall again.

PLATFORM SWITCH
This is a red wall switch with some small arrows on it that controls a platform. If you press it, it 
will turn green for a short while, activating a platform that will start to move. 

TRAP DOORS
There are two types of doors. One of them only allows you to pass through it from one side only, and 
once you're through, you cannot access it from the other side. The other doors turn if you pass it, so 
if you pass through it from one side, you can access it from the other side to go back. Livingstones 
or blocks cannot be moved, blasted, or pushed through a trap door.

KEYS AND KEYHOLES
You can hold three keys. There are three color keys: red, green and brown. You can use a key on a 
keyhole with the same color. Using a keyhole opens a wall. All keys with a certain colorcan be used on 
different keyholes with the same color, so beware what to use on what, e.g. if there are 2 red keyholes 
and you have a red key, you can use it on both keyholes triggering a different wall. Once a keyhole is 
used, it cannot be used again.

TRAP WALLS
There are different kind of walls. Some will close if you walk under it. This wall cannot be blown up, 
so it might trap you. Other walls are closed from the start, but can be opened by using a key in a 
keyhole or by standing on a grey floor button. If you put a block or Livingstone under a closing wall, 
it will jam and wont close anymore. If you push away the block  or Livingstone is gone, the wall will 
stay in its (open) position. This way you can permanently open a wall, so you can pass under it more 
than once.

BIG BLOCK
This is a big block that looks like the floor. It can be blown up with dynamite, and will fly away, 
creating a passage through. Watch out as the flying block might kill you. It will also kill of other 
enemies, so you can also use it to your advantage.

FALLING BIG BLOCK
Looks like a big block, but mostly hanging from the ceiling. When passing under hit, it can fall down 
on you and kill you. It cannot be blown up, and can be used as a step to reach certain places once 
fallen down.

MINI BLOWUP PLATFORM
This is a mini wooden platform. It can be blown up with dynamite to create a passage.

BLOWUP WALL
This wall can be blown up by dynamite. It looks a bit different than a normal wall, as it has some 
minor cracks in it.

RED FLOOR BUTTON
This floor button can do three things, it will either shoot an arrow from an arrowhead, open a trap 
wall somewhere, or opens a watervent for a certain amount of time. If it opens a watervent, the water 
will flow into a confined space making the water level rise. If you put a block (or livingstone) in the 
water, it will float and rise up with the water, allowing you to get to a higher plane.

GREY FLOOR BUTTON
This button will open a trap wall as long as a player stand son the button. If you walk off the button, 
the wall will close again. You can also but a block of Livingstone on the button to keep the wall open.

PANEL AND MOVING PILARS
A panel consist of 2 or 3 buttons. If you stand in front of it, it will show the panel zoomed. Using 
buttons (1),(2),(3) you can push the buttons on the panel. Each button controls one or more pilars, 
which can go up and down. The control can be complicated. Some buttons on panels make it so that 
certain pilars always go up, and other always go down, or that a position of a pilar is inverted (if 
it's down, it'll go up and vice versa).

SWITCHING PLAYER
If you're playing with Lao and Rick at the same time (DUJO temple), you can switch between the two 
players. The character you're not playing will just stand there and does nothing, but remember he can 
be killed!

SWAPPING KEYS
If Lao and Rick stand close to each other, they can exchange keys each one of them collected. This way, 
Lao can pick up a key from a place Rick cannot reach, and then give the key to Rick. Rick then can use 
the key in a place Lao cannot reach. 

BIG GREY FLOOR BUTTON
In levels where you play with Lao and Rick at the same time, you can activate this button by both 
standing on the button at the same time. This will open a wall, allowing you passage to the  next level.

EAGLY EYE
This is a item that's hidden somewhere in temple 5. If you find it you can use it for the next levels. 
Sometimes a room consists of more than 1 screen. With the eye you can watch different parts of the room 
while you're not in it. 
NOTE: You can only use it if the player stands on a solid floor, and not while on a ladder.

TREASURE
It looks like an ancient maya mask. It can contain a lifeup. In certain rooms, collecting treasures 
will trigger to open a wall, so in some rooms it's vital to collect them all to progress in this room. 
Sometimes the treasures are hidden somewhere in the room, especially the ones that contain one or more 
lifeups. Treasures can be seen on the room map.




========
| Maps |
========

Use F2 to pause game, and see some info, like the current room you're in. The time you've spend in this 
room (used for archievements, see below) and the items you've collected. It also shows the password for 
the current room (including items and lives). This password can be used to jump to this room immediately.

Use down+F2 or up+F2 to see the map for the current room and how many screen the current room consists 
of. Red squares are players, green squares are ammo, and white squares are treasures (which can contain 
lives). It CAN also show red arrows that indicates a passage.



================
| Achievements |
================

Hit F3 to see your achievements. Use arrow keys to scroll up and down through the list.
If you collect all the treasures in a room, hit all the enemies that can be killed in this room (some 
enemies cannot be killed), and complete the room within a certain time, you get 4 blue emblems! Failing
to do so will result in 3 or less yellow emblems. Try to complete all the levels with 4 blue emblems, 
and be the true Lao's Quest Champion!
WARNING: this is not easy :)

NOTE 1 : Getting all embles is not necessary to complete the game. You wont get a different ending, or 
something like that.

NOTE 2 : There are also 3 bonus rooms hidden in this game. They can only be reached by password.
The passwords are hidden somewhere across the temples.


========================================
| End of Readme                        |
========================================



