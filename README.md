# CataKill
A MacroQuest macro to automate killing (Single or SpawnPull system) in Catacombs of Dranik (Caza) Expeditions.

This macro will keep track and be able to pick up where you left off at any point if you /END and restart the macro.

Valid Starting Zones:
Temple of Marrs
Plane of Knowledge
The Nexus
Ruined City of Dranik

InI File:
MQ\Config\CataKill_[ToonName].ini

InI Setings Explained:

[General]
-
Debugging=FALSE  (Turn Debugging On/Off)
-
AssistMe=TRUE
-
CheckBots=TRUE
-
DoBurns=FALSE
-
SwarmPull=FALSE    (Turn to TRUE for SarmPulls / FALSE for SinglePulls)
-
BiggerSwarms=FALSE  (Turn to TRUE for BIGGER SwarmPulls (whole Corridors) / FALSE for standard room pulls)
-
RepeatMission=TRUE  (Turn to TRUE for REGET the expedition when it ends / FALSE to gate to Temple of Marrs and CAMP when it ends)
-
GroupNavToMe=TRUE
-
UseClickBuffs=FALSE
-
UseClickDamage=FALSE
-
UseMq2Melee=FALSE    (Turn to TRUE to Enable Mq2Melee plugin / FALSE to Disable Mq2Melee plugin)
-
LootCorpse=TRUE    (Turn to TRUE to Loot corpses)
-
LootMethod=DCONLY  (OPTIONS: DCONLY to loot Diamond COin and HIGH VALUE stackable items / E3 to have E# system handle all looting)
---
---
[Camp]
-
CampRadius=2500
---
---
[Pull]
-
ZRadius=500
---
PullAbility=ReplaceMeWithYourSkill 
---
PullAbilityRange=30
---
PullRequiresLineOfSight=TRUE
---
UseCastSpells=FALSE  ( HardForce your driver to cast his detrimental memorized spells in combat )
---
---
[BardSong]
-
BRDTravelSongSlot=11  ( BEEP if a GM is detected ?)
---
BRDMelodyName=base  ( BEEP if a GM is detected ?)
---
---
[Endurance]
-
MedEndAt=30
---
MedEndTill=95
---
---
[Mana]
-
MedAt=30
---
MedTill=95
---
BardMed=TRUE  ( BEEP if a GM is detected ?)
---
---
[Alerts]
-
AFKGM=TRUE		( Go AFK if a GM is detected ?)
---
UseBeep=TRUE	( BEEP if a GM is detected ?)
---
---
[Theme]
-
[DO NOT ALTER OR EDIT THESE]

