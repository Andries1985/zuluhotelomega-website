---
title: NPC & Boat Commands
description: "Various commands you can use on NPC's or boats."
date: 2024-11-20T11:47:31+01:00
sections:
  - Misc
tags:
  - NPC's
  - Boats
images:
  - /images/infovault/classes/bard/bard8.jpeg?width=1792&height=1024
---

## Merchants
Dragging a stable pet deed onto an animal trainer will give the pet back to you.

| Command                     | Information                                                                                                                             |
|-----------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Sell bag                    | Will sell all the content of a targeted bag.                                                                                            |
| Sell all                    | Will sell all the items on you that is of the same kind of the targeted item.                                                           |
| Sell                        | Will bring up a sell gump that allows you to select what items you want to sell.                                                        |
| Buy                         | Will bring up a buy menu that allows you to buy the selected items.                                                                     |
| vendor train/merchant train | Will bring up a skill training gump that allows you to train the selected skills to 33.3. Different vendors can train different skills. |
| identify                    | This command only works on mages or scribes and allows you to identify items or full bags with items.                                   |
| stable                      | This command only works on animal trainers and will stable the selected pet.                                                            |

## Bankers
{{< bs/alert danger >}}
{{< markdownify >}}
First time opening your bank for that character? Close the bank box and open it again to make sure your items won’t bug away, no items can be replaced by staff if this happens.
{{< /markdownify >}}
{{< /bs/alert >}}

| Command | Information                                                                                                                                               |
|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| bank    | Will open your bank box.                                                                                                                                  |
| balance | Shows the amount of gold you have in your bank.                                                                                                           |

## High Priests
If you hand over less gold then asked for you will make the priest upset at you and you will have to donate gold to him before you can use his services again.

| Command                              | Information                                                           |
|--------------------------------------|-----------------------------------------------------------------------|
| Greeting/Hail/hi/Hello/Help/Farewell | Chat with your high priest.                                           |
| Remove curse/Uncurse                 | Will uncurse the selected cursed item.                                |
| Detect curse                         | Will detect if the item is cursed before you try it on.               |
| Purify                               | Will purify the cursed item, turning it back to the uncursed version. |
| Heal                                 | Will cast the spell heal on you.                                      |
| Dispel                               | Will cast the spell dispel on you.                                    |
| Cure                                 | Will cast the spell cure on you.                                      |
| Protection                           | Will cast the spell protection on you.                                |
| Bless                                | Will cast the spell bless on you.                                     |

## Tamed creatures
To command your creatures you will have to type its name or “all ” before the command.
Tamed creatures will be released after a certain time if not properly fed, check the [Animal Lore]({{< relref "animallore" >}}) skill for more information.

| Command          | Information                                          |
|------------------|------------------------------------------------------|
| kill/attack      | Will make the animal attack the target.              |
| stop             | Will make the animal stop following and guarding.    |
| come             | Will make the animal come to you then stop.          |
| follow/follow me | Will make the animal follow the target/you.          |
| transfer         | Will transfer the animal to the selected player.     |
| guard/guard me   | Will make the animal guard the target/you.           |
| fetch            | Will make the animal fetch the targeted item.        |
| drop             | Will make the animal drop the items in its backpack. |
| speak            | Will make the animal speak.                          |
| stay             | Will make the animal stay in its place.              |

## Boats
Double-clicking your tillerman will allow you to name your boat.
Boats on Zuluhotel Omega are unlocked and can be boarded/commanded by anyone, however not drydocked by anyone. Use the ".whereboat" command to find your boat if it's lost.
If you die on a boat it will resurrect you after a certain time has passed, be patient as this can take some time (minutes).

| Command                         | Information                                                       |
|---------------------------------|-------------------------------------------------------------------|
| unfurl/unfurl sail              | Will make your boat move forward.                                 |
| drift/raise anchor              | Will make your boat drift.                                        |
| forward                         | Will make your boat move forward                                  |
| left                            | Will make your boat move towards its port side.                   |
| right                           | Will make your boat move starboard.                               |
| back                            | Will make your boat move backwards.                               |
| forward left                    | Will make your boat move towards its port bow side.               |
| forward right                   | Will make your boat move towards its starboard bow side.          |
| back left                       | Will make your boat move towards its port quarter side.           |
| back right                      | Will make your boat move towards its starboard quarter side.      |
| stop/furl sail/furl/drop anchor | Will stop your boats movement.                                    |
| turn right/starboard            | Will turn your boat starboard.                                    |
| turn left/port                  | Will turn your boat port way.                                     |
| come about                      | Will turn your boat 180 degrees.                                  |
| full                            | Will make your boat move quicker.                                 |
| slow                            | Will make your boat move slower.                                  |
| one forward/left/right/back     | Will make your boat move one step towards the direction you type. |
| drydock                         | Will drydock your boat.                                           |

