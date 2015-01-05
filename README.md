#EpicQuest, The ultimate, lightweight quest plugin!

EpicQuest is an easy to use yet highly customizable quest plugin. Immerse your players into Minecraft with a commandless questing experience through villagers, bounty signs and a book to show your progress!

**Quests Villagers Tips WARNING! If you are upgrading to 3.1, be sure to read the changelog! Your plugin will BREAK if you don't!**

##Features:
* Multiple tasks per quest
* Multiple quests at the same time
* Quest types:
  * Collect
  * Kill
  * Killplayer
  * Killanyplayer
  * Destroy
  * Place
  * Levelup
  * Enchant
  * Tame
  * Craft
  * Smelt
  * TalkToVillager
  * Killanymob
  * Killmobbyname
  * Repair
  * Goto
  * Clickblock
  * Executecommand
* Quest rewards:
  * Money (Vault)
  * Items
  * Permission group (Vault)
  * Commands execution
  * Heroes Experience
* Supported plugins:
  * Citizens
  * Heroes
  * MythicMobs and all other custom mob plugins through the "Kill Mob By Name" quest type
* Progress a quest in only the specified worlds
* Player statistics
* Permissions
* Quest requirements
* Quest lock time after finish (for daily quests and the likes)
* Sign support
* Any block as quest-giver
* Spawn villagers who give quests
* Party functionality
* Check which quests you have in a book - no commands! -
* Includes Vault integration

###Coming Soon:
* RPG Items support (collect quest type and rewards)
* BarAPI for progress tracking

##Commands
You must use either /q or /quest to precede the following commands:

Command	| Description | Permission
------- | ----------- | ----------
give | Give random quest | epicquest.user.give
give <number> | Give specified quest from the QuestList	| epicquest.user.give
turnin | Turn all your quests in | epicquest.user.turnin
questbook or qb	| Shows the quests you have	| epicquest.user.questbook
info <number> | Shows info on the specified quest from the QuestBook | epicquest.user.info
drop <number> | Drops the specified quest from the QuestBook | epicquest.user.drop
stats <playername> | Shows player statistics | epicquest.user.stats
help | Shows help pages | epicquest.user.help
questblock <give/turnin> <(if give)random/questnumber> | Options for the block you're looking at | epicquest.admin.questblock
party | Shows party members | epicquest.user.party
party invite <playername> | Invites a player to your party | epicquest.user.party
party accept | Accepts the current party invitation	| epicquest.user.party
party kick <playername>	| Kicks a player from your party if you are leader | epicquest.user.party
party leader <playername> | Makes somebody else the party leader | epicquest.user.party
party leave	| Leave your current party | epicquest.user.party
party chat | Toggles party chat | epicquest.user.party
questentity create <name> <quest> | Spawns a villager with a quest. Check the questentities.yml file after reloading the server for more advanced options! | epicquest.admin.questentity
questentity create <name> | Select a Citizen after this command to make him give quests. Check the questentities.yml file after reloading the server for more advanced options! | epicquest.admin.questentity
questentity remove <name> | Remove a villager with a quest | epicquest.admin.questentity
reload | Reload quests from the quests file | epicquest.admin.reload

##How to use
####[Quests](http://dev.bukkit.org/bukkit-plugins/epicquest/pages/creating-quests/)
####[Quest Givers](http://dev.bukkit.org/bukkit-plugins/epicquest/pages/how-to-use-quest-givers/)
####[Tips and Tricks](http://dev.bukkit.org/bukkit-plugins/epicquest/pages/tips-and-tricks/)
####[Sharing Quests](http://dev.bukkit.org/server-mods/epicquest/pages/quest-sharing/)

##Contribute!
Feel like you want to help EpicQuest improve? Simply clone the repo and away you go. I'll be more than happy to accept fork requests as long as it's a beneficial contribution towards EpicQuest; however, even a small change, even like changing up the README.md or fixing a slight bug will do just fine! Be sure to update your repo before starting on something!
