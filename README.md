# Jaceks-Stream-Pack

This is the official repository and issue-tracker for Jaceks Stream Pack, for Minecraft 1.12.2

### Table of Contents
* [Setup](#setup)
  * [Windows / Mac](#windows-/-mac)
  * [Linux](#linux)
  * [Server Automation](#server-automation)
* [Links](#links)

# Setup 
### For Contributors, Testers and Server Admins
Follow these steps to setup your workspace/server:

## Windows / Mac
1) Download the [Twitch App](https://www.twitch.tv/downloads) if you haven't already.
2) Fork and clone the Enigmatica 4 repository to the Instances folder of the Twitch App, the default path is `C:\Users\<user>\Twitch\Minecraft\Instances`
3) Double click the script `setup.bat` to setup InstanceSync. It is found in the `development` folder.
4) Pull.
5) Open the Twitch App, go to Mods > Minecraft, and you should see Enigmatica 4. If you already had Twitch App open, restart it.

You're done!

## Linux
#### Setup MultiMC Instance (Currently not possible 03-10-2019)
1) Download [MultiMC](https://multimc.org/#Download) if you haven't already.
2) Open MultiMC.
3) Click Add Instance, choose Minecraft 1.14.4, click Ok.
4) Click Edit Instance (right hand side)
5) Click Install Forge, pick the latest version.

#### Repository Setup
6) Fork and clone the Enigmatica 4 repository
7) Open the folder of the MultiMC Instance you made (step 1-5), and go into the .minecraft folder - Open a Terminal and use the following commands:
```
git init                                           # Initialize git in folder
git remote add origin URLToYourFork                # Set remote origin to your Jacek Stream Pack fork
git remote -v                                      # Verify remote
git fetch
git pull
```
8) Now double click the script `setup.sh` to setup InstanceSync. It is found in the `development` folder.
9) One more `git pull`

You're done!

### Alternatives
It is possible to setup a development instance for Enigmatica 4 in other ways, for example running it through the .Minecraft folder or using GDLauncher

## Links

* [CurseForge](https://www.curseforge.com/minecraft/modpacks/jaceks-pack)

* [Discord](https://discord.gg/QHJeSNf)
