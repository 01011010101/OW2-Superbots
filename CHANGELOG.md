### April 18, 2024
* Team 1
	- Added VENTURE as playable hero.
 	- RAMATTRA: New ability: Ravenous Aura: Leech HP from Super Bots while in Nemesis Form (testing).
* Super Bots
	- Buffed damage slightly.
---
### April 8, 2024
* Team 1
	- JUNKER QUEEN: Buffed Ultimate damage
	- MAUGA: New ability: Ego Boost: Cardiac Overdrive also buffs nearby allies (testing).
	- SOJOURN: Fixed Jump Jet damage over time duration.
---
### March 17, 2024
* Team 1
	- DOOMFIST: Updated HUD to show Super Moves
	- ILLARI: Buffed Damage Dealt by 5%
  	- JUNKER QUEEN
		- Buffed Ultimate damage to 300
  		- Lowered Damage Dealt by 5%
	- KIRIKO: Yokai Blast's knockdown increased to 5 secs
  	- SOJOURN: Fixed an issue where Jump Jets would burn longer than intended
* Super Bots
	- ROADHOG: Tweaked cooldowns
 	- ZENYATTA: Fixed an issue that gave instant Ults in endgame if ZenBot had been in play for more than 5 mins
 ---
### March 12, 2024
* Team 1
 	- JUNKER QUEEN: Buffed Ultimate damage from 150 to 200
* Super Bots
	- ROADHOG: Rebalanced after they added him back to the bot pool with the March 12 update
---
### March 10, 2024
* Team 1
	- Rebalanced Healing Dealt for everyone back to WEVVY.
	- BRIGITTE: Lowered HP from 250% to 200%.
 	- JUNKER QUEEN: Fixed a bug that allowed her to shout while stunned or knocked down
	- KIRIKO: Buffed damage for both [PRIMARY] attacks
		- Ofuda: Damage increased from 10 to 15.
		- Papercut: Damage tick/sec increased from 28 to 35
---
### March 8, 2024
* Team 1
	- ECHO: Buffed Quantum Laser damage.
  	- JUNKER QUEEN: Buffed Ultimate damage from 130 to 150, lowered Ult gen (combat) slightly
  	- KIRIKO: Fixed typo in HUD for her Ultimate
  	- MEI: Decreased Frostburn damage from .1 to .05. Reason: A good Mei player can absolutely dominate a match, especially if they get lots of headshots (source: me).
---
### March 7, 2024
* Team 1
  - LIFEWEAVER: New abilites:
  	- Choice of damage when using Ult: AOE Poison or pulse damage/stun
   	- Replaced Life Grip with teleport. Reason: Lowering Life Grip's CD resulted in trolling, and increasing the CD made it useless, so I replaced it entirely. I wanted at least another ability for him and this was the cheapest server cost of my ideas to implement.
---
### March 3, 2024
* Team 1
	- MAUGA: Tweaked Bumrush CD from 4 to 5 seconds.
---
### March 1, 2024 (Back to 4v6)
* Team 1
	- JUNKER QUEEN: Extended range of shout effects by 1m

* General
 	- Removed 7th bot from Team 2. Reason: Increased workshop overload crashes. Will revist as more optimizations are made.
---
### February 28, 2024
* Team 1
	- SOJOURN: Modified HUD text for Ultimate, buffed Ult gen (combat)
---
### February 26, 2024
* Team 1
	- BASTION: New abilites:
		- Flashbang grenades stun bots for 1 second
		- Ultimate: AP Rounds: High damage and shoot through walls
		- Updated HUD.
---
### February 23, 2024 (4v7)
* Team 1
	- BASTION: Increased Flashbang CD slightly
	- ILLARI: Buffed Ultimate damage
	- JUNKER QUEEN: Buffed Ultimate radius from 2 to 3.
	- KIRIKO: Lowered Ult gen (combat)
	- RAMATTRA: New ability: Nemesis Void Punch
	- REAPER: Decreased damage slightly
 
 * General
 	- Added 7th bot to Team 2 slot. Reason: Testing adding max allowed bots for increased challenge.
