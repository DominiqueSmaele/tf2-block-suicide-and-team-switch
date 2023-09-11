# About
I wrote this plugin for my Deathrun server, preventing the Activator from killing himself in various ways. Was pretty messy, so I thought I'd rewrite it.

I think I made it as efficiently as possible, but this is my first plugin so... If you have any recommendations on how to improve my code, definitely share!

# What will this plugin block?
- Kill
- Explode
- Jointeam


# ConVars
sm_blockSuicide_enabled (1) - Enable or disable this plugin
sm_allowOverride (1) - Allow or disallow overrides for suicides and team switches?
sm_blockKillTeam (0) - Which team to block kill for? (0 = No team, 1 = Team RED, 2 = TEAM BLUE, 3 = Both teams)
sm_blockExplodeTeam (0) - Which team to block explode for? (0 = No team, 1 = Team RED, 2 = TEAM BLUE, 3 = Both teams)
sm_blockSwitchTeam (0) - Which team to block switching teams for? (0 = No team, 1 = Team RED, 2 = TEAM BLUE, 3 = Both teams)
sm_allowSpectate (1) - Allow or disallow switching to spectate?
sm_allowSpectateTeam (0) - Allow spectate for which team? (0 = Both teams, 1 = Team RED, 2 = Team BLUE)


# Overrides
- suicideandteamswitch_override


By default the flag is "b" (admins).

# Compile Requirements
- Morecolors.inc


# Installation
- Put the .smx into tf/addons/sourcemod/plugins folder
- Put the plugin.blocksuicide.cfg in tf/cfg/sourcemod folder
- Put the blockSuicide.phrases.txt in tf/addons/sourcemod/translations folder
- Restart your server
