# AA Endgame Practice datapack for 1.21+

## First use

1. Open the "create world" menu
2. Turn "allow commands" on
3. Under the "more" tab, click "datapacks"
4. Drag and drop the pack into the window
5. Move it from available packs to selected packs
6. Create the world, Information will show up in chat

## Further usage

1. Hit the "recreate world" button on a previous world with the pack
2. Go under the "world" tab
3. Remove the seed parameter
4. Create the world

## Features and Quirks

Compatatible with 1.21-1.21.4

Many advancements will not show up in the vanilla menu, this is because they were overriden in order to prevent the toast messages from popping up. This makes an external tracker like AATool or SwiftAA almost necessary (though SpeedrunIGT still works)

You probably want to turn off the auto-switching to AA option in SpeedrunIGT, this will change to Any % when you go through the portal early enough, which you probably will in endgame practice.

You will always be placed near a temple, and your spawn point moved. So your coordinate may be pretty large. You will always be placed in a desert. There will also always be an end portal spawning above your head.

The Inventory is hard to edit, you have to edit the file under `data/endgame/function/inventory.mcfunction` and add your own `item replace` or `give` commands (make sure to remove slashes at the start of additional commands).

Unfortunately due to the hardcoded nature of a datapack it's nearly impossible to make this easily configurable. The function file editing isn't that bad for minor adjustments though. You can use a generator such as this one for [general items](https://www.gamergeeks.net/apps/minecraft/give-command-generator) or this one for [shulker boxes](https://www.gamergeeks.net/apps/minecraft/give-command-generator/chests-shulkers).

This project was made with [PackScript](https://www.github.com/Slackow/PackScript), if you want to do more extensive editing of this project, you should get the source and compile it with PackScript.
