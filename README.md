# trinitycore-patches
=======
Official test server:
set realmlist logon.realmsofwarcraft.com
Test realm: Dark Psyon

Create an account at http://www.realmsofwarcraft.com

I will update this as often as I can. Below is a list of patches.
I will start with the ALL patch. Apply Bots patch of your choice after applying ALL

* **ALL without any bots** - All patches in Individual folder (Player_Events not included)

I am also accepting donations. I am only adding this because a few people have asked how to donate. I never
thought about it, and never expected to get donations. I do this because I enjoy it. If you want to donate,
I won't deny you, but I will not be upset if you don't.

to donate, go here: http://www.realmsofwarcraft.com/donate.php or make a donation through paypal... realmsofwarcraft@gmail.com

Here is a list of the patches, and a detailed description of each. (Not finished, but working on it.)

* **255_in_who_list.patch** - 3.3.5a is designed for level 70 and the "who" list will only display up to level 99. This allows for higher levels to be displayed.
* **ArenaGambler.patch** - Someone give me a good description of this. I am assuming you bet on the winner of a battle in an arena.
* **Arena_Template.patch** - This patch replaces 1v1 arena patch. THis has 1v1 and 3v3 arena options.
* **Cheats-FastFishing-AttackAndRespawnSpeed.patch** - Configurable extras such as fast fishing, attack and respawn speed and others. Configs in worldserver.conf.
* **CongratsOnLevel.patch** (broken) - Small script that gives a reward for playing the game. Currently set for 2 items, gold and a spell for each 10 levels obtained.
* **CrossFactionBG.patch** - Cool but buggy patch that allows a player to choose a different faction for BG. it changes the character to the new faction, giving them skills etc for that faction. Character reverts back to normal after bg finishes. Try not to log out during the battle.
* **Fake_Players.patch** - Populates the "who" list with up to 49 fake online players. Message appears saying they do not want to be disturbed when whispered to.
* **Fatigue.patch** - Turn on or off the fatigue timer via worldserver.conf setting.
* **Guard-Elite-Honor.patch** - Gain honor from killing elite guards
* **GuildHouses.patch** - NPC that offers guild leaders a guild house. Once a leader purchases the house, and member of that guild can teleport using this NPC to the guild. Non guild members will not be able to teleport.
* **GuildLevelSystem.patch** - This sets up a cool system where each guild has XP. Players gain XP and that XP is also applied to the guild.
* **Individual-XP-Rate.patch** - Allows setting of different XP rates. I have not tested, so not sure how to set them.
* **KillStreak.patch** - Rewards for pvp based on number of successful wins in a row... I think.
* **Passive_Anticheat.patch** - Best anti cheat out there. checks for speed hacks, flying, etc.
* **NoN-Passive_Anticheat.patch** - Another anti cheat that checks for speed hacks, flying, etc. This one is much pickier than the passive.
* **Played_time.patch** - Rewards for playing the game, based on how long the player is in realm.
* **Player_Events.patch** - Rewards based on specific events. Example: Level rewards. First honorable kill rewards. Check readme file for details.
* **Playerbot-NPCBots.patch** - Old NPCBots patch plus a playerbot patch that allows you to "log in" another character on your account, controlled by the server. Buggy at best, but fun to play with.
* **Pvp_ranks.patch** - Ranking system for pvp.
* **Reforging.patch** - Blizzlike reforging Change 40% of your item stats to something else Sends item packets so you can see the changes on item tooltips Simple and easy to use interface Made for 3.3.5a.
* **StartGuild.patch** - Forces new characters into a guild when they are created.
* **Summon_NPC.patch** - This is an item, that when right-clicked, will spawn an npc (default entry number 100000). I use it to summon my TeleNPC2 NPC, so players can teleport anywhere any time. The NPC will automatically vanish after a few minutes.
* **TeleNPC2.patch** - The best of the best teleport scripts. an NPC with well organized coordinates for teleporting. You can add catagories, and locations, and restrict those locations in many way, such as by cost, specific guild, level required, etc.
* **Transmogrification.patch** - Transmogrification allows you to change the display of an item to something else. You can use any item in your bags as source of display, as long as it fits the requirements. Requirements can be tweaked in the server configuration file. Basically any item should work with transmogrification. Custom items as well. No item is hardcoded to the system. Has a feature to store sets of displays. This can be removed before compiling or in the configuration file. Made for 3.3.5a.
* **TriniIRC.patch** - Allows players to join a channel (set in config) and chat to people in an IRC channel. Configs are a bit confusing, but once working, you can admin the realm via IRC (so you can connect to IRC on your smartphone, and kick\ban players, chat, and do other commands). On the flip side, you can join the IRC chat room (on your computer, tablet or phone) and chat with in game players.
* **Vote_Rewards.patch** - Rewards system using vote points.
* **WorldChat.patch** - Chat Channel that can be seen by everyone anywhere.

I have combined a few of the patches into a single patch, to make things easier for me. These patches are just NPC's that offer stuff, like buffs or games. I have put them all in a single patch named All-In-One. This includes the following patches:

* **All-In-One-NPC.patch** - NPC that does a variety of things, from buffing to morphing.
* **Beastmaster.patch** - NPC that offers the sale of hunter pets. My version has pets in DB, and you can turn on/off hunter only, and GM only. You can also decide how much gold or tokens per pet, instead of per pet type (normal or exotic).
* **BountyHunter.patch** - Place a bounty on a player.
* **LevelNPC.patch** - NPC that offers levels for gold or tokens. Config option
* **LotteryNPC.patch** - NPC that creates a lottery.
* **NPCBuff.patch** - NPC that casts buffs on players. Buffs and cost in DB.
* **npc-enchant.patch** - An npc that will enchant items for you. No more searching for a player that can do it. Just give ME your gold :)
* **ProfessionNPC.patch** - NPC that will give you +10 to any profession... for a price. Price can be token or gold, set in config file.

Added some details, but check the website for more information on the patches.
