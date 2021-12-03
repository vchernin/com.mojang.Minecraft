# Minecraft (Flatpak)

#### Resource Packs, Mods etc.

You can install these to `~/.var/app/com.mojang.Minecraft/.minecraft`.

## Fabric support

*[Fabric](https://fabricmc.net/) is a lightweight, experimental modding toolchain for Minecraft.* 

A Flatpak Fabric extension is provided to ease installation, however mod installation itself is not done automatically.

Ensure to use versions of mods, Minecraft itself, and the Fabric API that are compatible, similarly as non-Flatpak Minecraft installs.

1. `flatpak install com.mojang.Minecraft.Utility.fabric --user`

2. Close and start Minecraft.

3. When prompted, chose a Minecraft version to create a Fabric profile for. Use the default install location, and click "Install". After install, close the Fabric Installer.

4. Save Fabric mods to `~/.var/app/com.mojang.Minecraft/.minecraft/mods` (you might need to create a `mods` folder). Note many mods require the [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) to be present alongside them, which can be installed like another mod.

Note: to see the install prompt again remove `~/.var/app/com.mojang.Minecraft/.minecraft/fabric_previously_installed`