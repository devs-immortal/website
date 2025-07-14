---
title: "Gamerules"
summary: "Details on configuring your Paradise Lost experience through new Gamerules"
author: 24Chrome
date: 2025-06-14T21:37:11+00:00
lastmod: 2025-07-14T16:02:54+00:00
thumbnail: /wiki/paradise_lost/thumbnails/guides/gamerules.webp
keywords: [gamerules, portal, commands]
---

<img src="/wiki/paradise_lost/guides/gamerules.webp">
Sadness.

## Tweaking the Paradise Lost Experience
Paradise Lost adds a few new Gamerules that allow for tweaking the mod slightly based on how you might want to play. Each Gamerule is detailed below. 

### paradiseVoidKills
This Gamerule will toggle if falling into the Paradise void kills players, or drops them into the Overworld. 

* When **true**, players will take normal void damage when falling into the void, and will respawn at their spawn point. This may be useful if trying to play a world in Paradise only.
* When **false**, players will teleport to the top of the Overworld when falling into the void.

Defaults to **false**.

### paradisePortalEnabled
This Gamerule will toggle if Paradise Portals can be opened by players or travel through them. 

* When **true**, Paradise Portals can be created normally and will teleport entities to Paradise.
* When **false**, Paradise Portals will not open when water is placed in the frame. If a Paradise Portal is created with commands or was created before the Gamerule was set to false, it will not be able to teleport entities to Paradise.

Defaults to **true**.
