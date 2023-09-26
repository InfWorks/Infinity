# Project Infinity
An Project Lotus Fork with lesser bugs and a bit more roles

# Project Infinity Background (ig)
![Inferno_Star](https://github.com/InfWorks/Infinity/assets/123344741/12da5b21-e252-4059-b565-fd8e5630d03c)


I am still working on this mod so please bear with me


What you should Expect:
  - All Lotus Roles
  - All bugs reported in Lotus to be fixed
  - Some roles coming from The Other Host Roles (Revival Roles Wont be added)
  - TOS options from TOH : TOR
  - Some TOS inspired roles
  - Some TOU inspired roles

Thats about it.

Roles
Impostor	Crewmate	Neutral Killing	Neutral Passive	Modifier
Assassin	Alchemist	AgiTater	Amnesiac	Bait
Blackmailer	Bastion	Arsonist	Copycat	Bewilder
Camouflager	Bodyguard	Blood Knight	Hacker	Bloodlust
Consort	Charmer	Egoist	Jester	Diseased
Creeper	Crusader	Hitman	Opportunist	Flash
Disperser	Demolitionist	Jackal	Phantom	Nimble
Escapist	Dictator	Juggernaut	Postman	Oblivious
FireWorks	Doctor	Marksman	Schrödinger's Cat	Romantic
Freezer	Escort	Necromancer	Survivor	Sleuth
Grenadier	Ex-Convict	Occultist	Terrorist	Tiebreaker
Identity Thief	Herbalist	Pelican		Torch
Janitor	Investigator	Retributionist		Watcher
Mafioso	Mayor	The Glitch		Workhorse
Mare	Mechanic	Werewolf		
Mastermind	Medic			
Miner	Medium			
Morphling	Mystic			
Ninja	Observer			
Pickpocket	Oracle			
Puppeteer	Physicist			
Serial Killer	Psychic			
Sniper	Repairman			
Swooper	Sheriff			
Time Thief	Snitch			
Vampire	Speedrunner			
Warlock	Swapper			
Witch	Tracker			
Yin Yanger	Transporter			
Trapster			
Crewpostor (Madmate)	Veteran			
Mad Guardian (Madmate)	Vigilante			
Madmate (Madmate)				
Mad Snitch (Madmate)				
Parasite (MadMate)				
Host Only Roles
GM


The GM (Game Master) is an observer role.
Their presence has no effect on the game itself, and all players know who the GM is at all times.
Always assigned to a host and is ghosted from the start.





Impostors
Assassin


Team: Impostor
Base: Impostor
Ability: Guess Roles To Kill

Role Description
Assassin is an evil guesser and part of the Impostor team. While in meeting the Assassin first vote locks in the player they're going to guess. Then the Assassin uses a chat command to guess the role (i.e. /r [role]). The Assassin's second guess locks in the guess. The Assassin has the ability to kill regularly and will suicide if they miss-guess.

Game Options (incomplete)
Name	Description	Type	Default
Assassin	The probability of the Assassin appearing	Percentage	0%
Maximum	How many Assassins should spawn	Number	1
Blackmailer


Faction: Impostor
Base: Impostor
Ability: Blackmail A Player
Indicator/Symbols: "BLACKMAILED" Text Over Targeted Player

Originally Developed by Tealeaf/단풍잎
Idea by Town of Us Reactivated & Town of Us

Role Description
Shapeshift into a player to blackmail them. During meeting, the blackmailed player will have text displaying "BLACKMAILED" to all players. If the player writes a certain number of messages (determined by host) while blackmailed, they will be executed.

Game Options
Name	Description	Type	Default
Blackmailer	The probability of the Blackmailer appearing	Percentage	0%
Maximum	How many Blackmailers should spawn	Number	1
Warnings Until Death	How many warnings the Blackmailed player gets before suicide	Number	0
Show Blackmailed To All	Show the 'BLACKMAILED' indicator to all players	Toggle	ON
Bounty Hunter


Faction: Impostor
Base: Impostor
Ability: Reduced Kill Cooldown
Indicatior/Symbols: Text Indicator Displaying Current Target

Originally Developed by: Discussions
Idea by The Other Roles

Role Description
Collect Bounty from Target players (marked by black name). If the Bounty Hunter kills their target, their kill cooldown is significantly reduced for their next kill. The time it takes for the target to change, the kill cooldown after killing their target, and kill cooldown after killing a non-target are predetermined by host in settings.

Game Options
Name	Description	Type	Default
BountyHunter	The probability of the Bounty Hunter appearing	Percentage	0%
Maximum	How many Bounty Hunters should spawn	Number	1
Time Until New Target	Time before the Bounty Hunters target is changed	Time	60
Kill Cooldown After Killing Target	The cooldown of the Bounty Hunter's Kill button after killing their target	Time	15
Kill Cooldown After Killing Other	The cooldown of the Bounty Hunter's Kill button after killing a non-target	Time	37.5
Camouflager


Faction: Impostor
Base: Shapeshifter
Ability: Disguise Everyone
Indicatior/Symbols: None

Originally Developed by: こう。
Idea by Town of Us Reactivated

Role Description
Shapeshift into a player and cause every living player to shapeshift into the chosen player for a short amount of time. When the duration is over, or if a meeting is called, players return to their normal form.

Game Options
Name	Description	Type	Default
Camouflager	The probability of the Camouflager appearing	Percentage	0%
Maximum	How many Camouflagers should spawn	Number	1
Camouflage Cooldown	The cooldown of the Camouflager's Shapeshift button	Time	17.5s
Camouflage Duration	Amount of time players are shifted for	Time	17.5s
Can Vent	Whether the Camouflager has a Vent button or not	Toggle	ON
Consort


Faction: Impostor
Base: Impostor
Ability: Roleblock Players
Indicatior/Symbols: Text Indicator Displaying Current Mode

Originally Developed by: Discussions
Idea by Det

Role Description
Use the Pet button to alternate between Role-Blocking and Killing. Role-Blocks prevent killing, reporting dead bodies, calling meetings, shapeshifting, and venting.

Game Options
Name	Description	Type	Default
Consort	The probability of the Consort appearing	Percentage	0%
Maximum	How many Consorts should spawn	Number	1
Roleblock Cooldown	The cooldown of the Consort's Kill button	Time	45s
Roleblock Duration	The duration of the Consort's Role-Block function	Number	Until Meeting
Creeper


Faction: Impostor
Base: Impostor
Ability: Mass Distruction
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Discussions

Role Description
The Creeper's only job is to cause as much devasation as possible. Use either your Pet or Shapeshift button to kill yourself and any player within a radius. You might find yourself lucky and be protected from your bombs with a shield (ex. medic shield) and live to see another day. If the option is off however, not even the medic shield will protect you.

Game Options
Name	Description	Type	Default
Creeper	The probability of the Creeper appearing	Percentage	0%
Maximum	How many Creepers should spawn	Number	1
Can Kill Normally	Whether the Creeper can kill normally	Toggle	ON
Can Be Shielded	Allows Creeper to be shielded by other players	Toggle	ON
Explosion Radius	The radius at which players will be affected by the Creeper's explosion	Toggle	Small
Grace Period	The amount of time before self explosion	Time	10s
Disperser


Faction: Impostor
Base: Impostor
Ability: Teleport Players
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Town of Us Reactivated

Role Description
Use Pet button to teleport everyone to a random vent.

Game Options
Name	Description	Type	Default
Disperser	The probability of the Disperser appearing	Percentage	0%
Maximum	How many Dispersers should spawn	Number	1
Disperse Cooldown	The cooldown of the Disperser's Pet Button	Time	12.5s
Disperser Gets Dispersed	Whether Disperser is teleported when ability is activated	Toggle	ON
Escapist


Faction: Impostor
Base: Shapeshifter
Ability: Mark A Location & Strategically Escape
Indicatior/Symbols: Text Cooldown Displaying Time Until Able To Escape & Until Next Mark

Originally Developed by: Discussions
Idea by Town of Us Reactivated

Role Description
First use Pet button to mark a location. Then, after a set cooldown, you can re-use the Pet button to teleport back to your marked location. This will then put the mark ability back on cooldown.

Game Options
Name	Description	Type	Default
Escapist	The probability of the Escapist appearing	Percentage	0%
Maximum	How many Escapists should spawn	Number	1
Cooldown After Mark	The cooldown of the Escapist's Mark ability	Time	5s
Cooldown After Escape	The cooldown of the Escapist's Escape ability	Time	40s
Clear Mark After Meeting	This option removes the Escapist's Mark after meeting	Toggle	ON
FireWorks


Faction: Impostors
Base: Shapeshifter
Ability: Explode Players Within Radius
Indicatior/Symbols: None

Originally Developed by: こう。
Idea by こう。

Role Description
Use Pet button to plant a fireworks (i.e. bombs) around the map until Max Firework Count has been reached. Make sure you have enough room for the pet animation. Shapeshift to detonate all of the Fireworks, killing everyone within radius of each one.


Note: The explosion goes through walls.
The FireWorks can also kill normally between placing fireworks.

Game Options
Name	Description	Type	Default
FireWorks	The probability of the FireWorks appearing	Percentage	0%
Maximum	How many FireWorks should spawn	Number	1
Total Firework Count	How many fireworks can be placed on the map	Number	3
Fireworks Per Round	How many fireworks can be placed per round	Number/Limit	No Limit
┗ Fireworks Ability Cooldown	The cooldown of the FireWorks's ability to plant fireworks (bombs)	Time	20s
Firework Explosion Radius	The Distance a player can be from a Firework and be affected by it's explosion	Number	0.8
Firework Delay	The amount of time it takes from shapeshift for the fireworks to explode	Time	1s
┗ Warn Players Before Explosion	All players within radius get a reactor alarm and text letting them know the firework is about to explode	Toggle	ON
Must Be Last Impostor	Whether the FireWorks can detonate fireworks before they are Last Impostor	Toggle	ON
Freezer


Faction: Impostors
Base: Shapeshifter
Ability: Shapeshift Into A Player To Freeze Them In Place
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Discussions

Role Description
The Freezer can freeze a player in place by shapeshifting into them. The player will be frozen until the Freezer unshapeshifts. Freezer may kill normally shifted or unshifted.

Game Options
Name	Description	Type	Default
Freezer	The probability of the Freezer appearing	Percentage	0%
Maximum	How many Freezers should spawn	Number	1
Freeze Cooldown	The cooldown of the Freezer's Shapeshift Button	Time	20
Freeze Duration	Amount of time that the player is frozen for	Time	10
Can Vent	Whether Freezer can vent or not	Toggle	ON
Grenadier


Faction: Impostor
Base: Impostor
Ability: Blind Nearby Players
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Town of Us Reactivated

Role Description
Using the Pet button sets off a bomb, blinding players in a fixed-distance. It may also blind allied-Impostors, based on host's settings. During this time The Grenadier may kill undetected.

Game Options
Name	Description	Type	Default
Grenadier	The probability of the Grenadier appearing	Percentage	0%
Maximum	How many Grenadiers should spawn	Number	1
Amount of Grenades	How many grenades are granted to the Grenadier	Number	3
Blind Cooldown	The cooldown of the Grenadier's Pet button	Time	30s
Blind Duration	The amount of time that lights are out	Time	15s
Blind Effect Radius	The radius of which players are affected by lights out	Number	1.8
Can Blind Allies	Whether Grenadier can blind allies or not	Toggle	OFF
Can Vent	Whether Grenadier has a vent button or not	Toggle	ON
Identity Thief


Faction: Impostor
Base: Shapeshifter
Ability: Shapeshift Into Your Victim
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by paigecourtney "CC"

Role Description
The Identity Thief shifts into whoever they kill. The disguise lasts until they are ready to kill again, or, optionally, until they kill another player and shift into their next victim.

Game Options
Name	Description	Type	Default
Identity Thief	The probability of the Identity Thief appearing	Percentage	0%
Maximum	How many Identity Thieves should spawn	Number	1
Disguise Settings	Options for how long the Identity Thief stays disguised for	Toggle	Kill CD
Janitor


Faction: Impostor
Base: Impostor
Ability: Clean Bodies With Report Button
Indicatior/Symbols: None

Idea by Town of Us Reactivated

Role Description
Choose between killing and cleaning at the end of kill cooldown. Once the choice is made, the Janitor's Kill Button is reset. Use Report button to clean dead bodies, making them unreportable. Use Kill button to kill players

Game Options (incomplete)
Name	Description	Type	Default
Janitor	The probability of the Janitor appearing	Percentage	0%
Maximum	How many Janitors should spawn	Number	1
Clean On Kill	Whether Janitor cleans bodies when they kill or not	Toggle	ON
┗ Kill Cooldown Multiplier	Multiplier required when Clean On Kill is ON	Multiplier	1.5x
Mafioso


Faction: Impostors
Base: Engineer
Ability: Gain Cash By Completing Tasks
Indicatior/Symbols: Counter Showing Number of Bullets (striked-through until a gun is achieved) AND Cash Counter

Original Role & Idea by Tealeaf/단풍잎

Role Description
The Mafioso is a unique impostor role, who cannot kill off the bat. Instead the Mafioso must complete tasks in order to gain cash. During meetings, the Mafioso can use their cash to purchase a couple of different items.
Type /o to see how much each item costs.
Only items you are able to use/buy will show up in the shop.

Tommy Gun: Allows the Mafioso to kill (one time purchase)
Bullet: Required to use with the Tommy Gun
Bulletproof Vest: Gives the Mafioso one-time use invincibility for next round
Role Revealer: Allows the Mafioso to reveal the role of one other player

Game Options
Name	Description	Type	Default
Mafioso	The probability of the Mafioso appearing	Percentage	0%
Maximum	How many Mafiosos should spawn	Number	1
Modify Shop Costs	Allows for custom costs for Mafioso Shop	Toggle	OFF
┣ Gun Cost	The custom cost of the Tommy Gun	Number	6
┣ Bullet Cost	The custom cost of the bullet	Number	6
┣ Vest Cost	The custom cost of the bulletproof vest	Number	6
┗ Role Revealer Cost	The custom cost of the Role Revealer	Number	5
Starts Game With Gun	Whether Mafioso starts with a gun or not	Toggle	OFF
Gun Cooldown	The cooldown of the Mafioso's Tommy Gun	Number	Global
Cash From Reporting Bodies	Cash received for reporting bodies	Number	2
Refresh Tasks When All Complete	Allows more tasks for Mafioso	Toggle	ON
The Global option for Gun Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Mare


Faction: Impostors
Base: Impostor
Ability: Buffed During Sabotage
Indicatior/Symbols: If Enabled, Your Name Will be Purple During Your Ability

Originally Developed by: Kihi, しゅー, そうくん, ゆりの
Idea by Kihi

Role Description
Mare gains special powers during specific sabotages (determined by host). These powers may include: Increased Speed and Decreased Kill-Cooldown. Be careful! If enabled in settings, your name will appear Purple while your ability is active.

Game Options
Name	Description	Type	Default
Mare	The probability of the Mare appearing	Percentage	0%
Maximum	How many Mares should spawn	Number	1
Speed Modifier During Sabotage	Controls speed boost during sabotages	Number	1.5x
Can Kill Without Sabotage	Whether Mare can kill when there isn't a sabotage	Toggle	ON
┗ Normal Kill Cooldown	Mare's normal Kill cooldown	Time	30s
Colored Name During Sabotage	Whether Mare's name is colored during sabotage	Toggle	ON
Kill Cooldown During Sabotage	Mare's Kill cooldown during a sabotage	Time	15s
Specific Sabotage Settings	Whether Mare's ability can be used during lights only or individual sabotages	Toggle	Lights Only
┣ Lights	Whether Mare can use it's ability during Lights sabotage (All Maps)	Toggle	ON
┣ Communications	Whether Mare can use it's ability during Communications sabotage (All Maps)	Toggle	OFF
┣ Oxygen	Whether Mare can use it's ability during Oxygen sabotage (The Skeld & MIRA HQ)	Toggle	OFF
┣ Reactor	Whether Mare can use it's ability during Reactor sabotage (All Maps)	Toggle	OFF
┗ Crash Course	Whether Mare can use it's ability during Avert Crash Course sabotage (Airship)	Toggle	OFF
Mastermind


Faction: Impostors
Base: Impostor
Ability: Sabotage Meetings
Indicatior/Symbols: "Manipulated!" text on manipulated players

Idea by Gurge 44

Role Description
Mastermind marks a player with their Kill button. After a delay, that player will gain text saying they've been Manipulated, and a countdown will begin. That player must kill another player before their countdown ends (by using either Pet or Kill), otherwise they suicide.

Game Options
Name	Description	Type	Default
Mastermind	The probability of the Mastermind appearing	Percentage	0%
Maximum	How many Masterminds should spawn	Number	1
Manipulation Cooldown	The cooldown of the Manipulator's Kill button	Number	Global
Manipulated Player Limit	How many players can be manipulated	Number	∞
Impostors Can See Manipulated	Whether Impostors can see manipulated players	Toggle	ON
Time Until Suicide	How much time the manipulated player has to kill	Time	12.5s
The Global option for Manipulation Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Miner


Faction: Impostors
Base: Impostor
Ability: Teleportation
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Town of Us Reactivated

Role Description
Use the Pet button to teleport to the last vent used. Make sure you have enough room for the pet animation. Kill, vent, and sabotage like any other impostor role.

Game Options
Name	Description	Type	Default
Miner	The probability of the Miner appearing	Percentage	0%
Maximum	How many Miners should spawn	Number	1
Miner Ability Cooldown	The cooldown on the Miner's teleportation ability	Time	17.5s
Morphling


Faction: Impostors
Base: Shapeshifter
Ability: Can Morph Into Other Players
Indicatior/Symbols: None

Originally Developed by: Innersloth

Role Description
The Morphling can shapeshift themselves into any player that was still alive at the end of the last meeting. It is a renamed Shapeshifter role in vanilla Among Us.

Game Options
Name	Description	Type	Default
Morphling	The probability of the Morphling appearing	Percentage	0%
Maximum	How many Morphlings should spawn	Number	1
Shapeshift Cooldown	The cooldown of the Morphling's Shapeshift button	Time	30s
Shapeshift Duration	The amount of time the Morphling can stay shifted for	Time	15s
Ninja


Faction: Impostors
Base: Shapeshifter or Impostor
Ability: Teleportation
Indicatior/Symbols: Text indicator Displaying Current Mode

Originally Developed by: Discussions
Idea by The Other Roles

Ninja Ability Activation: Shapeshift Button
Use Kill Button while shifted to mark target. When the Ninja unshifts, they will be teleported to their target and complete the kill. Use Kill Button while unshifted to kill normally. Shapeshift duration and cooldown is infinite.

Ninja Ability Activation: Pet Button
Use Pet Button to mark target. Use Pet Button again to teleport to the target and execute the kill. Make sure you have enough room for the pet animation. Use Kill Button like normal if you haven't used the Pet Button to mark a target yet.

Players Teleport to Ninja
With this option the Ninja no longer teleports to the target. Instead, the target is teleported to the Ninja where the kill will be executed.

Game Options
Name	Description	Type	Default
Ninja	The probability of the Ninja appearing	Percentage	0%
Maximum	How many Ninjas should spawn	Number	1
Players Teleport to Ninja	Allows marked players to teleport to Ninja	Toggle	OFF
Ninja Ability Activation	Whether the Ninja uses Shapeshift or Pet to mark target	Toggle	Pet Button
Pickpocket


Faction: Impostors
Base: Impostor
Ability: Steals Votes From Their Kills
Indicatior/Symbols: Counter Displaying Current Vote Increase

Originally Developed by: Discussions
Idea by Discussions

Role Description
The Pickpocket is an Impostor who steals the votes of players they kill. These votes stack up, which can make the Pickpocket very powerful.

Game Options
Name	Description	Type	Default
Pickpocket	The probability of the Pickpocket appearing	Percentage	0%
Maximum	How many Pickpockets should spawn	Number	1
Kill Cooldown	The cooldown of the Pickpocket's Kill button	Time	Global
Maximum Additional Votes	The maximum amount of extra votes the Pickpocket can acquire	Number	5
Resets Votes After Meetings	Whether Pickpocket loses votes after meeting	Toggle	ON
The Global option for Kill Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Puppeteer


Faction: Impostors
Base: Impostor
Ability: Control Players
Indicatior/Symbols: "◆" Indicator On Puppeted Players

Originally Developed by: Discussions
Idea by The Other Roles

Role Description
The Puppeteer can control a player and force them to kill the next non-impostor they come near. Use the Kill button next to a player to gain control over them. If the killed player has an ability that activates upon death, the effect will land on the controlled player instead of the Puppeteer. It is not possible for puppeteer to perform a normal kill.

Game Options
Name	Description	Type	Default
Puppeteer	The probability of the Puppeteer appearing	Percentage	0%
Maximum	How many Puppeteers should spawn	Number	1
Serial Killer


Faction: Impostors
Base: Impostor
Ability: The Impostor's Groupie Indicatior/Symbols: Timer Showing When Serial Killer Is Going To Suicide

Originally Developed by: Town of Host
Idea by Town of Host

Role Description
Has a reduced Kill-Cooldown (determined by host). Kill players before cooldown expires to avoid suicide.

Game Options
Name	Description	Type	Default
Serial Killer	The probability of the Serial Killer appearing	Percentage	0%
Maximum	How many Serial Killers should spawn	Number	1
Kill Cooldown	Cooldown of the Serial Killer's Kill button	Time	7.5s
Time Until Suicide	Amount of time given to the Serial Killer to make a kill	Time	80s
Timer Begins After First Kill	Whether the Suicide Timer begins after the first kill	Toggle	OFF
Sniper


Faction: Impostors
Base: Shapeshifter
Ability: Can Kill From A Far Distance
Indicatior/Symbols: None

Originally Developed by: こう。
Idea by Nebula on the Ship

Normal Sniper Mode
Use Shapeshift button to shift into another player. Take 1-2 steps in the direction you want to fire. Unshift to shoot. A bullet will travel in that direction until it kills a player. When out of bullets, Sniper turns to normal impostor role.

Load Bullet Mode
Use Pet Button to load a bullet and get ready to shoot. Make sure you have enough room to use your pet button. To shoot, the Sniper must take a few steps in the direction they aim to shoot, and then shapeshift.

Game Options
Name	Description	Type	Default
Sniper	The probability of the Sniper appearing	Percentage	0%
Maximum	How many Snipers should spawn	Number	1
Sniper Bullet Count	How many bullets the sniper can shoot	Number	26
Precise Shooting	View Precise shooting diagram below	Toggle	ON
Can Be Vetted on Snipe	The Sniper is affected by the Veteran's ability when using Snipe	Toggle	ON
Sniper Mode	Whether Sniper uses Normal Sniper Mode or Loaded Bullet Mode	Toggle	Normal Sniper Mode
┣ Load Bullet Cooldown	The cooldown between loading bullets	Time	17.5
┗ Max Loaded Bullets	How many bullets you may load in one round	Number	1
Precise Shooting: OFF
off

Precise Shooting: ON
on

Swooper


Faction: Impostor
Base: Impostor
Ability: Invisibility
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Town of Us Reactivated

Role Description
A normal impostor that can go invisible when entering a vent. While invisible, the Swooper can do all normal things (kill, sabotage, vent). Be careful! Depending on the host's options you may be revealed when killing another player.

Game Options
Name	Description	Type	Default
Sniper	The probability of the Swooper appearing	Percentage	0%
Maximum	How many Swoopers should spawn	Number	6
Invisibility Cooldown	The cooldown for the Swooper's Vent Button	Time	45s
Swooping Duration	How long the Swooper can be invisible for	Time	10s
Can Be Seen By Allies	Whether Swooper can be seen by other Impostors	Toggle	ON
Can Vent During Cooldown	Whether the Swooper can vent normally during cooldown or not	Toggle	OFF
Remain Invisible On Kill	Allows Swooper to remain invisible when they kill	Toggle	ON
Time Thief


Faction: Impostors
Base: Impostor
Ability: Decrease Meeting and Voting Time
Indicatior/Symbols: None

Originally Developed by: integral, しゅー, そうくん, ゆりの
Idea by みぃー

Role Description
Killing a player decreases meeting/voting time. Option: When TimeThief is expelled or killed, time is restored back to normal.

Game Options
Name	Description	Type	Default
Time Thief	The probability of the Time Thief appearing	Percentage	0%
Maximum	How many Time Thieves should spawn	Number	1
Meeting Time Stolen	How much time is taken off the Meeting Time per kill	Time	25s
Minimum Voting Time	The lowest amount of time the voting duration can be lowered to.	Time	15s
Return Stolen Time After Death	Whether the meeting/voting time is reverted to original when Time Thief dies	Toggle	ON
Vampire


Faction: Impostors
Base: Impostor
Ability: Delayed Kills
Indicatior/Symbols: None

Originally Developed by: Town of Host
Idea by The Other Roles

Role Description
The Vampire bites it's targets, resulting in a delayed kill. The bitten player will die after several seconds or when the next meeting is called. If the vampire bites Bait, the player will die immediately and a self-report will be forced.

Vampiress


Faction: Impostor
Base Impostor
Ability: Delayed & Normal Kills
Indicatior/Symbols: Text Indicator Showing Current Mode

Originally Developed by: Discussions
Idea by shiftyrose

Vampiress Role Description
The Vampiress works exactly like the Vampire with one exception, it can also make direct kills. Use the Pet Button to switch between Bites and Kills.

Game Options
Name	Description	Type	Default
Vampire	The probability of the Vampire appearing	Percentage	0%
Maximum	How many Vampires should spawn	Number	1
Kill Delay	The amount of time a kill is delayed	Time	7.5s
Vampiress	The probability of the Vampiress appearing	Percentage	0%
┣ Kill Cooldown	The cooldown of the Vampiress's Kill button	Number	Global
┗ Kill Delay	The amount of time a kill is delayed	Time	7.5s
The Global option for Kill Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Warlock


Faction: Impostors
Base: Shapeshifter
Ability: Can Curse Players
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by The Other Roles

Role Description
Use the Kill Button to curse a Player. The next time the Warlock shapeshifts, the cursed player will kill the nearest person. The Warlock may kill normally while shapeshifted. Be Careful! Cursed players can kill Impostors (and even the Warlock themself!).

Game Options
Name	Description	Type	Default
Warlock	The probability of the Warlock appearing	Percentage	0%
Maximum	How many Warlocks should spawn	Number	1
Cursed Players Kill Immediately	Whether cursed players kill immediately	Toggle	ON
┗ Limited Cursed Kill Range	Limits the cursed kill range	Toggle	OFF
Witch


Faction: Impostors
Base: Impostor
Ability: Kill & Curse Players
Indicatior/Symbols: Cross On Cursed Players

Originally Developed by: Town of Host
Idea by The Other Roles

Role Description
Alternate between curses and killing by utilizing the Kill Button. Players who are cursed by the Witch will be seen with a cross during the meeting. If the Witch is not voted off during this meeting, the cursed player dies. Regular kill self-reports Bait. Curse does not self-report Bait.

Game Options
Name	Description	Type	Default
Witch	The probability of the Witch appearing	Percentage	0%
Maximum	How many Witches should spawn	Number	1
Freely Switch Modes	Use Pet Button to switch between Spells and Kills	Toggle	ON
Switch Modes After Attack	Whether Kill/Curse mode automatically switches after attack	Toggle	ON
Yin Yanger


Faction: Impostors
Base: Impostor
Ability: Make Two Players Kill Each Other
Indicatior/Symbols: None

Originally Developed by: Discussions
Idea by Discussions

Role Description
The Yin Yanger is an Impostor with the ability to make two crewmates kill each other. Use the Kill button to tag two players. When they come within kill distance, they will kill each other. Yin Yanger can kill normally once targets have been set.

Game Options
Name	Description	Type	Default
Yin Yanger	The probability of the Yin Yanger appearing	Percentage	0%
Maximum	How many Yin Yangers should spawn	Number	1
Yin Yang Cooldown	The cooldown of the Yin Yanger's ability	Time	Global
The Global option for Yin Yang Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Madmates
CrewPostor


Faction: Neutral
Base: Crewmate
Ability: Kill Nearest Player By Finishing Tasks
Indicatior/Symbols: None
Win Condition: Win With Impostors

Originally Developed by: Discussions
Idea by crewpostor

Role Description
Complete a task to instantly kill the player nearest you (even impostors and other killing roles).

Game Options
Name	Description	Type	Default
CrewPostor	The probability of the CrewPostor appearing	Percentage	0%
Maximum	How many CrewPostors should spawn	Number	1
Warp To Target	Whether CrewPostor warps to target or kills without warping	Toggle	ON
Can Kill Allies	Whether Crewpostor can kill allies or not	Toggle	OFF
Refresh Tasks When All Complete	Allows more tasks for CrewPostor	Toggle	ON
Override CrewPostor's Tasks	Allows the Host to add or remove tasks from CrewPostor	Toggle	OFF
┣ Allow Common Tasks	Whether CrewPostor has Common Tasks or not	Toggle	ON
┣ CrewPostor Long Tasks	How many long tasks CrewPostor has	Number	5
┗ CrewPostor Short Tasks	How many short tasks CrewPostor has	Number	6
Madmate


Faction: Impostors
Base: Engineer
Ability: None
Indicatior/Symbols: None
Win Condition: Win With Impostors

Originally Developed by: Discussions
Idea by libhalt

Role Description
The Madmate is a Impostor sided Crewmate. They are unable to kill and do not know who the Impostors are and the Impostors cannot tell them apart from other Crewmates.

What To Do:
Try to get back into the Impostors good graces.
Act sus. Take suspicion off of Impostors by pretending to fix sabotages, venting, etc.

Game Options
Name	Description	Type	Default
Madmate	The probability of the Madmate appearing	Percentage	0%
Maximum	How many Madmates should spawn	Number	1
Can Sabotage	Whether the Madmate can sabotage	Toggle	ON
Mad Guardian


Faction: Impostors
Base: Crewmate
Ability: Finish Tasks To Become Unkillable
Indicatior/Symbols: None
Win Condition: Win With Impostors

Originally Developed by: 空き瓶/EmptyBottle
Idea by 空き瓶/EmptyBottle

Role Description
The Mad Guardian is an Imposter sided Crewmate who has to do tasks to activate their ability. Madmates do not know who the Impostors are and the Impostors cannot tell who they are from other Crewmates.

What To Do:
Finish tasks to become immune from kills.

Game Options
Name	Description	Type	Default
MadGuardian	The probability of the MadGuardian appearing	Percentage	0%
Maximum	How many MadGuardians should spawn	Number	1
Has Impostor Vision	Whether Mad Guardian has Impostor vision	Toggle	ON
Can Vent	Whether Mad Guardian can vent	Toggle	ON
┣ Vent Cooldown	The cooldown of the Mad Guardian's Vent button	Time	20s
┗ Vent Duration	The duration the Mad Guardian can stay in a vent	Time	9.5s
Override Mad Guardian's Tasks	Allows the Host to add or remove tasks from Mad Guardian	Toggle	OFF
┣ Allow Common Tasks	Whether the Mad Guardian has Common Tasks or not	Toggle	OFF
┣ Mad Guardian Long Tasks	The amount of Long Tasks the Mad Guardian has	Number	5
┗ Mad Guardian Short Tasks	The amount of Short Tasks the Mad Guardian has	Number	6
Mad Snitch


Faction: Impostors
Base: Crewmate or Engineer
Ability: Finish Tasks To See Imps
Indicatior/Symbols: None
Win Condition: Win With Impostors

Originally Developed by: そうくん
Idea by そうくん

Role Description
The Mad Snitch is an Imposter sided Crewmate who has to do tasks to activate their ability. Much like the Snitch, The Mad Snitch must complete tasks to figure out the Imposters to defend them in meetings. They do not know who the Impostors are and the Impostors cannot tell them apart from other Crewmates.

What To Do:
Finish tasks to see who the Impostors are & defend them in meetings.
Has the option to vent.

Game Options
Name	Description	Type	Default
Mad Snitch	The probability of the Mad Snitch appearing	Percentage	0%
Maximum	How many Mad Snitches should spawn	Number	1
Has Impostor Vision	Whether Mad Snitch has Impostor vision	Toggle	ON
Can Vent	Whether Mad Snitch can vent	Toggle	ON
┣ Vent Cooldown	The cooldown of the Mad Snitch's Vent button	Time	20s
┗ Vent Duration	The duration the Mad Snitch can stay in a vent	Time	9.5s
Override Mad Snitch's Tasks	Allows the Host to add or remove tasks from Mad Snitch	Toggle	OFF
┣ Allow Common Tasks	Whether the Mad Snitch has Common Tasks or not	Toggle	OFF
┣ Mad Snitch Long Tasks	The amount of Long Tasks the Mad Snitch has	Number	3
┗ Mad Snitch Short Tasks	The amount of Short Tasks the Mad Snitch has	Number	3
Parasite


Faction: Impostors (MadMates)
Base: Shapeshifter
Ability: Fallen Impostor (Buffed)
Indicatior/Symbols: None
Win Condition: Win With Impostors

Originally Developed by: Discussions
Idea by Loonie

Role Description
The Parasite is an Impostor Sided Killer who is able to kill but doesn't know who the Imposters are and vice versa. The Parasite is able to do everything that a regular imposter can do, and it must work with the Imposters to win together.. If they're still alive, that is. wink

Game Options
Name	Description	Type	Default
Parasite	The probability of the Parasite appearing	Percentage	0%
Maximum	How many Parasite should spawn	Number	1
Kill Cooldown	The cooldown of the Parasites Kill button	Number	Global
The Global option for Kill Cooldown means that this setting will be the same as the Kill Cooldown in Custom Settings from vanilla Among Us

Crewmate
Alchemist


Faction: Crewmate
Base: Crewmate
Ability: Collect Ingredients & Create Potions
Indicator/Symbols:

Ingredients
◆ = Catalyst (Source: Completing Tasks)
Θ = Theta Rift (Source: Random Spawn)
⚠ = Vial of Decay (Source: Dead Bodies)
❀ = Shifting Rose (Source: Shapeshifters)
☀ = Essence of Sight (Source: Fixing Lights)
◯ = Fragment of Discussions (Source: Groups of 3 or more people)

Potions
Potion of Death => Kills the nearest player
Castling Brew => Applies a 1-time use shield to the player
Potion of Sight => Increases players vision for 60 seconds OR removes sabotage vision
Warp Potion => Teleports you and a random player
Mechanic's Mix => Allows player to instant fix next sabotage
Leader Potion => Gives +1 vote during the next meeting
Serene's Grace => Reveals the role of the most nearby player
Unstable Concoction => Mutates into a random potion

Potion Ingredients
Potion of Death: ⚠ Vial of Decay + ◆ Base Catalyst Amount Castling Brew: ◆ (2) Catalyst + ◆ Base Catalyst Amount Potion of Sight: ☀ Essence of Sight + ◆ Base Catalyst Amount Warp Potion: Θ Theta Rift + ◆ Base Catalyst Amount Mechanic's Mix: Fragment of Discussions + ◆ Base Catalyst Amount Leader Potion: Fragment of Discussions + ◆ Base Catalyst Amount Serene Grace: (2) Shifting Rose + ◆ Base Catalyst Amount Unstable Concoction: (2) Theta Rift + ◆ Base Catalyst Amount

Actions:
Long Hold Pet Button*:
Outside Crafting: Brings you to the Crafting Menu
Inside Crafting: Close the Crafting Menu (also creates a potion if selected and all ingredients are collected)
With Potion: Use a crafted potion

Pet Button**:
Outside Crafting: Picks up any ingredients in the area
Inside Crafting: Scrolls through potions

Notes
*Hold pet button long enough that you see the petting animation multiple times.
**Hold pet button just long enough that you only see the petting animation one time.

Role Description
Alchemist is a jack-of-all-trades crewmate role that collects "ingredients". Ingredients can be found in the following ways:
• Catalyst - Found by completing tasks
• Essence of Sight - Found when helping fix lights
• Fragment of Discussions - Found randomly in groups of 3 or more players
• Shifting Rose - Found after a player shapeshifts
• Theta Rift - Found randomly
• Vital of Decay - Found off dead bodies

The Alchemist can use their pet button to pick up these ingredients, and will get a message below their name saying: "Found: [Ingredient Name]".

The Alchemist uses ingredients to craft potions, to switch into "crafting mode" the Alchemist must hold down their pet button. Once in crafting mode, the pet button can be used to switch the next crafted potion.

If in the crafting menu, the Alchemist can hold down their pet button to exit it. If the Alchemist has all of the necessary ingredients to craft the potion they were on, the potion will begin crafting as they hold the pet button.

Once the Alchemist has a potion, they can hold down the pet button to use it, consuming it.

Game Options
Name	Description	Type	Default
Alchemist	The probability of the Alchemist appearing	Percentage	0%
Maximum	How many Alchemists should spawn	Number	1
Base Catalyst Amount	The amount of catalysts needed for potions	Number	2
Potion of Death	Whether Potion of Death is a crafting option	Toggle	ON
Castling Brew	Whether Castling Brew is a crafting option	Toggle	ON
Potion of Sight	Whether Potion of Sight is a crafting option	Toggle	ON
Warp Potion	Whether Warp Potion is a crafting option	Toggle	ON
Mechanic's Mix	Whether Mechanic's Mix is a crafting option	Toggle	ON
Leader Potion	Whether Leader Potion is a crafting option	Toggle	ON
Serene Grace	Whether Serene Grace is a crafting option	Toggle	ON
Unstable Concoction	Whether Unstable Concoction is a crafting option	Toggle	ON
Bastion


Faction: Crewmate
Base: Engineer
Ability: Plant Bombs In Vents
Indicatior/Symbols: Counter Showing Remaining Amount Of Vents They Can Trap

Originally Developed By: Discussions
Idea By: Mek

Role Description
Use the Vent button to plant a bomb in a vent. This will kill the next player who uses that vent. Bombs last for one round only. Vents will be reset at each meeting.

Be careful! The Bastion can bomb themself by using a vent they've already planted a bomb in.

Game Options (incomplete)
Name	Description	Type	Default
Bastion	The probability of the Bastion appearing	Percentage	0%
Maximum	How many Bastions should spawn	Number	1
Plant Bomb Cooldown	The cooldown of the Bastion's Vent button	Time	19.5s
Bombs Per Round	How many bombs can be planted per round	Number	∞
Bodyguard


Faction: Crewmate
Base: Crewmate
Ability: Sacrifice's Their Life To Protect Another
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea By: Det

Role Description
The first player voted becomes the Bodyguard’s Target. This will not count as a vote. Whenever the Bodyguard’s Target is attacked, the attacker is killed alongside the Bodyguard. The Bodyguard may skip freely before their target is locked in and vote freely after their target has been locked in.

Game Options
Name	Description	Type	Default
Bodyguard	The probability of the Bodyguard appearing	Percentage	0%
Maximum	How many Bodyguards should spawn	Number	1
Change Guarded Player	Options for when to change the Guarded player	Toggle	After Death
Protect Against Beneficial Interations	Whether the Bodyguard protects against Beneficial Interactions (e.g. Crusader)	Toggle	OFF
Protect Against Neutral Interactions	Whether the Bodyguard protects agianst Neutral Interactions (e.g. Investigator)	Toggle	ON
Chameleon


Faction: Crewmate
Base: Engineer
Ability: Camouflage With Your Environment
Indicatior/Symbols: Invisible Duration Counter

Original Role & Idea by Tealeaf/단풍잎

Role Description
The Chameleon can use their Vent button to temporarily turn invisible. Their invisible duration is displayed below their name, and after a fixed duration they will re-appear in their current spot.

Game Options
Name	Description	Type	Default
Chameleon	The probability of the Chameleon appearing	Percentage	0%
Maximum	How many Chameleons should spawn	Number	1
Invisibility Duration	The duration of the Chameleon's invisibility	Time	10s
Invisibility Cooldown	The cooldown of the Chameleon's invisibility ability	Time	10s
Vent button cooldown = Invisibility Duration + Invisibility Cooldown

Charmer


Faction: Crewmate
Base: Crewmate
Ability: Charm Enemies To Join Your Team.
Indicatior/Symbols: Charmed Players Receive Indicator That They've Been Charmed

Original Role & Idea by Tealeaf/단풍잎

Role Description
When the Charmer uses their Pet/Kill button on an impostor or neutral killer, they become charmed and join the crewmates team. Charmed players will know they've been charmed, and lose the ability to kill crewmates. If the Charmer charms a crewmate, they misfire and die.

Game Options
Name	Description	Type	Default
Charmer	The probability of the Charmer appearing	Percentage	0%
Maximum	How many Charmer should spawn	Number	1
Ability Button	Choice between Pet/Kill for the Charmer's ability	Toggle	Pet Button
┗ Tasks Needed For Ability	How many tasks need to be completed to use Charm ability	Number	0
Charming Cooldown	The cooldown of the Charmer's Charm ability	Time	60s
Charmed Players Win With Crew	Whether charmed players win with Crewmates	Toggle	ON
Break Charm On Charmer Death	Whether charmed players remain on the Crewmates team upon the Charmer's Death	Toggle	ON
Max Charmed Players	How many players the Charmer can charm onto the Crewmate team	Number	∞
Crusader


Faction: Crewmate
Base: Impostor
Ability: Protect Players From Attacks
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea By: Det

Role Description
The Crusader works like a living Guardian Angel from Vanilla Amoung Us. Use the Kill button to select a target. This target will be protected from attacks.

Game Options
Name	Description	Type	Default
Crusader	The probability of the Crusader appearing	Percentage	0%
Maximum	How many Crusaders should spawn	Number	1
Protect Against Beneficial Interactions	Whether the Crusader protects against Beneficial Interactions (e.g. Crusader)	Toggle	OFF
Protect Against Neutral Interactions	Whether the Crusader protects against Neutral Interactions (e.g. Investigator)	Toggle	ON
Demolitionist


Faction: Crewmate
Base: Crewmate
Ability: Bombs their Killer
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea By: Mek

Role Description
When the Demolitionist is killed, they bomb the ground, giving the killer a few seconds to find a vent. If the killer does not vent in time, they are bombed. The killer is notified that they have killed the demolitionist by their name/role.

Game Options
Name	Description	Type	Default
Demolitionist	The probability of the Demolitionist appearing	Percentage	0%
Maximum	How many Demolitionists should spawn	Number	1
Demo Time	Amount of time the killer has to find a vent	Time	1.5
Dictator


Faction: Crewmate
Base: Crewmate
Ability: Pick Who To Vote Out
Indicatior/Symbols: Counter (During Meetings) Showing Number Of Dictates Before Suicide

Originally Developed By: そうくん
Idea By: そうくん

Role Description
Three things happen when the Dictator votes for someone in meeting:

They forcibly end the meeting.
The player they voted for is exiled.
Sacrifice themself in the name of justice (they die) if they have no more dictate votes left.
Game Options
Name	Description	Type	Default
Dictator	The probability of the Dictator appearing	Percentage	0%
Maximum	How many Dictators should spawn	Number	1
Number of Dictates	How many times Dictator can use their ability	Number	1
┗ Show Dictate at End of Meeting	Shows Dictate message at end of meeting (rather than right away)	Toggle	ON
Suicide if Crewmate Executed	Whether Dictator suicides when executing a Crewmate	Toggle	OFF
Doctor


Faction: Crewmate
Base: Scientist
Ability: Can See How Players Died
Indicatior/Symbols: Cause Of Death Displayed In Meetings

Originally Developed By: Town of Host
Idea By: Nebula on the Ship

Role Description
The Doctor has a portable vitals panel just like the vanilla role, Scientist. Check this regularly to get an approximated time of death. While in meeting (and by closing the chat), the Doctor can see a player’s cause of death in parentheses next to their name.

Game Options
Name	Description	Type	Default
Doctor	The probability of the Doctor appearing	Percentage	0%
Maximum	How many Doctors should spawn	Number	1
Vitals Cooldown	The Cooldown of the Doctor's Vitals button	Time	40s
Vitals Battery Charge	The amount of time the Doctor can View portable vitals	Time	14.5s
Escort


Faction: Crewmate
Base: Impostor
Ability: Role Block Players
Indicatior/Symbols: "RB" Indicator On Roleblocked Player

Originally Developed By: Discussions
Idea By: Loonie

Role Description
Use the Pet button to roleblock
Role blocks prevent kills, reports, and venting.
Cannot roleblock The Glitch.

Game Options
Name	Description	Type	Default
Escort	The probability of the Escort appearing	Percentage	0%
Maximum	How many Escorts should spawn	Number	1
Roleblock Cooldown	The cooldown of the Escort's ability	Time	45s
Roleblock Duration	The duration of the Escort's ability	Time	Until Meeting
Ex-Convict


Faction: Crewmate
Base: Crewmate
Ability: Prepare A Location, Then Escape!
Indicatior/Symbols: Text Cooldown Displaying Time Until Able to Escape & Until Next Mark

Original Role & Idea by Tealeaf/단풍잎

Role Description
First use Pet button to mark a location, then after a set cooldown, you can re-use the Pet button to teleport back to your marked location. This will then put the mark ability back on cooldown.

Game Options
Name	Description	Type	Default
Ex-Convict	The probability of the Ex-Convict appearing	Percentage	0%
Maximum	How many Ex-Convicts should spawn	Number	1
Cooldown After Mark	The cooldown of the Ex-Convict's mark ability	Time	5s
Cooldown After Escape	The cooldown of the Ex-Convict's escape ability	Time	40s
Clear Mark After Meeting	Whether Ex-Convict's mark stays after meeting	Toggle	ON
Herbalist


Faction: Crewmate
Base: Crewmate
Ability: Plant Blooms to Slowly Gather Info
Indicatior/Symbols: Bloom Counter On Seeded Players & Plant Bloom Cooldown Counter

Original Role & Idea by Tealeaf/단풍잎

Role Description
Use your Pet button to plant a seed on a player. After a set period of time, that player's "bloom counter" will increase. After a set number of blooms, use your pet button to reveal that player's role. After a player's role has been revealed, you can continue to reveal it to the nearest player by using the pet button on the same player.

Game Options
Name	Description	Type	Default
Herbalist	The probability of the Herbalist appearing	Percentage	0%
Maximum	How many Herbalists should spawn	Number	1
Time Until Bloom	The amount of time it takes for the seed to bloom	Time	15s
Blooms Until Role Reveal	How many blooms are needed before role reveal	Number	3
Plant Bloom Cooldown	The cooldown of the Herbalist's seed planting ability	Time	20s
Reveal on Bloom	Whether the Herbalist needs to use the pet button to reveal the role on the seeded player	Toggle	OFF
Investigator


Faction: Crewmates
Base: Impostor/Crewmate
Ability: Investigate Roles
Indicatior/Symbols: Player's Name Changes Based On "Good" or "Bad"

Originally Developed By: Discussions
Idea By: Town of Us Reactivated

Role Description
Use the Pet button to investigate if the player is good or bad. In general, red is bad & green is good.

Red = Bad

Impostors (always)
Neutral Killing (predetermined by host)
Neutral Passive (predetermined by host)
Crewmate Killing (predetermined by host)
Madmate (predetermined by host)

Green = Good

Crewmates (always)
Neutral Killing (predetermined by host)
Neutral Passive (predetermined by host)
Crewmate Killing (predetermined by host)
Madmate (predetermined by host)

Game Options
Name	Description	Type	Default
Investigator	The probability of the Investigator appearing	Percentage	0%
Maximum	How many Investigators should spawn	Number	1
Investigate Cooldown	The cooldown of the Investigator's Kill button	Time	27.5s
Neutral Killing are Red	Whether Neutral Killing roles appear red when investigated	Toggle	OFF
┣ AgiTater	Whether AgiTater will show a red name when investiagted	Toggle	Enabled
┣ Arsonist	Whether Arsonist will show a red name when investigated	Toggle	Enabled
┣ Blood Knight	Whether Blood Knight will show a red name when investigated	Toggle	Enabled
┣ Demon	Whether Demon will show a red name when investigated	Toggle	Enabled
┣ Egoist	Whether Egoist will show a red name when investigated	Toggle	Enabled
┣ The Glitch	Whether The Glitch will show a red name when investigated	Toggle	Enabled
┣ Hitman	Whether Hitman will show a red name when investigated	Toggle	Enabled
┣ Jackal	Whether Jackal will show a red name when investigated	Toggle	Enabled
┣ Juggernaut	Whether Juggernaut will show a red name when investigated	Toggle	Enabled
┣ Marksman	Whether Marksman will show a red name when investigated	Toggle	Enabled
┣ Occultist	Whether Occultist will show a red name when investigated	Toggle	Enabled
┣ Pelican	Whether Pelican will show a red name when investigated	Toggle	Enabled
┣ Pestilence	Whether Pestilence will show a red name when investigated	Toggle	Enabled
┣ Plague Bearer	Whether Plague Bearer will show a red name when investigated	Toggle	Enabled
┣ Retributionist	Whether Retributionish will show a red name when investigated	Toggle	Enabled
┣ Ruthless Romantic	Whether Ruthless Romantic will show a red name when investigated	Toggle	Enabled
┗ Werewolf	Whether Werewolf will show a red name when investigated	Toggle	Enabled
Neutral Passive are Red	Whether Neutral Passive roles appear red when investigated	Toggle	OFF
┣ Amalgamation	Whether Amalgamation will show a red name when investigated	Toggle	Enabled
┣ Amnesiac	Whether Amnesiac will show a red name when investigated	Toggle	Enabled
┣ Copycat	Whether Copycat will show a red name when investigated	Toggle	Enabled
┣ Executioner	Whether Executioner will show a red name when investigated	Toggle	Enabled
┣ Hacker	Whether Hacker will show a red name when investigated	Toggle	Enabled
┣ Jester	Whether Jester will show a red name when investigated	Toggle	Enabled
┣ Opportunist	Whether Opporttunist will show a red name when investigated	Toggle	Enabled
┣ Phantom	Whether Phantom will show a red name when investigated	Toggle	Enabled
┣ Postman	Whether Postman will show a red name when investigated	Toggle	Enabled
┣ Schrödinger's Cat	Whether Schrödinger's Cat will show a red name when investigated	Toggle	Enabled
┣ Survivor	Whether Survivor will show a red name when investigated	Toggle	Enabled
┣ Terrorist	Whether Terrorist will show a red name when investigated	Toggle	Enabled
┗ Vulture	Whether Vulture will show a red name when investigated	Toggle	Enabled
Madmates are Red	Whether Madmate roles appear red when investigated	Toggle	OFF
┣ CrewPostor	Whether CrewPostor will show a red name when investigated	Toggle	Enabled
┣ Mad Guardian	Whether Mad Guardian will show a red name when investigated	Toggle	Enabled
┣ Madmate	Whether Madmate will show a red name when investigated	Toggle	Enabled
┣ Mad Snitch	Whether Mad Snitch will show a red name when investigated	Toggle	Enabled
┗ Parasite	Whether Parasite will show a red name when investigated	Toggle	Enabled
Mayor


Faction: Crewmate
Base: Crewmate or Engineer
Ability: Additional Votes / Venting Calls Meetings
Indicatior/Symbols: Counter Showing Number of Pocket Meetings

Originally Developed By: Discussions
Idea By: The Other Roles

Role Description
Mayor’s vote is counted multiple times (predetermined by the host in settings). Depending on the options, they can call emergency meetings by using the Pet button. Additionally, there's an option where Mayor has to reveal before gaining additional votes (reveal by voting yourself)

Game Options
Name	Description	Type	Default
Mayor	The probability of the Mayor appearing	Percentage	0%
Maximum	How many Mayors should spawn	Number	1
Reveal for Votes	Reveal extra votes from Mayor	Toggle	OFF
Mayor Additional Votes	How many additional votes the Mayor has	Number	1
Pocket Meeting	Whether the Mayor has pocket meetings	Toggle	ON
┗ Number Of Uses	How many pocket meetings the Mayor has	Number	3
Mechanic


Faction: Crewmate
Base: Engineer
Ability: Use Vents
Indicatior/Symbols: None

Originally Developed By: Innersloth

Role Description
The Mechanic can use vents to travel around the map. They are restricted by the Vent Use Cooldown & Max Time In Vents Options used for vanilla Engineer. The Mechanic is a renamed Engineer from vanilla Among Us.

Game Options
Name	Description	Type	Default
Mechanic	The probability of the Mechanic appearing	Percentage	0%
Maximum	How many Mechanics should spawn	Number	1
Vent Cooldown	The cooldown of the Mechanic's Vent button	Time	40s
Vent Duration	The amount of time the Mechanic can stay in a vent	Time	14.5s
Medic


Faction: Crewmate
Base: Crewmate
Ability: Shield a Player From Attacks
Indicatior/Symbols: Small "+" Mark Showing Shielded Player

Originally Developed By: Discussions
Idea By: Town of Us Reactivated

Role Description
The Medic is able to vote a player to shield. Based on host's options, the Medic may be able to change their protected player during following meetings.

Game Options
Name	Description	Type	Default
Medic	The probability of the Medic appearing	Percentage	0%
Maximum	How many Medics should spawn	Number	1
Change Guarded Player	Options for if/when to change guarded player	Toggle	After Death
Medium


Faction: Crewmate
Base: Crewmate
Ability: Reveal The Killers Role When Reporting
Indicatior/Symbols: Medium

Originally Developed By: Discussions
Idea By: Town of Us Reactivated

Role Description
Use the Report button to report a body.
In meeting chat, the Medium will receive a message revealing the role of the reported player's killer. Medium can only see killer's role if they reported the body themselves. Depending on host's settings, they may also see an arrow pointing to bodies.

Game Options
Name	Description	Type	Default
Medium	The probability of the Medium appearing	Percentage	0%
Maximum	How many Mediums should spawn	Number	1
Has Arrows to Bodies	Whether the Medium will see an arrow point to bodies	Toggle	OFF
Mystic


Faction: Crewmate
Base: Crewmate
Ability: Notified When Players Are Killed
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea By: Town of Us Reactivated

Role Description
When a player is killed, Mystic receives a single flash and alert. It is very similar to when the reactor is sabotaged. Use this alert to estimate time of death.

Game Options
Name	Description	Type	Default
Mystic	The probability of the Mystic appearing	Percentage	0%
Maximum	How many Mystics should spawn	Number	1
Mystic is a Modifier	Whether Mystic is a Modifier instead of a role	Toggle	OFF
Flash Duration	Amount of time a Flash alert is present	Time	0.5s
Send Audio Alert	Whether there is an audio alert	ON/OFF	ON
Observer


Faction: Crewmate
Base: Crewmate
Ability: Increased Vision
Indicatior/Symbols: None

Original Role & Idea by Tealeaf/단풍잎

Role Description
Finish tasks to gain vision. Depending on the host's options, you may gain a small vision boost upon completing each task, or, a large vision boost when all tasks have been complete.

Game Options
Name	Description	Type	Default
Observer	The probability of the Observer appearing	Percentage	0%
Maximum	How many Obervers should spawn	Number	1
Slowly Gains Vision	Whether the Observer gains vision with each task completed or total task completion	Toggle	OFF
┗ Vision Gain On Task Complete	The amount of vision increase the Observer receives for each task they complete	Multiplier	0.15x
Override Starting Vision	Whether Observer starts with a different vision other than default	Toggle	OFF
┗ Starting Vision Modifier	How much vision the Observer has before any tasks are completed	Multiplier	0.25x
Finished Tasked Vision	The final vision distance Observer has when all tasks are completed	Multiplier	2.25x
Lights Immunity If Tasks Finished	Whether Observer is unaffected by Lights Sabotage or not	Toggle	ON
Oracle


Faction: Crewmate
Base: Crewmate
Ability: Reveal A Role Upon Death
Indicatior/Symbols: After the Oracle dies, the targeted player will have their role shown to everyone with a bluish-purple gradient

Originally Developed By: Discussions
Idea By: Det

Role Description
The first player voted by the Oracle becomes the Oracle’s Target. This will not count as a vote. When the Oracle dies, the Target’s role is revealed to everyone. The Oracle may skip freely before their target is locked in and vote freely after their target has been locked in. The Oracle can choose to reveal their own role if they wish by voting themselves.

Game Options
Name	Description	Type	Default
Oracle	The probability of the Oracle appearing	Percentage	0%
Maximum	How many Oracles should spawn	Number	1
Physicist


Faction: Crewmate
Base: Scientist
Ability: Can See Vitals
Indicatior/Symbols: None

Originally Developed By: Innersloth

Role Description
The Physicists have a portable vitals monitor that can be accessed anywhere on the map. The Physicist is a renamed Scientist from vanilla Amoung Us.

Game Options
Name	Description	Type	Default
Physicist	The probability of the Physicist appearing	Percentage	0%
Maximum	How many Physicists should spawn	Number	1
Vitals Cooldown	The Cooldown of the Physicist's Vitals button	Time	40s
Vitals Battery Charge	The amount of time the Physicist can View portable vitals	Time	14.5s
Psychic


Faction: Crewmates
Base: Crewmate
Ability: See A Potential Evil Player
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea By: Loonie

Role Description
The Psychic has the ability to see potential evils during a meeting. Three players will be highlighted in red, at least one of them is evil. The number of players highlighted can be adjusted by the host.

Game Options (incomplete)
Name	Description	Type	Default
Psychic	The probability of the Psychic appearing	Percentage	0%
Maximum	How many Psychics should spawn	Number	1
Highlighted Players	How many players are highlighted during meeting	Number	3
All Killing Roles are Evil	Whether all killing roles are considered evil (including sheriff)	Toggle	ON
Repairman


Faction: Crewmates
Base: Crewmate/Engineer
Ability: Clear Sabotages Without Help
Indicatior/Symbols: None

Originally Developed By: 空き瓶/EmptyBottle
Idea By: 空き瓶/EmptyBottle (SabotageMaster)

Role Description
Repairman can fast-fix sabotages that typically require two players (e.g. reactor) on their own. Lights can be fixed by touching a single lever. Opening a door in Polus or The Airship will open all the linked doors.

Game Options
Name	Description	Type	Default
Repairman	The probability of the Repairman appearing	Percentage	0%
Maximum	How many Repairmans should spawn	Number	1
Repairman Can Vent	Whether the Repairman can vent	Toggle	ON
┣ Vent Cooldown	The cooldown of the Repairman's vent button	Time	40s
┗ Vent Duration	How long the Repairman can stay inside a vent	Time	15s
Fast Fixes Lights	Whether Repairman can fast-fix Lights	Toggle	ON
Fast Fixes Reactor	Whether Repairman can fast-fix Reactor	Toggle	ON
Fast Fixes Oxygen	Whether Repairman can fast-fix Oxygen	Toggle	ON
Fast Fixes Communications	Whether Repairman can fast-fix Communications	Toggle	ON
Fast Fixes Doors	Whether Repairman can fast-fix Doors	Toggle	ON
Fast Fixes Crash Course	Whether Repairman can fast-fix Crash Course	Toggle	ON
Sheriff


Faction: Crewmate
Base: Impostor/Crewmate
Ability: Can Shoot Impostors
Indicatior/Symbols: Counter showing number of bullets

Originally Developed By: Town of Host
Idea From: Woodi-dev

Role Description
The Sheriff can kill Impostors. Be Careful! The Sheriff will misfire (kill themself) if they shoot a crewmate or a neutral not allowed by host. Additionally (depending on settings) they may have no tasks.

Game Options
Name	Description	Type	Default
Sheriff	The probability of the Sheriff appearing	Percentage	0%
Maximum	How many Sheriffs should spawn	Number	1
Kill Target On Misfire	Whether Sheriff will kill their target when misfiring	Toggle	OFF
Kill Cooldown	The Cooldown for the Sheriff's Kill/Pet button	Time	25s
Total Shots	The total amount of shots (kills) the Sheriff can make	Number	5
One Shot Per Round	Whether the Sheriff can make multiple shots per round or not	Toggle	ON
Sheriff Action Button	Toggles the Kill/Pet Button for the Sheriff's ability	Toggle	Kill
Snitch


Faction: Crewmate
Base: Crewmate
Ability: Finish Tasks To See Killers
Indicatior/Symbols: ⚠ indicator when on task threshold

Originally Developed By: Town of Host
Idea From: The Other Roles

Role Description
The Snitch can see Impostors (has option to see any neutral killers as well) once tasks are complete. When the Snitch has a certain number of tasks left (predetermined based on host's settings), they will be revealed to the killers with a ⚠ indicator. Depending on the settings, when their tasks are completed, the Snitch may also see arrows pointed in the direction of each player they're tracking.

Game Options
Name	Description	Type	Default
Snitch	The probability of the Snitch appearing	Percentage	0%
Maximum	How many Snitches should spawn	Number	1
Remaining Task Warning	How many tasks the Snitch will have remaining to alert the killers	Number	2
Evil Have Arrow to Snitch	Whether evil players will have an arrow to the Snitch	Toggle	ON
Enable Arrow for Snitch	Whether the Snitch will have arrows to the killers	Toggle	ON
┗ Colored Arrow	Whether the arrows are colored based on role color	Toggle	ON
Snitch can Track Any Killing	Whether Snitch can track any killers	Toggle	ON
Override Snitch's Tasks	Options to customize Snitch's tasks	Toggle	OFF
┣ Allow Common Tasks	Whether the Snitch will receive Common Tasks	Toggle	ON
┣ Snitch Long Tasks	How many Long Tasks will be assigned to the Snitch	Number	5
┗ Snitch Short Tasks	How many Short Tasks will be assigned to the Snitch	Number	6
Speedrunner


Faction: Crewmates
Base: Crewmate
Ability: Increased Speed Upon Task Completion
Indicatior/Symbols: None

Original Role & Idea by Tealeaf/단풍잎

Role Description
Finish tasks to gain a speed boost! Depending on the host's options, you may gain a small speed boost (possibly temporarily depending on settings) after completing singular tasks, or, get a large speed boost after reaching a task-threshold.

Game Options
Name	Description	Type	Default
Speedrunner	The probability of the Speedrunner appearing	Percentage	0%
Maximum	How many Speedrunners should spawn	Number	1
Temporary Boost Upon Finishing Task	Whether the Speedrunner will receive a temporary small boost after finishing each task	Multiplier	0.1x
┗ Temporary Boost Duration	How long the temporary speed boost lasts after each completed task	Time	3s
Permanent Speed Gain per Task	How much of a permanent boost the Speedrunner gets after completing each task	Multiplier	0.1x
Tasks Remaining Until Main Speed Boost	How many tasks need to be completed to receive Final Speed Boost	Number	2
┗ Final Speed Boost	Final Player Speed when Speedrunner completes Tasks Until Speed Boost	Multiplier	2.25x
Swapper


Faction: Crewmate
Base: Crewmate
Ability: Swap Votes During Meeting
Indicatior/Symbols: None

Idea From: Town of Us Reactivated

Role Description
The first two players you vote each meeting will have their votes swapped. After voting those players, you may vote as normal. Alternatively, you can skip at the start and continue to normal voting.

Game Options
Name	Description	Type	Default
Swapper	The probability of the Swapper appearing	Percentage	0%
Maximum	How many Swappers should spawn	Number	1
Swaps Per Game	How many votes the Swapper can swap per game	Number	∞
Tracker


Faction: Crewmate
Base: Crewmate
Ability: Track a player's movements
Indicatior/Symbols: Arrow Pointing Towards Tracked Player

Idea From: Town of Us Reactivated

Role Description
Once per meeting, select a player to track. You will have an arrow pointing towards that player until they die. If enabled, you may also use your pet button to temporarily track all dead bodies.

Game Options
Name	Description	Type	Default
Tracker	The probability of the Tracker appearing	Percentage	0%
Maximum	How many Trackers should spawn	Number	1
Arrow Update Rate	The rate at which your tracking arrown updates	Time	1s
Can Track Bodies	If the Pet button ca nbe used to track bodies	Toggle	OFF
┣ Can Track Unreportable Bodies	If, when tracking bodies, unreportable bodies are shown	Toggle	ON
┣ Track Body Duration	The duration of the body tracking ability	Time	12.5s
┗ Track Body Cooldown	The cooldown of the body tracking ability	Time	40s
Transporter


Faction: Crewmate
Base: Crewmate
Ability: Transport Two Players
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea From: Town of Us Reactivated

Role Description
Use the Pet button and cause two random players to switch places. Make sure you have enough for the pet animation.

Game Options
Name	Description	Type	Default
Transporter	The probability of the Transporter appearing	Percentage	0%
Maximum	How many Transporters should spawn	Number	1
Number of Transports	How many times the Transporter may use it's ability	Number	25
Transport Cooldown	The cooldown of the Transport ability	Time	30
Trapster


Faction: Crewmates
Base: Crewmate
Ability: Trap Their Killers
Indicatior/Symbols: None

Originally Developed By: そうくん
Idea By: 宿主ランニング

Role Description
Upon death, Trapster freezes their killer in place for a few seconds.

Game Options
Name	Description	Type	Default
Trapster	The probability of the Trapster appearing	Percentage	0%
Maximum	How many Trapsters should spawn	Number	1
Traps on Indirect Kills	Whether the Trapster's ability works on indirect kills	Toggle	ON
Trapped Duration	The amount of time the killer is trapped for	Time	5s
Veteran


Faction: Crewmate
Base: Crewmate
Ability: Counterattacks Players' Kill Button
Indicatior/Symbols: None

Originally Developed By: Discussions
Idea From: Town of Us Reactivated

Role Description
When the Veteran is attacked while on Alert, the attack will backfire resulting in the attacker's death. Use the Pet button to activate the Veteran's ability. Pro Tip - Make sure you have enough room for the Pet animation!

Game Options
Name	Description	Type	Default
Veteran	The probability of the Veteran appearing	Percentage	0%
Maximum	How many Veterans should spawn	Number	1
Number of Alerts	How many times the Veteran can Alert (protect themself from attack)	Number	10
Alert Cooldown	The Cooldown between Pet Button Usage (Alerts)	Time	15s
Alert Duration	The amount of time the Veteran is Alerted for	Time	3.5s
Kill Crewmates	Whether the Veteran can kill Crewmates or not	Toggle	ON
Kill While Transported	Wether the Veteran can kill the player they're transported with	Toggle	ON
Kill Ranged Attackers	Whether the Veteran can kill Ranged Attackers (e.g. Crewpostor)	Toggle	ON
Vigilante


Faction: Crewmate
Base: Crewmate
Ability: Guess Evil Roles To Eliminate Them
Indicatior/Symbols: None

Originally Developed By: たんぽぽ
Idea From: Town of Us Reactivated

Role Description
Vigilante is a nice guesser and part of the crewmate team. While in meeting the Vigilante's first vote locks in the player they're going to guess. Then the Vigilante uses a chat command to guess the role (i.e. /r [role]). The Vigilante's second guess locks in the guess. The Vigilante suicides if they misguess.

Game Options
Name	Description	Type	Default
Vigilante	The probability of the Vigilante appearing	Percentage	0%
Maximum	How many Vigilantes should spawn	Number	1
Neutral Killing
AgiTater


Faction: Neutral Killing
Base: Impostor
Ability: Pass The Bomb (Hot Potato)
Win Condition: Be The Last Man Standing

Originally Developed by: Discussions
Idea by Aaron Stuart

Role Description
As an AgiTater your goal is to give your bomb to another player using your kill button. Once another player is in range, the bomb will automatically be passed to them. This continues until a meeting is called (or optionally after a duration) where the last person holding the bomb is then eliminated.

Game Options (incomplete)
Name	Description	Type	Default
AgiTater	The probability of the AgiTater appearing	Percentage	0%
Maximum	How many AgiTaters should spawn	Number	1
Place Bomb Cooldown	The cooldown of the AgiTater's ability to place bombs	Number	Global
Explode On Meetings	Whether bombed players explode when a meeting is called	Toggle	ON
Explode After Duration	Whether bombed players will explode after a specific amount of time has passed	Toggle	OFF
Explode When Bombed Twice	Whether bombed players will explode if they get a bomb for the second time	Toggle	OFF
Bombs per Round	How many bombs can be placed per round	Number	3
Bomb Transfer Rate	The time someone needs to be next to a player for the bomb to transfer	Time	1s
The Global option for Place Bomb Cooldown means that this setting will be the same as the 