---
### February 22, 2024
* Team 1
	- KIRIKO: New abilites:
		- 2x [PRIMARY] attacks: direct damage or DoT
		- Ultimate: Damage and knockdown bots in the path of your Kitsune.
		- Updated HUD.
  - GENJI: Update HUD, renamed Detonate Marks and changed the description slightly.
  - ZENYATTA: Updated HUD, made verbiage for [PRIMARY] and [SECONDARY] attacks to be more in line with Ultimate description.
---
### February 21, 2024
* Team 1
	- JUNKER QUEEN: New abilites:
		- Choice of shout (stun or knockdown)
		- Ultimate does massive damage in a straight line
		- Updated HUD.
--- 
### February 16, 2024
* Team 1
  - BAPTISTE: Lowered damage dealt
  - D.VA: Decreased Ultimate generation (passive, combat)
  - DOOMFIST: Lowered damage back to 100%.
  - HANZO: Lowered damage dealt slightly, lowered Ult gen. Reason: Hanzo in endgame basically gets instant ults.
  - MAUGA: New ability: Bumrush, an unstoppable charge.
  - MOIRA: Fixed flying when using Ultimate
  - REINHARDT: Lowered HP slightly
  - SOMBRA: Fixed HUD icon for Phased Stealth
 
* General
  - Updated Flying HUD
---
### February 12, 2024
* Team 1
  - Decreased damage dealt across the board. Reason: Bots are too easy. Also, bots dying too quickly = more levels faster for both teams = more frequent abilities = workshop load crashes.
  - SOJOURN: New abilities: (Reason: I felt her kit encouraged a hit-and-run playstyle, so I leaned into it with her new abilities)
  	- Rocket Boost Slide: Sweep and knockdown bots for 2 seconds when you slide into them.
   	- Jump Jets: Burn nearby bots for 10/sec for 3 seconds.
	- Ultimate: Super Railgun: Massive damage and shoot through walls. Reason: Unlike Widow, Sojourn cannot see through walls during her Ult, which helps make this Ult not stupid OP.
* General
	- Fixed bot names. Bots will no longer show "DAMAGE 3" or "TANK 1" but instead will have their proper names.
---
### February 11, 2024
* Team 1
	- ECHO: Reworked: (Reason: Echo went through the most revisions in this mode after OW2 broke two of her abilities. I believe this rework is a good balance of fun/ction at minimal server cost)
		- Quantum Beam no longer limited to Ultimate. Cooldown set to 14 seconds.
		- Ultimate: Overdrive: Free Flight + speed and damage buff. Reason: Enabled 'Buff Effects' extension to give Echo Ana's Nano Boost effect during her ult. The effect + the temporary buffs helps sell the effect.
		- Disabled permament flying, tweaked Flight cooldown. Reason: Echo already gained free flight from her Flight ability. Having her permanently flying (something I did to make her unique) meant running the new Flying script constantly, resulting in more frequent workshop overload crashes when she was in play. Decreasing Flight cooldown to 35% stills gives her almost constant free flight but at a much, much lower server cost.
		- Disabled Auto Fire for Sticky Bombs. Reason: Echo's Auto and Rapid Fire were broken in OW2 with the rate-of-fire changes. After many different iterations, the best way to emulate the OW1 Auto Fire for Sticky Bombs was to set CD=0% and loop the Auto Fire rule every .800 seconds. Unfortunately, this has a high server cost and caused workshop load crashes, so I shelved this for now pending a rework.
		- Updated HUD.
	- REAPER: Decreased damage by 3%. Reason: Reaper needs to be one of the top DPS, but he continues to do 300k+ more damage than everyone else.
