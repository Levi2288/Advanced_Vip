# Advanced Vip/Donator Menu

[Alliedmods post]: https://forums.alliedmods.net/showthread.php?p=2750375#post2750375
[Raining Money]: https://forums.alliedmods.net/showthread.php?p=2558324
[Fake Case]: https://github.com/Bufika2288/Fake-Case
[Fake Vac Kick]: https://forums.alliedmods.net/showthread.php?p=2317588
[Body Color Example]: https://imgur.com/a/AHI0ezb
[Body Size Example]: https://imgur.com/a/C7Un2W8

It's started as a Basic Donator/Vip menu but now its kinda big so i renamed the plugin to "advanced".
i recommend this pluginfor fun server because of the lot of fun function.

I'm not a pro coder so the plugin probably not optimized that well

[Alliedmods post]

## Installing modules:

Just drop everything in your addons folder and change map / Restart the server.




### What is great about this plugin:

- 100% Translate support
- Chat processor support
- Fully customizable
- Everything saved in cookies 
- U can register your own commands

# Cmds

By default:

- sm_dm 
- sm_donator 
- sm_donatormenu

but u can register your owns with ```sm_donatormenu_commands``` cvar

# Functions

- Vipspawn (Default cmd: sm_vipspawn)
- Enemy weapon shop for each team (Default cmd: sm_weaponmarket)
- Spawn With items (HealthShot, TagGrenade, Taser, DefuseKit)
- Perks (Bhop, +hp & armor on spawn, +Cash each round)
- Raining Money (U need this plugin for it [Raining Money])
- Play Fake Game Sounds (Bomb Has Been Defused, Terrorist Win, etc)
- Open Fake Case (U need this plugin for it [Fake Case])
- Fake Vac Kick (U need this plugin for it [Fake Vac Kick])
- Body Color ([Body Color Example])
- Body Size ([Body Size Example])
- Body Transparency 
- Spawn Things (Ball, SnowBall Pile, Chicken)

# Changelog
1.0 Release
1.1 fixed join & disconnect messages
1.2 Added enemy weapon market

# Cvars 

There is a lot so im just gonna yeet everything here.

```

// How much + armor donators/vip get by default (0 to disable)
// -
// Default: "25"
sm_armor_onspawn "25"

// Enable the body modifications functions
// -
// Default: "1"
sm_body_modifications_enable "1"

// Enable the body size function
// -
// Default: "1"
sm_bodycolor_enable "1"

// Enable the body size function
// -
// Default: "1"
sm_bodysize_enable "1"

// You can set here custom commands to open the main menu
// -
// Default: "vip, advancedvip, vipmenu"
sm_donatormenu_commands "vip, advancedvip, vipmenu"

// Enable the main plugin
// -
// Default: "1"
sm_donatormenu_enable "1"

// admin flag for donators menu (empty for all players)
// -
// Default: "o"
sm_donatormenu_flag "o"

// Enable the bhop perk
// -
// Default: "1"
sm_enable_hop "1"

// Enable the fakecase function
// -
// Default: "1"
sm_fakecase_enable "1"

// Enable the Fun functions
// -
// Default: "1"
sm_fun_functions_enable "1"

// Cooldonw to use fake vac kick in sec
// -
// Default: "120.0"
sm_fvk_cooldown "120.0"

// Enable the fake VAC kick function
// -
// Default: "1"
sm_fvk_enable "1"

// How much + hp donators/vip get by default (0 to disable)
// -
// Default: "25"
sm_health_onspawn "25"

// Enable spawn items
// -
// Default: "1"
sm_items_enable "1"

// Enable join and discnonnect message for vips
// -
// Default: "1"
sm_join_disconnect_msg "1"

// Cooldonw to use the sounds in sec
// -
// Default: "120.0"
sm_playsound_cooldown "120.0"

// Enable the raining money function
// -
// Default: "1"
sm_rainmoney_enable "1"

// Restrict the module cmds to flag b (Recomended if you using fake vac kick or raining money module)
// -
// Default: "1"
sm_restrick_module_cmds "1"

// + money on round start (0 to disable)
// -
// Default: "700"
sm_round_start_money "700"

// You can set here custom commands to use spawn
// -
// Default: "vipspawn, respawn, spawnme"
sm_spawn_commands "vipspawn, respawn, spawnme"

// Enable the "VipSpawn" function
// -
// Default: "1"
sm_spawn_enable "1"

// Enable the body transparency function
// -
// Default: "1"
sm_transparency_enable "1"

// You can set here custom commands to use the weapon market 
// -
// Default: "weaponshop, blackmarket, weaponmarket"
sm_weaponmenu_commands "weaponshop, blackmarket, weaponmarket"

// Enable the "Enemy Weapon Shop" function
// -
// Default: "1"
sm_weaponmenu_enable "1"

// How much time weaponmenu is active and can be used? (in sec)
// -
// Default: "45"
sm_weaponmenu_time "45"


```


