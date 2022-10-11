									README

This is yum13241's weapons mod. Let's start with the legal stuff first in
LICENSE. By using the mod, you agree to the content found in the LICENSE
lump.

The FAQ.

Q: What changed?
A: Weapons. I'll explain. All weapons have an increased raise and lower speed.

Fist: Slot 1. Is faster.

Chainsaw: Slot 1. Is faster now.

Precise Pistol: Slot 2. The pistol is now 100% accurate, and the alt fire does more damage, but spreads. Uses 3 ammo (it fires 3 shots, which do 8 damage, and spread).

Auto Shotgun: Slot 3. The shotgun now has 2 modes: auto mode (primary fire) and pump mode (altfire). The auto mode WILL slurp up your ammo!
Uses 1 shell.

SSG: Slot 3. Made reload faster, so it can be viable in this mod.

Precise Machinegun: Slot 4. It's now called the Machinegun, and the Machinegun is now 100% accurate. It's also very fast.

Rocket Launcher: Slot 5. Altfire shoots grenades.

Plasma Gun: Slot 6. removed recoil for primary fire, alt fire shoots a rail. Altfire uses 10 cells.

Railgun: Slot 6. Primary fire shoots a centered railshot, while altfire shoots left and right angled shots.
The altfire takes slightly longer to ready ater shooting and the normal fire uses 10 cells. and the alt fire uses 20 cells.

BFG9000: Slot 7. Altfire is the press release beta BFG2704 attack, but BETTER!. (In case you don't 
know, the BFG2704 in the press release beta shot 80 red and green balls. It was
removed for "looking like christmas" and lagging PCs at the time). I added it
back, this time as an altfire! Altfire uses 40 cells, if you have less than 40,
it will slurp it up all.


Unmaker: Slot 8. Works just like the Doom 64 Unmaker as of now. See decino's AMAZING video here @ https://www.youtube.com/watch?v=vvkraMwjo24

HBFZero: Slot 8. This gun is so overpowered it will destroy everything in one hit, and it's unobtainable without cheats. It was only added for fun and because I can.


New in version 1.4:


After the green and red ball blast, there will be 3 railgun shots, one centered, and one 10
degrees to the right, and another 10 degrees to the left. The balls bounce 3 times too!



Q: I'm confused about the license, can you help me understand?
A: So basically you can do whatever the hell you want to, but you can't change
the license of this work, you are free to learn from and reuse my code, and you
MUST give credit. The mod is share-alike WITH some exceptions. You MUST change the name of the 
software (including in say, GAMEINFO), and add the original author to CREDITS.
The license is also COPYLEFT, meaning that if you create a fork (spinoff), you
MUST keep in under this license, with some exceptions. See LICENSE for more details.


Q: HELP! I need compat with Freedoom/Chex Quest!
A: For Freedoom, the mod works out of the box, but can be a bit alienating.
In order for it to NOT use Doom weapon names, just change some things in
DEHACKED.

Replace:
TAG_CHAINGUN = Precise Machinegun
TAG_PLASMARIFLE = Plasma Gun
GOTCHAINGUN = You got the precise chaingun!
GOTLAUNCHER = You got the explosive launcher!
TAG_ROCKETLAUNCHER = Explosive Launcher

With:
TAG_CHAINGUN = Precise Minigun
TAG_PLASMARIFLE = Polaric Energy Cannon
GOTCHAINGUN = You got the precise minigun!
GOTLAUNCHER = You got the explosive launcher!
TAG_ROCKETLAUNCHER = Missile Launcher

OR just prefix a # to these entries. You could also delete the DeHackEd lump al-
together.

You are also gonna have to change the obituaries if you don't want alienation.
(They are in the DECORATE lump).

Other than some weapon name discrepancies, this mod works fine in Freedoom.

---------------------------------CHEX QUEST 3----------------------------------
Works!

For BOTH games, rename ALL the sound effects you don't want to use to smth like,
say, instead of DSRADIO (if you don't like the DWANGO 5 chat sound), rename
it to, say CSRADIO. Or anything other than DSRADIO really. If you
DO manage to get CQ3 working, rename DSSHOTGN to anything, like
CSSHOTGN, so it doesn't sound like DooM 64.

Heretic, HeXen, and Strife are OUT OF THE SCOPE of THIS mod. I'm surprised if
they work.



Q: How can I contact you?
A: You can reach me thru email, (anarchyforall123@gmail.com), the ZDoom forums,
(yum13241), and Discord (yum13241#8226). Please note that I don't use Discord often.

Q: Does the no warranty clause mean I can't ask for help?
A: No. It just means I'm not resposnsible if your computer explodes, divides 
by 0, or anything happens to your PC.
I am also not __obligated__ to provide help, but I still do provide help when I can.