---
### February 6, 2024
* Team 1
  - DOOMFIST: Lowered damage dealt to 125%
  - ECHO: Lowered Flight cooldown
  - MEI: Decreased Ultimate generation (combat, passive), lowered damage dealt to 150%
  - MOIRA: Lowered Ultimate generation (passive)
  - REAPER: Lowered HP
  - ROADHOG: Fixed speed boost when using Asthmatic Trample
  - SOJOURN: Fixed HUD (top HUD counter was enabled for her when it shouldn't have)
    - Added new ability: Rocket Boost Slide
---
### February 3, 2024
* Team 1
	- JUNKER QUEEN: Increased Ultimate knockback impulse slightly
* Super Bots
	- KIRIKO: Buffed HP to 500%
---
### January 27, 2024
* Team 1
  - Fixed Flying. You now move at 0 speed when enabling flying. Reason: This is how flying worked in WEVVY.
  - ECHO: Made flying permanent (no toggle)
  - JUNKER QUEEN: Increased knockback of Jagged Blade, increased Ultimate generation (passive) cooldown to 100%.
  - MERCY: Decreased damage to 150%.
  - MOIRA: Ult changes:
	- Disabled manual cancelling of Ultimate. Reason: Kept being reported as a bug. Removing this does not significantly change her gameplay.
 	- Made Ultimate duration a flat 10 seconds and removed the internal counter/timer. Reason: Moira started causing workshop overload crashes near the endgame as she was Ulting too frequently (did not happened in OW1). I removed the internal variable chase that made her Ult 20 seconds and the supporting code to cut down on the number of scripts running, and replaced the counter with the in-game Ultimate duration counter (accomplished by changing her Ult duration from 'infinite' to 122%, which is exactly 10 secs).
	- Now phased while casting Ultimate. Reason: To compensate for the above changes. She Ults less frequently now, but when she does she makes a big bang.
  - REINHARDT: Increased Fire Strike cooldown back to 100%. Reason: to compensate for now having 2 charges.
---
### January 15, 2024
* Team 1
	- CASSIDY: Increased Phased Roll cooldown to 3 seconds. Reason: Workshop overload crashes when spammed (this occured in OW1 too, I kept forgetting to fix it).
---
### January 12, 2024
* Super Bots
  - ORISA: Increasd HP to 475%, decreased Javelin Spin cooldown to 80%. Reason: Needed to be more of a threat.
---
### January 8, 2024
* Team 1
	- MAUGA: Decreased Ultimate generation (combat)

* Super Bots
	- MAUGA: Decreased damage a little.
---
### December 29, 2023
* Team 1
	- Reset several heroes' Ult generations back to WEVVY.
---
### December 22, 2023
* Team 1
  - D.VA: Increased Bunny Hop chase rate
  - HANZO: Fixed Sonic Arrow explosion
  - JUNKRAT: Modified money earned from kills. Reason: Workshop overload issues from frequent use.
  - MAUGA: Lowered Health from 300% to 200%.
---
### December 2, 2023
* Team 1
  - Rebalanced several heroes back to WEVVY.
  - MAUGA: Fixed HUD
  - ROADHOG: Fixed Asthmatic Trample (broken after Nov 4, 2023 update)
  - SOJOURN: Buffed damage
---
### October 24, 2023
* Team 1
	- Decreased Ultimate generation for:
		- CASSIDY
		- GENJI
		- ILLARI
		- JUNKRAT
		- MEI
		- MOIRA
		- PHARAH
		- REINHARDT
		- SOJOURN
		- SOMBRA
		- TRACER
		- WIDOWMAKER
		- ZENYATTA
	- Hero Changes:
		- ORISA: Fixed [ABILITY 1] self-heal and moved it to [ABILITY 2], fixed HUD, tweaked cooldowns.
		- PHARAH: Decreased power generation slightly

* General
  - Updated Game Mode description.

* Super Bots
  - MOIRA: Increased Ultimate frequency
---
### October 4, 2023
* Team 1
	- Decreased Ultimate generation for:
		- GENJI
		- JUNKRAT
		- ORISA
		- REAPER
		- REINHARDT
		- ROADHOG
		- WIDOWMAKER
	- Hero Changes:
		- HANZO: Buffed damage
		- MEI: Increased cooldown of Ice Block
		- PHARAH: Fixed an issue where Bunker Buster was not deducting 100 power
		- ROADHOG: Increased Rebreather cooldown
---
### October 3, 2023
* Team 1
	- Decreased Ultimate generation for:
		- BASTION
		- CASSIDY
		- MOIRA
		- SOMBRA
	- Hero Changes:
		- D.VA: Increased Bunny Hop's T chase rate
---
### September 30, 2023
* Team 1
	- Decreased Ultimate generation for:
		- D.VA
		- JUNKRAT
		- SOMBRA
	- Hero Changes:
		- PHARAH: Decreased power generation slightly

* Super Bots
	- Buffed bot HP, damage, and ultimate generation across the board
---		
### September 25, 2023 (4v6)
* Team 1
	- Decreased Ultimate generation for:
		- BASTION
		- PHARAH
		- SOMBRA
		- TORBJORN
		- ZARYA
	- Hero Changes:
		- ASHE: Decreased Shotgun knockback to 200%
		- CASSIDY: Ammo limit increased to 200%
		- ECHO: Increased Quantum Beam cooldown
		- REINHARDT: Increased Shield Recharge

* Super Bots
	- Changed Lucio's DANGER HUD element and removed the ⚠️ icon. Reason: Lucio's ult becomes predictable. I didn't want to change any of his great Ults or the timing, so obscuring when he will exactly ult introduces the illusion of randomness.
	- Increased Ultimate generation for:
		- HANZO
		- BRIGITTE

 * General
	- Changed Team 1 player slots to 4.
		- Reason:<br>1) I want something different than the now-standard 5v5, but 6v6 causes a ton of workshop overload crashes. 4v6 is a good compromise and something I can properly balance and extend safely.<br>2) I don't advertise this game mode, so filling a full team of 6 people for a few matches almost never happens.
