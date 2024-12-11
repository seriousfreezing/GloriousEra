![Banner](https://i.imgur.com/ajXnqrZ.png)

**Glorious Era** is a modpack that transforms your Vanilla experience from the new versions to the Beta versions of Minecraft. The aim is to allow you to play by adding other mods on top, without having to remove features from the new versions.
### Looking to fork or use assets from my modpack? [Click here!](https://github.com/seriousfreezing/GloriousEra/wiki/Forks)

# 📥 Installation Guide
<details>
<summary>Client-side</summary>

- [CurseForge Launcher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
- [Modrinth Launcher](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
- [MultiMC](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/141)
- [GDLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)
- [ATLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/361/)
</details>

> [!WARNING]
> Back up your server before you do anything.

<details>
<summary>Server-side</summary>

  - [Docker Compose](https://docker-minecraft-server.readthedocs.io/en/latest/)
  - [mcman](https://github.com/ParadigmMC/mcman)
- <details>
  <summary>Packwiz</summary>

  1. Download the [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap/releases);
  2. Then move it to the root folder of your server; 
  - It's the same folder as the ``fabric-server-1.xx.x-0.1x.x.jar`` file.
  3. Go to ``pre-launch command`` and add this command: 
  ```
  java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/GloriousEra/refs/heads/main/versions/supported/1.21.1/index.toml
  ```
    - [You can switch to the version of Minecraft you want;](https://github.com/seriousfreezing/SolarApocalypse/tree/main/versions/supported)
    - If you can't find it, maybe your server provider doesn't support it.

    **If you have any problems or questions, go to the [Packwiz wiki](https://packwiz.infra.link/tutorials/creating/getting-started/) or contact them on their [discord server.](https://discord.gg/DcSkRF4)**
  </details>
</details>

# 🙌 Credits
- The modpack is based on **[Adrenaline](https://modrinth.com/modpack/adrenaline) and [Simply Optimized](https://modrinth.com/modpack/sop)**;
- The descriptions and the wiki are inspired by the projects: **[Adrenaline](https://modrinth.com/modpack/adrenaline), [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) and [Sodium](https://modrinth.com/mod/sodium)**;
- Some features are from other data packs/resource pack:
  - [Classic Villages](https://www.planetminecraft.com/data-pack/classic-villages/) by [MineOym](https://www.planetminecraft.com/member/mineoym/)
  - [Nostalgic Fishing](https://modrinth.com/datapack/nostalgic-fishing) by [kxffie](https://modrinth.com/user/kxffie)
  - [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs/) by [The Vanilla Tweaks team](https://vanillatweaks.net/about/)

# 📜 License
This modpack is licensed under the GNU General Public License v3.