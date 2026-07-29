![Features](https://cdn.phototourl.com/member/2026-07-24-d9eff9f2-ca14-46c6-83da-b5735c4be67a.png)

![Trennlinie](https://cdn.phototourl.com/member/2026-07-24-de9637b8-7809-40ae-8cb6-47790600d1bf.png)

![About](https://cdn.phototourl.com/free/2026-07-23-5b6f0697-33d5-4002-800e-a6e64c433092.png)

**Bring back the classic falling block duplication mechanics to modern Minecraft versions!**

Gravity Duplication Return is a lightweight, server-side Fabric mod that restores the legendary End Portal duplication bug. This mechanic, once a staple of technical Minecraft, allowed players to duplicate falling blocks like Sand, Gravel, and Concrete Powder. This mod brings it back exactly as you remember it, while adding modern controls for server administrators.

![Trennlinie](https://cdn.phototourl.com/member/2026-07-24-de9637b8-7809-40ae-8cb6-47790600d1bf.png)

![Features](https://cdn.phototourl.com/free/2026-07-23-94c1e1c4-28bd-428c-8eb0-8ca7edbe69cd.png)

Portal Duplication

Reverts the "fix" for entities passing through portals. When a falling block entity (like sand or a dragon egg) enters an End Portal, it is no longer removed from the source world during the dimension change. This results in the entity being successfully teleported while also remaining in the original world, enabling classic "duper" machines to function again.

Administrative Control

We understand that server owners might want to regulate duplication. We've added two specific GameRules to give you full control:

*   `/gamerule enable_portal_duplication <true|false>`
    *   **Default:** `true`
    *   **Effect:** Globally toggles the duplication mechanic for all allowed entities.
*   `/gamerule enable_dragon_egg_duplication <true|false>`
    *   **Default:** `true`
    *   **Effect:** Specifically toggles duplication for Dragon Eggs. Useful for servers that want to allow sand duping but keep the Dragon Egg unique.

Detailed Logging

Stay informed about what's happening on your server. Every time an entity is duplicated, a log entry is created in the server console: `[GravityDupe] Sand duplicated at End Portal at [x=100, y=64, z=200]`

Mod Compatibility & Customization

Designed with compatibility in mind, this mod uses Minecraft's Tag system.

*   **Custom Entities:** By default, it supports `minecraft:falling_block`.
*   **Expandable:** You can allow _any_ entity (even items or entities from other mods) to be duplicated by adding them to the entity type tag: `gravity-duplication-return:duplicatable_entities` via a Data Pack.

Optimized Performance

The mod uses a "Fast-Path" check for standard falling blocks to ensure zero impact on server tick rates, even with high-speed duplication machines.

![Trennlinie](https://cdn.phototourl.com/member/2026-07-24-de9637b8-7809-40ae-8cb6-47790600d1bf.png)

![Requirements](https://cdn.phototourl.com/member/2026-07-24-6661cf6e-4769-443e-8510-23c06a177ce4.png)

*   **Platform:** Fabric
*   **Minecraft Versions:** 26.1, 26.1.1, 26.1.2, 26.2
*   **Side:** **Server-Side Only**. Clients do not need to install this mod to benefit from the restored mechanics.

![Trennlinie](https://cdn.phototourl.com/member/2026-07-24-de9637b8-7809-40ae-8cb6-47790600d1bf.png)

![Installation](https://cdn.phototourl.com/member/2026-07-24-0dc2ca7b-8aea-4bb6-8ce8-222ffa464c8d.png)

1.  Ensure you have the **Fabric Loader** installed on your server or client.
2.  Download the `Gravity Duplication Return` JAR file.
3.  Place the file into your server's or singleplayer instance's `mods` folder.
4.  Restart your server / game and enjoy!

![Trennlinie](https://cdn.phototourl.com/member/2026-07-24-de9637b8-7809-40ae-8cb6-47790600d1bf.png)

![Lizenc](https://cdn.phototourl.com/free/2026-07-23-de1b7d28-0140-458e-ba20-508dc5ea0a1e.png)

This project is licensed under the **CC-BY-4.0 license**. If you want to read the full legal details, click the button below:

<div><a href="https://raw.githubusercontent.com/leopoldoronaldi/Gravity-Duplication-Return/refs/heads/main/LICENSE" style="text-decoration:none" rel="nofollow"><img src="https://s1.directupload.eu/images/260723/bwrocayj.png" width="250px" style="display:inline-block;border:none"></a></div>
