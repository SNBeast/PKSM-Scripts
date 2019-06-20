# PKSMScript

## Table of Contents
- [Installing Scripts](#Installing-Scripts)
- [Legality Warning](#Legality-Warning)
    - [Replaced Scripts](#Replaced-Scripts)
    - [Past Gen](#Past-Gen)
- [Script Notes](#Script-Notes)
    - [Mass Inject Scripts](#Mass-Inject-Scripts)
    - [Fill Dex Scripts](#Fill-Dex-Scripts)
    - [Item Scripts](#Item-Scripts)
    - [Reset Scripts](#Reset-Scripts)
    - [Battle Facility Scripts](#Battle-Facility-Scripts)
    - [Other Scripts](#Other-Scripts)
- [Making Scripts](#Making-Scripts)
- [Credits](#Credits)
- [Script file format](#Script-file-format)

## Installing Scripts
If you're using PKSM v6.0.0 or later then you already have most (if not all) scripts already installed

If you're still using PKSM v5.1.x (which is no longer receiving support), do the following:

1. Download the `scripts.7z` from [this release](https://github.com/FlagBrew/PKSM-Scripts/releases/tag/v1.1)
2. Extract the contents and copy the `scripts` folder to your SD card so that its path is `/3ds/PKSM/scripts`

## Legality Warning
>There is risk to using some of these scripts, *particularly on the most recent games* (US/UM and Su/Mo).

The following is a list of unlabeled scripts (with no legal counterpart) known to edit parts of your save to illegal values:

- `all versions` **Set Vivillon Fancy Form** -- any Scatterbug/Spewpa/Vivillon caught or bred after using this will be illegal
- `all versions` **Set Vivillon Pokeball form** -- any Scatterbug/Spewpa/Vivillon caught or bred after using this will be illegal

### Replaced Scripts
Old versions of these scripts included the following elements that could be flagged as illegal if a save is put through strict hack checks

- `USUM, SM` **All items 99x** -- Black Flute, Blue Scarf, Bug Gem, Cherish Ball, Dark Gem, Discount Coupon, Dragon Gem, Dream Ball, Electric Gem, Fairy Gem, Fighting Gem, Fire Gem, Fluffy Tail, Flying Gem, Ghost Gem, Grass Gem, Green Scarf, Greet Mail, Ground Gem, Ice Gem, Macho Brace, Odd Keystone, Old Amber, Pink Scarf, Poison Gem, Psychic Gem, Red Scarf, Relic Band, Relic Copper, Relic Crown, Relic Gold, Relic Silver, Relic Statue, Relic Vase, Rock Gem, Safari Ball, Shoal Salt, Shoal Shell, Sport Ball, Steel Gem, Water Gem, White Flute, Yellow Scarf
- `USUM, SM` **All Medicine 99x** -- Blue Flute, Red Flute, Yellow Flute
- `USUM, SM` **All berries 99x** -- Razz Berry, Nanab Berry, Wepear Berry, Cornn Berry, Magost Berry, Rabuta Berry, Nomel Berry, Spelon Berry, Pamtre Berry, Watmel Berry, Durin Berry, Belue Berry
- `ORAS` **Unlock & max all O-Powers** -- unreleased S levels
- `ORAS, XY` **Give all items 99x** -- Bug Gem, Cherish Ball, Dark Gem, Dragon Gem, Electric Gem, Fairy Gem, Fast Ball, Fighting Gem, Fire Gem, Flying Gem, Friend Ball, Ghost Gem, Grass Gem, Ground Gem, Heavy Ball, Ice Gem, Level Ball, Love Ball, Lure Ball, Moon Ball, Odd Keystone, Park Ball, Poison Gem, Psychic Gem, Relic Band, Relic Copper, Relic Crown, Relic Gold, Relic Silver, Relic Statue, Relic Vase, Rock Gem, Safari Ball, Sport Ball, Steel Gem, Water Gem
- `B2W2, BW` **Give all items 99x** -- Blue Scarf, Cherish Ball, Dream Ball, Fast Ball, Friend Ball, Green Scarf, Heavy Ball, Level Ball, Love Ball, Lure Ball, Moon Ball, Park Ball, Pink Scarf, Red Scarf, Safari Ball, Sport Ball, Yellow Scarf
- `B2W2, BW` **Give all berries 99x** -- Rabuta Berry, Pamtre Berry
- `HGSS` **Give all pokeballs 99x** -- Cherish Ball, Park Ball, Sport Ball
- `PT, DP` **Give all pokeballs 99x** -- Cherish Ball
- `DP` **Give all items 99x** -- Shoal Salt, Shoal Shell

### Past Gen
These scripts may cause problems in the unlikely event you should ever have to go through thorough hack checks

- `HGSS` **Unlock all Pokewalker Courses** -- Rally, Sightseeing, and Amity Meadow were not released for all regions
- `HGSS, PT` **Give all items 99x** -- Griseous Orb (untradeable and only one can be obtained per file)
- `PT, DP` **Get all Pokewatch apps** -- Alarm Clock and Stopwatch were never released

## Script Notes
These are notes and details that may be useful to know about scripts that couldn't be summarized to fit in scripts' names

### Mass Inject Scripts
- All mass injection scripts target the first slot of Box 1 to start injecting the collection. If you're worried about losing some of your Pokémon, make sure to clear out enough of your in-game boxes to make room
    - **Living Dex**
        - Gen 5: 22 boxes
        - Gen 6: 25 boxes
        - Gen 7: 27 boxes
    - **Colosseum**: 2 boxes
    - **XD**: 3 boxes
    - **PKX injector**: 1 slot for every `.pk*` or `.pb7` file in `/3ds/PKSM/inject`
    - everything else: 1 box
- Not all Pokémon in the mass injection scripts may be legal
- Only the "Living Dex" scripts update your dex. If you want the contents of a mass inject script to be registered but don't want the full Fill Dex, do one of the following:
    - deposit the unregistered Pokémon in the Day Care then withdraw them
    - take them into a wild battle (reported to work but not confirmed)
- **rBreedingDitto**: the Ditto in these scripts were obtained from [this list on /r/BreedingDittos](https://www.reddit.com/r/BreedingDittos/comments/2wqabp/giveaway_so_you_want_a_ditto/). They are subject to all the conditions and limits set by /r/BreedingDittos (so don't try passing them off as legal on /r/pokemontrades)

### Fill Dex Scripts
- Regional Pokédex scripts will overwrite anything you've seen (and owned if you use the "owned" version) which may cause you to lose registration of anything not in your game's regional Pokédex
- These scripts will fill your dex enough to unlock access to the following rewards:
    - `PT, DP` **Sinnoh seen**: regional dex diploma, National dex upgrade
    - `HGSS` **Johto owned**: regional dex diploma
    - `HGSS, PT, DP` **National owned**: national dex diploma
    - `BW` **Unova owned**: regional dex diploma
    - `BW` **National owned**: national dex diploma
    - `B2W2` **Unova seen**: Permit (for visiting Nature Preserve)
    - `B2W2` **Unova owned**: regional dex diploma, Oval Charm
    - `B2W2` **National owned**: national dex diploma, Shiny Charm
    - `XY` **Kalos seen**: Oval Charm
    - `XY` **Kalos owned**: regional dex diplomas (Central, Coastal, Mountain, Kalos)
    - `ORAS` **Hoenn seen**: Oval Charm
    - `ORAS` **Hoenn owned**: regional dex diploma
    - `ORAS, XY` **National owned**: national dex diploma, Shiny Charm
    - `USUM, SM` **Alola owned**: Shiny Charm
- **National** versions will also unlock access to all corresponding regional rewards
- **owned** versions will also unlock access to all corresponding **seen** rewards
- **Complete** versions will unlock all the same rewards as the **National owned** versions
- Only the **Complete** versions will fill in Mythicals (Mew, Celebi, Jirachi, etc.)
- Only the **Complete (illegal)** versions will unlock *all* forms and shiny sprites, including unreleased ones

### Item Scripts
- `USUM, SM` **slot 1 x897-960**: due to the way items are stored in Gen 7 saves and the current limitations of PKSM's scripts, the quantity of the item in the pouch's first slot is set to something in the range of 897 to 960 (depends on the former quantity) rather than 999 like in past generations
- `B2W2, BW` **Item slot 1 - Pass Orb x65535**: this was only added because the MAX level Pass Powers require 9999 to use, which is more than existing scripts give. Also note that the game will display the amount weirdly, like `?35`

### Reset Scripts
- `all games` **Reset [pokemon]**: Allows any listed Pokémon to be re-obtained (if gift) or re-battled
- `USUM` **Reset Main Conflict**: resets everything between getting to the Altar of the Sunne/Moone and encountering Mina
- `USUM` **Reset Postgame**: resets it back to the start of the Rainbow Rocket arc, when you enter your house, you meet Sophocles and go the Festival Plaza
- `USUM` **Reset Nanu Event**: ?
- `USUM` **Reset Team Skull Pose Event**: resets the event in Po Town where you help the Team Skull Grunt who can't make the Team Skull pose
- `USUM` **Reset Janitor Event**: resets the event that happens when you talk to the janitor in Hau'oli Mall
- `USUM` **Reset Shiny Exeggcute Battle**: resets the battle against the Poni Island trainer with the shiny Exeggcute
- `USUM` **Remove Stakataka and Blacephalon**: the reset scripts for these two cause them to respawn indefinitely after capture/defeat so this script was made to allow users to end that if they want
- `USUM` **Reset Red and Blue**: resets initial Battle Tree event in which you battle Red or Blue
- `ORAS` **Reset Delta Episode**: resets back to before the battle with Wallace in front of Sky Pillar
- `B2W2, BW` **Reset Geonet**: allows you to change the location you registered on the Geonet
- `B2W2` **Reset N and Shadow Triad battles**: allows you to rematch the trainers without waiting for the season to change
- `B2W2` **Reset Bianca/Cheren Battle**: You will need to have used Memory Link at least once
- `B2W2` **Reset most Memory Link cutscenes**: You will need to have used Memory Link at least once. The only the Pokémon Musical scene is not reset.
- `HGSS` **Reset Sinjoh Ruins**: resets the event where you take an Arceus to the Ruins of Alph and eventually receive a lv1 Dialga/Palkia/Giratina holding its respective Orb
- `HGSS` **Reset Red**: respawns Red at Mt. Silver without having to defeat the Elite Four
- `HGSS` **Legendary Beasts Full**: Will place all 3 in the basement of Burned Tower, allowing you to release them again. You won't have to chase Suicune around Johto and Kanto again. *__Use with caution__ -- all side effects haven't been fully explored yet*
- `HGSS` **Roamer Lati Full**: This will allow you to repeat the Steven event that spawns the Lati-twin to roam around Kanto. Similar to the script above along with the same disclaimers. Also, **MAKE SURE YOU RUN THIS SCRIPT WHEN YOU ARE SAVED INSIDE THE FAN CLUB OF VERMILION CITY**
- `HGSS` **Legendary Beasts Safe**: The safe script simply sets the roamer's status from captured to defeated and will start roaming again once the Elite 4 is defeated again
- `HGSS` **Roamer Lati Safe**: The safe script simply sets the roamer's status from captured to defeated and will start roaming again once the Elite 4 is defeated again
- `HGSS` **Shuckle**: Resets gift Shuckle received in Cianwood City. After you beat the game, you cannot receive Shuckle anymore
- `DP` **Set all legendaries battlable/disappeared**: same as **Reset [pokemon]** above

### Battle Facility Scripts
- `all games` **Streak**: sets the current streak to just before a meaningful battle (facility leader, item reward, etc.)
- `HGSS, PT` **Battle Factory Max Trades**: This will set your trade count to 9999. The more trades you do, the better Pokemon you can choose to rent at the start
- `HGSS, PT` **Battle Castle Points**: This will set your CP to 9999, allowing you to buy as many upgrades, items, heals, skips etc as you want. Note, you don't unlock the ability to skip a battle until you win 21 battles.
- `B2W2, BW, HGSS, PT, DP` **Skip to Last Battle**: Only effective if you quicksave. Lets you can skip straight to the 7th battle in the set
    - `HGSS, PT` **Battle F-A-C**: F = Factory, A = Arcade, C = Castle
- `all games` **Use party**: Allows you to use the members of your party, starting from the first.
    - ***Legality Warning***: This can let you smuggle in otherwise banned species (such as mascot legends)

### Other Scripts
- `all games` **Quick hatch**: does **NOT** hatch your eggs for you -- it just makes the eggs hatch in as few steps as possible
- `all games` **Day Care Set Exp**: sets the experience gained from the Day Care for both (all 4 in ORAS) slots
- `USUM, SM` **Shop 6 Tent Bonus**: set which bonus is active from the tent shop located in slot 6 (requires a tent shop to be in that slot)
- `USUM` **Set 100 hatched eggs**: set the number of hatched eggs to 100 so that you can just talk to the stats judge to unlock IV checking in the PC
- `USUM` **Set Sun/Moon time**: sets the in-game time of day, to allow access to time limited events (only available during day/night)
- `ORAS, XY` **Supreme Honor Pokepuffs**: fill all 100 Pokepuff slots with Supreme Honor Pokepuffs
- `ORAS, XY` **Pokemon Link**: These codes will allow you to acquire these event Pokemon from the Pokemon Link on the main menu. Until you claim it in-game, using more than one at a time will overwrite any you've already injected. If you care about legality, Celebi can only come from X & Y and Glalie and Steelix can only be received from ORAS.
- `ORAS` **Mirage Spots**: Sets the available Mirage Spots to the set selected, all of which also include Crescent Isle where you can find Cresselia. Spots will change when the date changes, and may change if you pass people through the PSS
- `XY` **Set Kanto Bird - 10 encounters**: Beat the Elite Four, encounter the roaming Kanto bird (Articuno, Zapdos, Moltres) once, and it will go to Sea Spirit's Den
- `B2W2, BW` **Pass Power MAX**: changes your currently equipped Pass Power. These MAX versions are as powerful as Lv3 and last for 1 full hour, but cost 9999 Pass Orbs to activate so you will need to use these along with the **Items slot 1 - Pass Orb x65535** script
- `B2W2, BW` **Season**: changes the current season of the save -- Note that changing area (leaving a building/cave, changing route, etc.) will update the season to match the system's current date
- `B2W2` **Hidden Grotto**: Some species may be version exclusive and not in the game you use the script on. Will always have their Hidden Ability
- `B2W2` **Join Avenue - Restock All Shops**: This will refill all the shops contents and therefore, you can buy from all the shops again without having to wait for the next day.
- `B2W2` **Join Avenue - 7 Day Promotion**: This will cause a week long promotional event. When this code is used, for one week from when the game was last saved, all the shop's items are only half price!
- `B2W2` **Join Avenue - Lv9 All Shops**: this code will set all of your shops to level 9 and as such, only one visitor referral will be necessary to max out each shop
- `B2W2, BW, HGSS` **Swarm**:
    - `B2W2, BW`: The swarm you choose may not stick if the "last saved" date on your save does is before the current date according to the system you next play on.
    - `B2W2, BW`: Route 8 is frozen over in Winter so you may be unable to encounter Croagunk (BW) or Quagsire (B2W2) after setting it as the active swarm.
    - `HGSS`: due to the inability to tell HG saves apart from SS saves (by their content alone), both games will see "Baltoy / Gulpin" with Baltoy's sprite and "Sableye / Mawile" with Sableye's sprite on the selection screen despite Baltoy and Sableye only appearing in HG and Gulpin and Mawile only appearing in SS
- `BW` **Black City White Forest**: lets you manipulate which residents are in your Black City (Black) or White Forest (White). `Front` means you will see the resident in your game, `Back` means that others will see the resident when they connect to your game via Entralink. For more details on what particular residents provide, see Bulbapedia's pages on [Black City](https://bulbapedia.bulbagarden.net/wiki/Black_City) and [White Forest](https://bulbapedia.bulbagarden.net/wiki/White_Forest).
- `HGSS, PT, DP` **Lotto ID Number**: number matches one of the in-game trades
    - `PT, DP` - Abra (Oreburgh)
    - `HGSS` - Machop (Goldenrod Department Store)
- `HGSS` **Rematch All Gym Leaders**: sets up rematch with Gym Leader in Saffron Dojo
- `Pt, DP` **Fulfill Spiritomb encounter requirements**: sets everything up so that you will battle Spiritomb the next time you examine the Broken Tower / Hallowed Tower on Route 209 (between Hearthome and Solaceon)
- `PT, DP` **Great Marsh**: lets you pick which species fill each area's daily binocular Pokémon
- `PT, DP` **Level Man**: controls the man in the house west of the Pal Park, who gives an item if you show him a Pokémon of a certain level
- `PT, DP` **All Berries Watered**: waters all berry plots in region
- `PT, DP` **Berries - Floaroma/Eterna Harvestable**: If nothing planted in plots, a running sprite of the male character will appear in the plot. You can harvest from them with no known problems, although you'll get nothing.
    - **Floaroma**: includes plots within Floaroma Town as well as plots on the way to Valley Windworks
    - **Eterna**: includes all plots from Valley Windworks to Eterna City
- `PT` **Sets total steps to 299,999**: allows easy unlocking of Chandelier in the Resort Area Villa

---

## Making Scripts
See the [docs README](https://github.com/FlagBrew/PKSM-Scripts/blob/master/dev/README.md)

---

## Credits
- bernardogiordano - PKSM, PKSMScript.py, dump.py, scripts
- Lavorther - scripts
- piepie62 - PKSM's picoC API, genScripts.py, scripts
- PKMWM1 - scripts
- PlasticJustice - scripts
- SpiredMoth - scripts, documentation, dev scripts (all Node and some Python)
- trainboy2019 - scripts
- wrathsoffire - scripts

---

## Script file format

```
# "Legacy" PKSM script structure
# u8 magic[10]        // PKSMSCRIPT
# u32 offset          // save offset to write the data to
# u32 length          // payload length
# u8 payload[len]     // payload data
# u32 repeat_times    // repeat payload n times
# ...
```
