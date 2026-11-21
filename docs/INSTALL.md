# Installing Fuse

Fuse runs on **Minecraft 1.21.11** with **Fabric**.

## 1. Get your jar

1. Open https://dashboard.fuseclient.com
2. Click **Connect Discord** (Fuse only gets your Discord name and profile picture).
3. Click **Download**. This is your personal Fuse jar. Don't share it.

## 2. Install Fabric

- **Vanilla launcher:** run the installer from https://fabricmc.net/use/installer/, pick **1.21.11**, click Install.
- **Modrinth, Prism, Dawn:** create a new instance for **1.21.11** with the **Fabric** loader.

## 3. Add the mods

Put these two files in the instance's `mods` folder:

- **Fabric API** for 1.21.11 (https://modrinth.com/mod/fabric-api)
- **Your Fuse jar** from step 1

Vanilla launcher `mods` folder on Windows: `%appdata%\.minecraft\mods`

## 4. Play

Start the game with the Fabric profile and press **Right Shift** to open Fuse.

## It doesn't start?

- Check the game version is exactly **1.21.11** and the profile is **Fabric**.
- Check **Fabric API** is in the `mods` folder.
- Keep only **one** Fuse jar in the folder.
- Only the jar from the dashboard works. Jars from anywhere else won't run.
- New PC and it says the licence is locked? See [FAQ](FAQ.md#i-got-a-new-pc).