---
### September 16, 2023 (More OW2 Fixes)
* Team 1
	- Decreased Ultimate generation for:
		- D.VA
		- ILLARI
		- JUNKER QUEEN
		- MCCREE
		- SOJOURN
		- TRACER
		- ZENYATTA

* Super Bots
	- Changed bots from 'Hard' to 'Extreme'. Reason: Hard is not hard anymore in OW2. Lethal was slightly better, and Ultimate and Aimbot were unfair (especially for low HP heroes who would get 1-shot instantly from across the map). Extreme is a good starting point for now, but may change later.
	- Increased Ultimate generation for:
		- HANZO
		- BRIGITTE

* General
	- Decreased PUSH robot speed.
---
### August 4, 2023 (Fix everything broken in OW2)
* Team 1
	- Enabled OW2 heroes for Team 1
	- Added new heroes to Armor Classes:
		- Illari -> 25
		- Junker Queen -> 75
		- Kiriko -> 25
		- Ramatra -> 50
	- Enabled PUSH mode and associated maps.
	- Added more maps to the pool.
	- Fixed HUDs for new OW2 heroes
	- Modified HUDs for heroes who had abilities disabled
	- Fixed D.VA's Bunny Hop (downward impulse would not activate)
	- Fixed ECHO's Auto Fire and Ultimate
	- Fixed WIDOWMAKER's Ultimate Rail Gun.
	- Fixed Third Person
	- Disabled Flying for MOIRA, SIGMA, and ZENYATTA. Reason: The method to enable flying in OW1 (Gravity=0%) is broken in OW2. Need to fix.
	- Disabled broken abilties for:
		- BAPTISTE
			- Ultimate: Full-Auto. Reason: Broken in OW2 (rate-of-fire changes).
		- BASTION
			- Ultimate: Proton Cannon. Reason: Beam needs "Beam Effect" extension to be enabled.
		- DOOMFIST
			- Super 1 - Super Uppercut. Reason: Broken with OW2 rework. Needs fixes.

* Super Bots
	- Added new OW2 heroes to bot pool.
 	- Balanced new OW2 Super Bots.
	- Disabled SUPERBOTS Torbot Ultimate Auto-Fire. Reason: Broken in OW2.
	
* Relics
	- Fixed Vortex resetting speed to 100% when respawning.
	
