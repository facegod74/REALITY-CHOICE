# REALITY-CHOICE
RED PILL BLUE PILL EFFECT

INSTALL:
1. Drop the folder into your FiveM resources folder.
2. Add this to server.cfg:
   ensure reality_choice_facegod74_v3
3. In shared/config.lua set:
   Config.Framework = 'standalone', 'qb', or 'esx'
   Config.Inventory = 'ox', 'qb', or 'none'
4. For ox_inventory, copy install/ox_inventory_items.lua into ox_inventory/data/items.lua.
5. Copy the images from img/ into ox_inventory/web/images/.
6. Restart ox_inventory and this resource.

TEST COMMANDS:
/realitytest       Gives test pills. Disable Config.Commands.GiveTestPills before public launch.
/realitycraftgold  Attempts the 1% Gold Pill craft.
/realityclear      Clears active client effects.

CONSUMABLE UPDATE:
Blue Pill, Red Pill, and Gold Pill are now true one-time consumables.
When a player uses a pill, the server checks inventory, removes 1 pill, locks the player from using more while active/on cooldown, then starts the effect.

ITEMS:
reality_bluepill
reality_redpill
reality_goldpill

BRANDING:
Reality Choice
Made by facegod74
