# Imperial GMOD

Changelog for Imperial GMOD DarkRP server.

---
### February 4th, 2016
* Fixed food mod not appearing
* Capped max level at 99
* Added 'Food Chef' job
* Changed TEAM_THIEF limit to 3
* Changed TEAM_GANG limit to 4
* Fixed world entities from being deleted
* Added 'Mayors Daughter' job (Level 10)
* Added 'Scientist' job (Level 15)
* Split VIP jobs into a new category
* Added 'Activist' job
* Added Angry Hobo SWEP for hobo classes

### January 28th, 2016
* New Commands: !resetnlr, !resetlevel, !resetspawm, !resetwarns, !buyvip
* Documentation updated in T-Admin Module
* Restricted Trained Thief to level 4
* Added more props to spam whitelist
* Edited !buyvip so pre-existing vip and staff can't buy it (Staff, talk to Jazzar)
* Player gains XP by performing certain actions in-game
* Added admin menu for T-Admin commands. Use !tadmin
* Fixed chat still appearing when using T-Admin command

### January 27th, 2016
* NLR detection system done
* Level system done w/ global variables
* Made police jobs require a level of 5
* Added new T-Admin Commands (see the forums for details)
* Time tracking script done
* OwnerHUD fixed
* Fixed bug with warning system not banning properly

### January 25th, 2016
* Created anti-prop crash system. Alerts admins on possible server crashers.
* Added edible foods mod
* Gave service workers the ability to sell food
* NLR timer added
* Gave noclip perms to moderators

### January 24th, 2016
* Added reason to kick message for T-Admin
* Taxrate change message fixed from displaying decimal value instead of percent
* Fixed not being able to OOC chat from certain commands (sub.string issue)
* Gave TEAM_TERRORIST lockpick
* Adjusted hit price to $3000, set cooldown per client to 10 minutes.
* Fixed T-Pose with shop manager.

#### New Staff:
* Uncle Shoes (Sinister) [STEAM_0:0:77549325]

### January 23rd, 2016
* Removed taser swep due to abuse
* Fixed terrorist having police sweps
* Added 'Staff on Duty' job
* Added reason to !warn system. Usage: !warn 'player name' RDM
* Set sbox_maxtextscreens from 1 to 3
* Fixed exploit with players dropping weapons and inventorying them
* Changed website software from MyBB to phpBB
* Added new style for website
* Rule updates for basing and job-specific
* Added 'Communications Collection Terms' to MOTD
* Disabled 'Needs Approval' admin function on website
* Added "Damage Players in Seats' (http://steamcommunity.com/sharedfiles/filedetails/?id=428278317)
* Added 'Seat Weaponiser 2' (http://steamcommunity.com/sharedfiles/filedetails/?id=601411453)
* Fixed map not downloading to client (Whoops, probably why we have had low population)
* Added loading screen for new clients
* Added Arnold job for VIP. 
* Created "Arnold Yelling" swep. (NOTE: ADMINS PLEASE GIVE THIS A TRY ITS IN 'OTHER' WEAPONS)

### January 22nd, 2016
* Added PermaProps for admins 
* Replaced old stacker tool with non-exploitable version
* Fixed exploit for unlimited entities via. inventory
* Added Smart Weld
* Made some textscreens around the map
* Added benches, props, etc around the map for scenic appeal
* Fixed FailRP exploit using safe zone to get full health
* T-Admin Administration HUD in beta. Owner module preview done (http://i.imgur.com/caGDrx3.jpg)
Includes player logging, information, getip function, and more. Need to add warns count.

### January 21st, 2016
* Added Door STool (http://steamcommunity.com/sharedfiles/filedetails/?id=104479467)
* Added Taser http://steamcommunity.com/sharedfiles/filedetails/?id=578333531
* Added SmartSnap (http://steamcommunity.com/sharedfiles/filedetails/?id=588721781)
* Added precision tool
* Server automatically cleans up disconnected props every five minutes
* Adjust Job Instructions for new VIP jobs

### January 20th, 2016
* Fixed warns jumping from 1 to 3
* Changed jobs that can raid (like thief, underground) to gray to avoid confusion.
* Changed Bitcoin Miner limit to 3. 
* Bitcoin sell price changed from $100 to $200 per BTC
* Added VIP Bitcoin Miner.

### January 19th, 2016
* Disallowed clientside scripts in settings.lua
* Dedicated Teamspeak w/ Ranks (ts.imperialgmod.com)
* Moved webhost and FastDL over to new Los Angeles host
* Made !needadmin requests bright green
* !taxrate function fixed
* Fixed moderators not seeing !needadmin requests
* Warn system is now working. Usage: !warn 'playername'. There is NO warn reason. The name must be between the ' character.
* VIP thread created. VIP donation section on index updated.
* Prevented users from crashing server with Creator tool.

---

### January 18th, 2016
* Added inventory system to server (https://scriptfodder.com/scripts/view/15)
* Fixed an exploit with TEAM_DRUG that crashed the server.

---

### Before January 18th, 2016

##### Addon Additions
* Added TDMCars
* Sit Anywhere addon

##### Exploits Patches and Fixes
* Installed CAC

##### DarkRP Gamemode Changes
* More guns like m9k_remington1858 for handgun dealer
* Mayor needs to lose job on death
* Fix t-posing models
* Remove Police Sniper
 
##### T-Admin System
* [T-Admin] Add attacker swep logging
* Damage log system for admins
* Spawn Safe Zone
* Admin help needs to go in chat as well !needadmin
* Warn system should display globally that someone was warned

##### Custom Addon Changes
* Adjust btc mining rate
* Change position for spawn btc exchange

##### VIP System
* Added 8 unique jobs for VIP