* General
	- HUD
 		- Updated button references (made them more generic) for HUDs and abilities to account for console/controller.
		- Removed player death and superbot killed counters. Reason: Replaced by scoreboard.
		- Removed Challenge Roulette when challenge is not active. Reason: The HUD in OW2 is jacked. Left and right-side text is centered, so removed this to improve visibility.
	- PUSH Mode
		- Increased push bot speed.
---
###### CHANGES BELOW COPIED FROM [HERE](https://docs.google.com/document/d/1WwOGDoImdErTrU-VU9Pxc0oTp9ALMUmJaqAeW_fBrm8/edit#heading=h.426wf8g8k27o)

### 04/24/2020 - 05/21/2020 (1.00 PTR)<br>
  CORE:  
    Updated all HUDs, all icons and all descriptions.  
    Halved everyone’s damage and halved the bot’s max HP on level up.  
    Changed Armor tiers to be a flat +25.  
      Tier 1: 0 Ranged  
      Tier 2: 25 Support  
      Tier 3: 50 Bruisers  
      Tier 4: 75 Tanks  

  RELICS:  
    Relic descriptions have been shortened now so they take up less room on screen, however I have added new instructions on screen.  Holding [Crouch] will allow you to display more information per relic you have equipped.  Hopefully this should clear up any confusion on what your relic does.  

  All Relics have been reworked or improved.  
  Fixed an issue when selecting a relic then switching heroes would automatically equip you with that relic while inside of the spawn room, which is unintended.  
  Purified:  
    +100% Healing dealt and received.  
    +50% Damage when full health.  
    +10% HP per second.  
  Vortex:  
    +100% Movement Speed.  
    +Damage based on current Movement speed.  
    -7 Second respawn timer.  
  Corrupted:  
    +100% Damage  
    -25 Armor  
    +5% Ultimate Generation per kill  
  Aegis:  
    +10 ~ 25 Armor based on role. (10 if you are a tank, 25 everyone else)  
    +25% Damage per nearby bot, for a total of +150% Damage.  
    +Shield invulnerability when you’re low on HP, 40 second cooldown.  
  Hero:  
    +25% Damage.  
    +25% Movement speed.  
    +25% HP per elimination.  
    -1 Second cooldown on damage dealt.  
  
  HEROES:  
    Removed Third Person camera for a few character’s ultimates that didn’t work out after all, like Pharah and Roadhog.  But added third person to other abilities to improve the gameplay feel for unique abilities.  
    Changed Armor tiers for some characters:  
      TORBJORN 75 -> 50  
      MERCY 50 -> 25  
      ECHO 50 -> 25  
      LUCIO 50 -> 25  
      BRIG 50 -> 25  
      REAPER 25 -> 50  
      SOMBRA 25 -> 50  
      SIGMA 25 -> 0  
    Ana   
      Reduced size of primary AoE heal by 2m down to 5m, corrected the effect.  
      Primary attacks now apply a 10 second weak poison that deals 1% of a bot’s max HP every second, but this poison keeps stacking if you continue to deal damage.  
    Baptiste  
      Jumping height slightly increased so that you get better air with hover boots.  
      Unlimited ammo turned on again.  
      Full-Auto removed.  
      Ultimate Full-Auto: Grants Full-Auto and double damage after placing Amplification Matrix.  
    Hanzo  
      Removed automatic storm arrows.  
      Burning from fire arrows now stacks on targets.  
      Sonic Arrow now applies Burning or Frozen to all enemies in a 10 meter radius if you land the shot on an enemy, the burn and freeze from this arrow are much stronger.  
    Lucio  
      Removed damage bonus from movement speed on boop, moved it to Vortex.  
      Removed Primary attack.  
      Reduced Soundwave knockback.  
      Soundwave (Tinnitus) deals knockback based on movement speed.  
      Soundwave (Tinnitus) heals based on movement speed.  
      Lucio’s base damage increased to 400% (makes Soundwave deal 100 damage).  
      Amp It Up doubles Lucio’s damage for the duration.  
      Lucio takes reduced damage based on his current movement speed.  
      Removed the ring effects from his ultimate, it was causing too much visual chaos.  
    Moira - Changed her HUD text to display as In-World Text so that everyone can see what her ultimate’s current charge is at.  
    Pharah - Reworked:  
      Rebalanced damage gained from Fusion Reactor.  
      Removed Emergency Repairs.  
      Fusion Reactor: Now starts at 0% and builds to 999%, can no longer go past the limit by earning eliminations, but eliminations still give 25%.  
      Bunker Buster: Reduced cost from 150% to 100%.  BB can now be used even if you don’t have any fusion reactor power, it’ll just be much weaker.  
      Booster Dash: Fly forward without gaining or losing altitude while holding [secondary fire].  You take less damage while Booster Dashing.  
    Reaper  
      Renamed Rampage to Creeping Death, improved visuals, polished scripts.  
      Moved shadow teleport to melee, apparently it’s easier to use for some people.  
    Reinhardt  
      Sonic Charge now phases out Reinhardt for 1.5 seconds.  
      Scorching Wave can now stack and re-apply burning.  
      Symmetra - Fixed a glitch that made other characters spawn while holding secondary fire after having played with Symmetra, thanks @Scourge for the fix.  
      Nerfed impulse mine’s activation from 4 seconds to 5 seconds.  
    Torbjorn - Reworked:  
      Can use Rivet Gun again.  
      Dwarven Rage: [Ability 2] Overload enhances your abilities and heals for 25% HP and doubles your damage for the duration.  
      Dwarven Leap: Hold [Crouch]+[Jump] to leap forward in the air.  
      Dwarven Rage: Knockdown bots and set them on fire when you land.  Also phases you out for the duration of the leap.  
      Molten Punch: [Melee] sets bots on fire.  
      Can stack the burn effect.  
      Dwarven Rage: Knockdown bots when punched as well.  
    Winston - Removed Harambe’s Rage, moved it to Aegis.  Renamed ultimate to “Harambe’s Revenge”.  
    Zenyatta - Reduced healing area of primary fire from 10 to 5 to match Ana’s healing area, also fixed the ring effect to match the healing area.  
  
  SUPERBOTS:  
    Bots Level up faster now.  Every 10 deaths = 1 level.  
    Removed Overtime speed bonus.  
    Added Overtime Challenges during overtime.  
      Separation Anxiety  
      Social Distancing  
      Relentless  
      Sudden Death  
      Juggernaut  
      Swarm  
      Apotheosis  
    Removed all permanent icons.  
    Removed Lucio’s “Danger” sound, since it wouldn’t work consistently.  
    Changed Lucio’s “Danger” text to now be a Warning icon -> ⚠.  
    Increased Lucio’s knockback cooldown.  
    Lowered Damage on Bastion and Torbjorn.  
    Lowered Reaper’s stun from 0.8 to 0.5, now it should be easier to avoid death if you react fast enough on certain characters.  
    Zarya’s Death Sphere now instantly kills any players inside upon expiration.  
  
