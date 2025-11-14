# ZombiesCantClimb

What Does This Mod Do?
This mod stops zombies from climbing ladders in 7 Days to Die.
You know how sometimes you set up a perfect bunker, only for a zombie to casually stroll up the ladder like it’s rush hour? Yeah, this kills that nonsense.

By default, no zombies can climb ladders. But if you want certain zombies (like the spider zombie) to still climb, you can add them to a simple list in the config file. Easy as that. Just make sure you follow the formatting example I added in the XML.


Does It Work on Client or Server? (Please Read Below on these 2 points.)

✅ Servers: Works perfectly and EAC can be ON or OFF. Players don’t need to download anything.

⚠️ Local Single-Player / Peer-to-Peer Hosting: Requires EAC OFF in order to load correctly. Others shouldnt need to install it still this way though.



How to Install
Grab the mod folder (called TheMeanOnes_ZombiesDontClimb)
Drop it into your Mods folder:
For single-player: %APPDATA%\7DaysToDie\Mods
For a dedicated server: drop it in the game/server’s Mods directory (Others don’t need to install!)
Start the game and check the console — you’ll see a green log like:
[TheMeanOnes_ZombiesDontClimb] Config loaded: Climbing Whitelist Mode, Allowed Zeds: (your list here)



A Quick Few Notes
Servers: Works with EAC ON or OFF.
Local Hosting: Requires EAC OFF!!
The mod auto-generates a config file on launch. You can tweak it to allow specific zombies to climb by editing:
NoZombieClimbingConfig.xml
Set WhitelistClimbing to true and list any zombies you want to let climb. If you want none of them climbing, just leave the list empty. AKA as is.
This mod only blocks ladder climbing — zombies can still bash doors, walls, and windows like usual. They can also stack on top of one and other, which means that it may appear they are climbing. When indeed they are not, they are smart as shit.
If you’re using this in an overhaul, just credit it and link back here so players get the latest version downloaded. Make it a dependency instead of bundling it directly.
Works in Version 2.2+ 
      8. REQUIRES TMO CORE TO FUNCTION (WHICH ALSO CAN BE SERVERSIDE!)
