---
sidebar_position: 7
---

# War Guide

# MvndiCraft EventWar Guide

## Introduction And Mechanics

Mvndicraft uses the EventWar plugin for war and diplomatics in Towny.
Eventwar wars focus on capturing towns by taking down the HP of border chunks.
There are currently only 3 war types available on Mvndicraft:

- Nation VS Nation Wars (All towns in Nation1 fight against all the towns in Nation2, no other nation can get involved)
- Town VS Town Wars (Two towns go to war with eachother, no other town can get involved)
- Civil Wars (A town mayor decides that they want ownership of the nation they are currently apart of)
- Independence Wars (An occupied town fights for its freedom against a Nation)

## Commands

- `/eventwar guide` - opens a book ingame telling you how the war system is configured
- `/t redeem token <WARTYPE>` - redeems a war book which can be used to declare war (costs war tokens)
- `/declare war <WARTYPE>` - declare a war while holding a war book in your hand
- `/towny map hud` - display a map scoreboard of nearby towns and their claims' area (CAPTURED CHUNKS AREN'T SHOWN)

## Starting A War

In order to start a war, you need some war tokens. War tokens are handed out to each non-neutral town every 24h.
Once you have enough war tokens, you can use the redeem command to get the war book which you will need for your upcoming war.
War book prices per war type:

- CIVIL WAR: 7
- TOWN WAR: 3
- NATION WAR: 10
- INDEPENDENCE: 6

## War Schedules

Wars have a 1 day warmup time, meaning that if you declare a war today, it will officially start tommorrow at the same time. <br/>
This way, you have time to prepare for the War if you are offline, and to call for your allies. <br/>
Wars can be declared EVERYDAY between `11:00 EST` and `17:00 EST`. <br/>
There are no online party/member requirements for a war to be declared. <br/>

## Picking A Side (CIVIL WAR + INDEPENDENCE WAR)

A message will appear prompting you to choose a side in the civil war. <br/>
You have one hour before the war (23h after the declaration) to pick a side.

## War Durations

Each war type lasts a different amount of time.

- CIVIL WAR: 2h
- TOWN WAR: 1.5h
- NATION WAR: 2.5h
- INDEPENDENCE: 1.5h

## Capturing Chunks

If you are apart of the war, and not in neutral town, you are able to capture chunks.
You must be on Y level 61 or above to capture chunks.
Simply stand on the border chunks of enemy towns, until you get a chat message saying the HP of the chunk has been set to 0 or the chunk has been captured, then you can advance further into the town.
The whole point of this is not to get points by capturing towns, but to capture the homeblock of the enemy town and knock the town out of the war (Nation / Civil War) by doing so, or ending the war (Town War).
Each chunk has an HP of 55, and homeblocks have and HP of 150. Damage is dealt every 5 seconds and the amount is the number of enemies standing on the town's chunk.

## Points

While doing certain activities, you get points for the war. If the war does not end in the maximum given time, the points will define the winner of the war. You will get points for:

- KILLING AN ENEMY: 1p
- CAPTURING A CHUNK: 10p
- CAPTURING A TOWN (NATION/CIVIL WAR): 20p

## Surrendering (OPTIONAL)

To surrender, type `/surrender < WHITE_PEACE | MONEY | TOWNS | MONEY_AND_TOWNS >`.
If you think you can peace talk with your enemy, try using the surrender command. Surrendering is useful if you or your enemy want to end the war faster but get something out of it, such as:

- MONEY: Surrender to your enemy and pay a price to them.
- TOWNS (CIVIL WAR / NATION WAR): Surrender towns to your enemy and end the war faster.
- BOTH: Pay money and hand over towns to your enemy to end the war faster
- WHITE PEACE: No one gets anything, the war just ends.

## Leaving CONQUERED status

When a nation wins a war against you by capturing your town, you will be conquered forever. The only way to have independence is to declare a Independence War against your conquering nation.

## End Of War

After wartime has ended, or all cities / the capital has surrendered (Nation / Civil War), a winner will be decided.
In Independence war, if the declaring town wins they are unconquered and freed from the occupying nation.
The winners are the ones with most points / the ones that haven't surrendered (in case anyone has) / the ones that have captured the capital (Nation War). The winners will get to keep the towns they have conquered the homeblocks of during the War (Nation War), will absorb the town (Town War), or will become the new capital of the nation (Civil War).

## Griefing

When a town is conquered/fallen during a war, the winners will have permission to <br/>
open chests and other switches in the town for `15 Minutes`.