## Player vendors
Player vendors require payments, if your vendor isn’t carrying any gold he will leave you and all items you have on him. You can drag gold onto him to have him carry it for you.
To sell items on your vendor just drag the item you want to sell onto him.

| Command            | Information                                                                                                                                                             |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| buy                | Will bring up a buy menu that shows what the vendor is selling.                                                                                                         |
| purchase           | Add things you want the merchant to buy for you so other players can sell items to your merchant. *Use with caution so your vendor don't run out of gold and leave you* |
| release            | Will fire your vendor.                                                                                                                                                  |
| sell               | Will tell you if the player vendor is buying any items.                                                                                                                 |
| collect            | Will collect gold from your vendor, max 60k gold each time you type it.                                                                                                 |
| status             | Will tell you how much gold your vendor is carrying for you.                                                                                                            |
| wear               | Allows you to dress your vendor.                                                                                                                                        |
| strip/undress      | Undresses your vendor.                                                                                                                                                  |
| fullname follow me | Makes your vendor follow you.                                                                                                                                           |
| fullname stop      | Makes your vendor stop following you.                                                                                                                                   |
| hire               | Hires a fired vendor.                                                                                                                                                   |
| log                | Will show your vendors message log.                                                                                                                                     |
| help               | Will show you a list of all commands.                                                                                                                                   |

## Warrior for hire
To access your warrior's backpack you double-click the warrior.
To command the warrior you will have to type the warrior's name or “all ” before the commands on the list.
If your warrior for hire dies you will receive a heart that you can hand to a high priest to resurrect your warrior for hire.

| Command          | Information                                                                                 |
|------------------|---------------------------------------------------------------------------------------------|
| kill/attack      | Attacks the target you select.                                                              |
| stop             | Stops the warrior from following and guarding.                                              |
| heal/heal me     | Heal will try to heal the selected target. Heal me will try to heal you.                    |
| come             | The warrior will come to you then stop.                                                     |
| follow/follow me | Follow will make the warrior follow the target. Follow me will make the warrior follow you. |
| transfer/brb     | Chat with your warrior.                                                                     |
| guard/guard me   | Will guard the target or yourself.                                                          |
| fetch/get        | Will go get the targeted item.                                                              |
| drop             | Will drop everything in the warriors backpack to the ground.                                |
| dismount         | Will dismount the warrior                                                                   |
| ride/mount       | Will make the warrior mount the selected mount.                                             |
| stfu/squelch     | Will squelch your warrior.                                                                  |
| speak/unsquelch  | Will unsquelch your warrior.                                                                |
| rearm            | Will make your warrior change weapons.                                                      |
| release          | Will fire your warrior.                                                                     |
| wear             | Will dress your warrior with the targeted item.                                             |
| hide             | Will hide your warrior.                                                                     |
| showpack         | Will open your warriors backpack.                                                           |
| warcry           | Will make your warrior warcry.                                                              |
| go crazy         | Will make your warrior go crazy.                                                            |
| undress          | Will undress you warrior.                                                                   |

## Totem
To command your totem you will have to type its name or “all ” before the command.
If you loose your totem you can use either .wheretotem or .recalltotem to get your totem back.

| Command   | Information                                                    |
|-----------|----------------------------------------------------------------|
| stop      | Stops the totem from following.                                |
| come      | Makes the totem come to you then stop.                         |
| follow    | Makes the totem follow you.                                    |
| fetch/get | Will make the totem fetch the selected item.                   |
| drop      | Will make the totem drop whatever it have in its backpack.     |
| speak     | Chats with your totem.                                         |
| cureself  | Totem will try to cure itself.                                 |
| cure      | Totem will try to cure you.                                    |
| healself  | Totem will try to heal itself.                                 |
| heal      | Totem will try to heal you.                                    |
| light     | Totem will try to cast night sight on you.                     |
| protect   | Totem will try to cast protection on you.                      |
| bless     | Totem will try to cast bless on you.                           |
| loot      | Will make the totem loot items/corpses around him.             |
| give      | Will make the totem gives items in its backpack to the target. |
| vamp      | Will drain mana from the master and give to the totem.         |
| hide      | Will hide the totem.                                           |
