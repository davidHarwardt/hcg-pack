
## notes
quests
- automate <item>

shop
- use instead of villagers
    - buy enchantments
    - produce bulk items to earn currency

- challenges in special dimension

## automatable tasks
- cobblestone farm
- tree farm
- [food] farm (wheet, potato, cactus, sugarcane, ...)
- mining
- autocrafting

## objectives
- make lockable door
- build openable and closable door using turtle
- play midi (jingle / never gonna give you up)

## tutorial
- how to play (skipable)
    - [todo]
- computercraft: intro [requires how-to-play]
    - getting started
        - rew: 1 x advanced computer
    - how does the shell work
    - how to write programs (lua)
        - `print`
        - variables (declaration, math, types)
        - string operations
    - how to execute programs
- turtles: intro [requires cc:intro]
    - getting started
        - req: 1 x advanced turtle
    - functions
        - fuel (`refuel`, `getFuelLevel`)
        - [lua] if
        - movement (`forward`, `back`, ...)
        - turning (`turnLeft`, `turnRight`)
        - detect (`detect`, `detectUp`, ...) + return value of [`forward`, ...]
        - [lua] while loops (`while`, `repeat` ... `until`)
        - [lua] numeric for (`for`)
        - block place (`place`, `placeUp`, ...)
        - [lua] methods (`function`...`end`)
        - mining turtle
            - req: 1 x advanced turtle (consumed)
            - rew: 1 x advanced mining turtle
        - block break with mining turtle (`dig`, `digUp`, ...)

        - [optional]
        - wait (`sleep`)
        - get more information about block (`inspect`, `inspectUp`)
        - crafting (`craft`)
        - combat with sword (`attack`)
        - specialized tools (`equip` + rules for tools)
        - the vector type
- farms [requires turtles:intro]
    - a cobblestone farm
        - req: checkbox
        - rew: 1 water + 1 lava bucket + 1 hopper
        - quest: explaination of hopper and cobblegen mechanics
    - generate 64 cobblestone with your farm [requires cobblestone-farm]
        - req: 64 cobblestone (consumed)
    - ...

## mods
- mouse-tweaks
- mod-menu
- roughly-enough-items
- tempad
- linked-storage
- quarz-elevator
- capes
- cc-restitched
    - turtlematic
    - unlimitedperipheralworks
- squat-grow
- extended-drawers
- toms-storage
- inventory-sorting
- chipped
- harvest-with-ease
- ping-wheel
- hole-filler

## ftb mods
- quests
- teams
- ranks
- chunks
- backups-2

## perf
- sodium
- lithium
- phosphor

---

## optional
- kubejs
- content-tweaker
- charm
- sodium-extras
- dash-loader
- betterend
- chipped
- hex-casting
- angel-rings
- compact-machines

- eden-ring
- quark


## interesting
- programming-8x9craft
- tis-3d
- the throngler

## commands
```
# add more claimable chunks to player
/ftbchunks admin extra_claim_chunks <player> [add|set|get] <value>
/ftbchunks admin extra_force_load_chunks <player> [add|set|get] <value>

/ftbranks add <player> <rank>

/ftbquests change_progress @s complete <quest-id>
```

tag: { Icon: "ftblibrary:textures/icons/friends.png" }
tag: { Icon: "ftblibrary:textures/icons/map.png" }

- `#000000` (top)
- `#575757` (bottom)
- `#E29F00` (text)
- `#441616` (shadow)

