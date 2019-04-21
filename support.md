<!-- TITLE: Support -->
<!-- SUBTITLE: Before you go yell in the #support channel, check these common issues! -->

### Table of Contents
1. [Installer Issues](#1-installer-problems)
2. In-Game Issues
3. Common mod questions

# 1. Installer problems
### 1.1 Is the mod manager a virus?
BitDefender and other AV software seem to have added the Mod Manager into their database of suspicious programs. See this [GitHub issue](https://github.com/beat-saber-modding-group/BeatSaberModInstaller/issues/20) for more info, and use your best judgement.

### 1.2 I can't download the mod manager, or it closes as soon as I start it up
Make sure you're using the one from the [BSMG GitHub](https://github.com/beat-saber-modding-group/BeatSaberModInstaller/releases/latest). There are 3 releases being distributed due to concerns about how different AV software blocks the application:
* BeatSaberModManager-Unbundled.zip
* BeatSaberModManager.exe
* BeatSaberModManagerClassic.exe
Take your pick, they all work the same way. Alternatively, consider using [BeatDrop](https://bsaber.com/beatdrop/) instead.

### 1.3 Permission errors
Run the mod manager in admin mode if your PC's security settings have insufficient permissions to patch files by default.

# 2. Game has issues after installing mods
### 2.1 GetThreadContext Failed Error
If a window pops up saying `GetThreadContext Failed` and/or you hear a Windows error sound, you may have software on your PC that's breaking Beat Saber mods. Many third-party anti-cheat software like ESEA and FaceIt Anti-Cheat disrupt BSIPA from applying mods to Beat Saber, even when not running. Some Anti-Virus software exhibit similar behavior. We're working on a more permanent solution, but at the moment you need to do the following steps:
1. Uninstall the anti-cheat software
2. Reboot your PC
3. Verify files in Steam, or reinstall the game on Oculus Home

### 2.2