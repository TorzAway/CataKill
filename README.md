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
Debugging=FALSE  (Turn Debugging On/Off)
AssistMe=TRUE
CheckBots=TRUE
DoBurns=FALSE
SwarmPull=FALSE
BiggerSwarms=FALSE
RepeatMission=TRUE
GroupNavToMe=TRUE
UseClickBuffs=FALSE
UseClickDamage=FALSE
UseMq2Melee=FALSE
LootCorpse=TRUE
LootMethod=DCONLY

[Camp]
CampRadius=2500

[Pull]
ZRadius=500
PullAbility=ReplaceMeWithYourSkill
PullAbilityRange=30
PullRequiresLineOfSight=TRUE
UseCastSpells=FALSE

[BardSong]
BRDTravelSongSlot=11
BRDMelodyName=base

[Endurance]
MedEndAt=30
MedEndTill=95

[Mana]
MedAt=30
MedTill=95
BardMed=TRUE

[Alerts]
AFKGM=TRUE		( Go AFK if a GM is detected ?)
UseBeep=TRUE	( BEEP if a GM is detected ?)

[Theme]


