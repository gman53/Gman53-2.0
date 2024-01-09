
# Eaglercraft server

### ty [Byte#9476] for fixing the forwarding issue!!


### smashed together by [ayunami2000](https://github.com/ayunami2000)
### refurbished by [EstaticYT](https://www.youtube.com/channel/UCbdWfxvmD7s2sML9Y3YX4VQ)

**THIS REPO USES [PluginInstaller](https://github.com/darverdevs/PluginInstaller)**

**LATEST UPDATE: PUT ON GITHUB**

## Helpful video tutorial by a generous user
motd changing is DIFFERENT than what these tutorials say!! -- check the `java/bungee_command/config.yml` for how to change (motd1 is first line, motd2 (you can add this) is the 2nd one)

### TUTORIAL COMING SOON

## Usage:


##

### NOTE: to control, you MUST open the website view in a new tab instead of playing in the editor.

## To change the server icon:
Replace the `server-icon.png` file under `java/bungee_command` with your desired server icon.

## To run server commands:
In the Console, run commands without the /

## To save progress:
**Notice: This is now done automatically, every 30 seconds, using a plugin!** In the server console or in-game as an opped player, run `/save-all` to save the world.

## Too slow?
-This is because you are using a free service to host a Minecraft server. Of course it is slow and the only way to fix this is to self-host at home.-

## Getting admin/OP or enabling command blocks
To give yourself OP (admin), go to the server console and run `op username` and press enter (replacing "username" with your username in-game).

To enable command blocks, go to `java/bukkit_command/server.properties` and add a new line at the end: `enable-command-block=true`. Then, restart the server.

## [Item ID List](http://mineteamleblog.blogspot.com/p/minecraft-id-list-151.html)

## Plugins
Eaglercraft is Minecraft 1.5.2, so plugins you will use will have to be supported by Bukkit 1.5.2 (not Spigot). You can add plugin JAR files into the `java/bukkit_command/plugins` folder.

**Official Plugin Collection**

*COMING SOON*

**Some plugins I suggest you use:**

### [LoginSecurity](https://dev.bukkit.org/projects/loginsecurity/files/711129)
Adds /login and /register to your server. **Make sure you turn OFF sessions in the config (run server once after adding plugin, run the server once after adding loginsecurity, go to "plugins/LoginSecurity/config.yml", and change `sessions: use:` from true to false), or else players may be able to "resume session" on any account!**
### [Essentials](https://dev.bukkit.org/projects/essentials/files/711777) & [Essentials Extra](https://dev.bukkit.org/projects/essentials/files/711776)
"Essential" commands and features for any Minecraft server. Widely popular, even today!
### [WorldEdit](https://dev.bukkit.org/projects/worldedit/files/698941)
Super popular world editing plugin!
### [NoSpawnChunks](https://dev.bukkit.org/projects/nospawnchunks/files/586974)
Prevents loading spawn chunks on your server. Helps to optimize it greatly!

## Not working?
1. Make sure you haven't broken any essential files.
2. Join the [official Eaglercraft discord server](https://discord.gg/6yTNkypXWh) and look for any answers there.
3. If all else fails, contact me directly **through Discord** at `crispywombat122`
5. If you do not have access to Discord, THEN you can email me.