### 04/14/2020 (0.99.9f)  
  HEROES:  
    Echo - Added Echo base functionality so she doesn’t break the game.  Will add custom changes to her in the next version.  
  
### 04/13/2020 (0.99.9e1)  
  HEROES:  
    Junkrat - Fixed a script where his money would be infinitely adding to a total earned.  Fixed his money earned message so that now it consolidates multiple earnings from eliminations into one message.  Made Killpile roulette teleport slightly above payload, needs testing.  
    Symmetra - Did a first pass on her rework, reverted her invincible change.  Now she takes damage again but her impulse mine constantly deals damage as soon as it’s ready again.  4 Second cooldown between pulses.  Still a work in progress, will keep an eye on her.  
  
### 04/06/2020 - 04/10/2020 (0.99.9e)  
  CORE:  
    Some characters such as Doomfist and Junkrat that instantly killed enemies now cause damage over time, which simulates instantly killing them, but it should give more credit towards POTG.  
    Some characters now use Third-Person while using their ultimates.  
    Fixed and updated a couple of HUDs, work in progress.  
  
  RELICS:  
      Aegis - Now increases the player's armor by 10% as well.  
      Hero - 25% Damage, 25% Speed and 25% Max HP recovered per elimination.  Rebalanced the relic so that it’s equally as good as the others, just in a different way.  Also removed lifesteal since it was heavy on server resources and some characters benefited from it while others didn’t at all.  I reduced the speed because 50% felt like too much at higher levels, especially for people that particularly avoid Vortex for that very same reason.  
      Hero - Fixed an oversight where equipping Hero over and over would result in infinitely increased damage.  
      Vortex - Fixed slide animation not showing up or working as intended.  Reduced the stun of the slide slightly.  
  
  HEROES:  
    Ana - Increased primary healing from 100 to 150.  
    Baptiste - Buffed Damage.  Now has full auto, but infinite ammo turned off.  
    Bastion - Proton Cannon now deals damage based on how strong the bots are, so his scaling adapts instead of dropping off in the later game.  Gonna start doing this to all DPS characters that need it, nobody else.  
    D.va - Fixed Bunny Hop not working, added third person camera to it.  
    Doomfist - Some of his super attacks knockdown now, so he gets credit on some environmental kills.  Landing a super will heal him for 25% of his max health over 3 seconds.  
    Junkrat - Buffed his damage.  Updated and polished Kill Pile and Point explosion roulette, they’re more reliable now and less subject to “nothing” happening.  Hopefully fixed his money message, needs testing.  
    Lucio - Resurrecting players now grants 10% bonus damage.  
    McCree - Increased his base damage and now his ultimate sends enemies flying after a random interval, pay attention and shoot them when they go into the air.  You have to be far away from the bots when you activate ult, because they will focus you.  
    Mercy - Fixed a mercy glitch that caused her to deal 0% damage from the start.  Mercy’s charm no longer has a cooldown, but now it only lasts 5 seconds.  Charm now only grants 10% damage, but resurrections also give her 10% damage now.  
    Moira - Polished her bomb scripts, she now pulsates for far less damage per tick while building the bomb, fixed an issue with the bomb dealing damage outside of the bomb on detonation.  The bomb now deals damage once per explosion (4 times) at the end, and it’s based on how much you built up.  The bomb’s damage will scale as the game progresses.  
    Reinhardt - Fire Strike now burns bots again, but no longer knocks down and has a 1 second cooldown.  His shield now heals him for 5% of his max health instead of a flat 50 hp every second while deployed.  
    Reaper - Fixed an exploit oversight with Rampage when switching characters while Rampage was on.  
    Sombra - Lowered Max Health slightly, buffed her damage.  Sombra wasn’t doing double damage with her backstab, she was doing like x10 damage, so I fixed it.  She’s meant to be a support DPS because of her ability to CC so hard.  So yeah she’s not meant to outshine characters like Widowmaker or Ashe in terms of damage.  
    Symmetra - Re-worked her a bit, she can’t be damaged now at all but she also can’t contest the point if she’s the only one on the point.  WIP, needs testing, etc.  
    Widowmaker - Explosion damage increased slightly, radius halved but still based on charge.  
    Zenyatta - Increased primary healing from 40 to 100.  
  
  SUPERBOTS:  
    Torbjorn - Removed fire aura.  
    Roadhog - Removed breather knockback.  
    Zarya - Buffed damage.  Death Sphere now causes a burning effect for clarity and her sphere should do a flat 25% of your max health, this is still reduced by your current armor.  Once you have 25% or less, it will deal even more damage based on Zarya’s current damage increase.  Needs testing.  
    Lucio - Reduced healing by half, his healing was off the charts.  Buffed “World on Fire” roulette event so it is more deadly, seeing as nobody has ever died from it.  
    Reaper - Nerfed his damage slightly.  Reaper should now stun everyone that gets touched by his ultimate, instead of just the first person.  You can only be stunned once per every 3 seconds.  
  
###### LOGS HAVE BEEN TRIMMED
