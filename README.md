# Minecraft Fabric Mods
My collection of client-side fabric mods, collected in this repository for easy access.

## Installing
1. Run Minecraft with the version you want to install fabric for at least once. Minecraft installs a new version when that version is launched for the first time
2. Download and run the [fabric loader](https://fabricmc.net/use/installer/)
3. Open the .minecraft folder (see below for more instructions).
5. Open the `mods` folder. Create it if it doesn't exist. Launching the fabric version of minecraft will automatically create the mods folder, but this is not necessary.
6. Open the terminal (see below for more instructions).
7. Paste the following command, replacing <VERSION> with the version of Minecraft you're playing (i.e., `1.19.2`):
```bash
git clone --branch <VERSION> https://github.com/nolanbarry/minecraft-fabric-mods.git .
```
> If the `git` command doesn't exist, install `git` [here](https://git-scm.com/download/win).

> If you receive the following error: "`fatal: Remote branch <VERSION> not found in upstream origin`", this repository doesn't have support the version you entered.
8. Move any mods you don't want into the `disabled` folder

## Opening the .minecraft folder
### Windows
1. Tap the `Windows` key (or open the start menu), type `run`, then hit `Enter` to open the `Run` dialog.
2. Paste `%APPDATA%/.minecraft/` into the `run` dialog, then hit the `Enter` key or click `OK`. This will open the minecraft folder in Explorer
### Mac
1. Tap `⌘+Space` to open Spotlight
2. Type `~/Library/Application Support/minecraft` and hit `Enter`

## Opening the Terminal
### Windows
1. Right click in the Explorer window in empty space (not on a file)
2. Click `Open in Terminal`

### Mac
1. Tap `⌘+Space` to open Spotlight
2. Type and run `Terminal`
3. Paste the following command and hit enter:
```bash
cd ~/Library/Application Support/minecraft/mods
```