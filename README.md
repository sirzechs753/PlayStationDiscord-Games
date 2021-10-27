# What i Change

- Added PS5 Locale support for en-US en-CA by [@CodyRWhite](https://github.com/CodyRWhite) [Pull Request](https://github.com/Tustin/PlayStationDiscord-Games/pull/149) in the [original  repo](https://github.com/Tustin/PlayStationDiscord-Games) by [@Tustin](https://github.com/Tustin)
- Added PS5 Locale support for en-id
- Added Filter Support for PS5 games (only grab ps5 games listed in [games.yml](https://github.com/sirzechs753/PlayStationDiscord-Games/blob/master/games.yml))
- Added PS5 backward compatibility support (clone ps4 games in [games.json](https://github.com/sirzechs753/PlayStationDiscord-Games/blob/master/games.json) to ps5 section)

# How to Use

- Install node js
- Clone my forked [PlayStationDiscord](https://github.com/sirzechs753/PlayStationDiscord)
- Follow the instruction in [Developing](https://github.com/sirzechs753/PlayStationDiscord#developing) section

## Adding titles 

- Open an Issue with feature request
- List the titleId and the name of the game you want to add

## Limitation

Due to discord rich presence assets limited to 300 per application, number of ps4 + ps5 games listed in [games.yml](https://github.com/sirzechs753/PlayStationDiscord-Games/blob/master/games.yml) must be 300 or lower for PS5 backward compatibility to work.

# PlayStationDiscord-Games

Games which are supported for [PlayStationDiscord](https://github.com/Tustin/PlayStationDiscord).

[![Build Status](https://travis-ci.org/Tustin/PlayStationDiscord-Games.svg?branch=master)](https://travis-ci.org/Tustin/PlayStationDiscord-Games)

## Adding titles

1. Fork the repo
2. Modify `games.yml` and add the title id(s) you want (use the same format I used) **Please don't modify `games.json`, this file should be read-only and only modified by the script.**
3. Open a PR with your changes.

## Supported Games

|                               Icon                                |                                                                   Title                                                                    |
|-------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
|<img src="ps5/PPSA01491_00.png?raw=true" width="100" height="100">|Assassin's Creed Valhalla                                                                                                                   |
|<img src="ps5/PPSA01325_00.png?raw=true" width="100" height="100">|ASTRO's PLAYROOM                                                                                                                            |
|<img src="ps5/PPSA01502_00.png?raw=true" width="100" height="100">|Bugsnax                                                                                                                                     |
|<img src="ps5/PPSA01628_00.png?raw=true" width="100" height="100">|Call of Duty®: Black Ops Cold War                                                                           |
|<img src="ps5/PPSA02048_00.png?raw=true" width="100" height="100">|Dead by Daylight PS4™ & PS5™                                                                                                                |
|<img src="ps5/PPSA01342_00.png?raw=true" width="100" height="100">|Demon's Souls                                                                                                                               |
|<img src="ps5/PPSA02562_00.png?raw=true" width="100" height="100">|Genshin Impact                                                                                                                              |
|<img src="ps5/PPSA01347_00.png?raw=true" width="100" height="100">|Godfall                                                                                                                   |
|<img src="ps5/PPSA02181_00.png?raw=true" width="100" height="100">|Guilty Gear -Strive-                                                                                                                        |
|<img src="ps5/PPSA01411_00.png?raw=true" width="100" height="100">|Marvel's Spider-Man: Miles Morales                                                                                                |
|<img src="ps5/PPSA01387_00.png?raw=true" width="100" height="100">|NBA 2K21 Next Generation                                                                                                                    |
|<img src="ps5/PPSA01556_00.png?raw=true" width="100" height="100">|Resident Evil Village                                                                                              |
|<img src="ps4/CUSA07022_00.png?raw=true" width="100" height="100"> |Fortnite                                                                                                                                    |
|<img src="ps4/CUSA05042_00.png?raw=true" width="100" height="100"> |Destiny 2                                                                                                                                   |
|<img src="ps4/CUSA11100_00.png?raw=true" width="100" height="100"> |Call of Duty®: Black Ops 4                                                                                                                  |
|<img src="ps4/CUSA05969_00.png?raw=true" width="100" height="100"> |Call of Duty®: WWII                                                                                                                         |
|<img src="ps4/CUSA04762_00.png?raw=true" width="100" height="100"> |Call of Duty®: Infinite Warfare                                                                                                             |
|<img src="ps4/CUSA03522_00.png?raw=true" width="100" height="100"> |Call of Duty®: Modern Warfare® Remastered                                                                                                   |
|<img src="ps4/CUSA02290_00.png?raw=true" width="100" height="100"> |Call of Duty®: Black Ops III                                                                                                                |
|<img src="ps4/CUSA00803_00.png?raw=true" width="100" height="100"> |Call of Duty®: Advanced Warfare                                                                                                             |
|<img src="ps4/CUSA00018_00.png?raw=true" width="100" height="100"> |Call of Duty® Ghosts                                                                                                                        |
|<img src="ps4/CUSA08724_00.png?raw=true" width="100" height="100"> |Battlefield™ V                                                                                                                              |
|<img src="ps4/CUSA08829_00.png?raw=true" width="100" height="100"> |Call of Duty®: Modern Warfare®                                                                                                              |
|<img src="ps4/CUSA05770_00.png?raw=true" width="100" height="100"> |STAR WARS™ Battlefront™ II                                                                                                                  |
|<img src="ps4/CUSA05877_00.png?raw=true" width="100" height="100"> |Persona 5                                                                                                                                   |
|<img src="ps4/CUSA02299_00.png?raw=true" width="100" height="100"> |Marvel's Spider-Man                                                                                                                         |
|<img src="ps4/CUSA07413_00.png?raw=true" width="100" height="100"> |God of War                                                                                                                                  |
|<img src="ps4/CUSA07408_00.png?raw=true" width="100" height="100"> |God of War                                                                                                                                  |
|<img src="ps4/CUSA00744_00.png?raw=true" width="100" height="100"> |Minecraft                                                                                                                                   |
|<img src="ps4/CUSA01163_00.png?raw=true" width="100" height="100"> |Rocket League®                                                                                                                              |
|<img src="ps4/CUSA03041_00.png?raw=true" width="100" height="100"> |Red Dead Redemption 2                                                                                                                       |
|<img src="ps4/CUSA01788_00.png?raw=true" width="100" height="100"> |Tom Clancy's Rainbow Six® Siege                                                                                                             |
|<img src="ps4/CUSA07211_00.png?raw=true" width="100" height="100"> |FINAL FANTASY VII REMAKE                                                                                                                    |
|<img src="ps4/CUSA14168_00.png?raw=true" width="100" height="100"> |RESIDENT EVIL 3                                                                                                                             |
|<img src="ps4/CUSA09249_00.png?raw=true" width="100" height="100"> |Call of Duty®: Modern Warfare® 2 Campaign Remastered                                                                                        |
|<img src="ps4/CUSA12031_00.png?raw=true" width="100" height="100"> |KINGDOM HEARTS Ⅲ                                                                                                                            |
|<img src="ps4/CUSA15322_00.png?raw=true" width="100" height="100"> |Sid Meier's Civilization VI                                                                                                                 |
|<img src="ps4/CUSA02320_00.png?raw=true" width="100" height="100"> |Uncharted: The Nathan Drake Collection™                                                                                                     |
|<img src="ps4/CUSA09311_00.png?raw=true" width="100" height="100"> |Assassin's Creed® Odyssey                                                                                                                   |
|<img src="ps4/CUSA05933_00.png?raw=true" width="100" height="100"> |KINGDOM HEARTS - HD 1.5+2.5 ReMIX -                                                                                                         |
|<img src="ps4/CUSA06412_00.png?raw=true" width="100" height="100"> |TERA                                                                                                                                        |
|<img src="ps4/CUSA15233_00.png?raw=true" width="100" height="100"> |Black Desert                                                                                                                                |
|<img src="ps4/CUSA00288_00.png?raw=true" width="100" height="100"> |FINAL FANTASY XIV                                                                                                                           |
|<img src="ps4/CUSA09032_00.png?raw=true" width="100" height="100"> |YAKUZA 6: The Song of Life                                                                                                                  |
|<img src="ps4/CUSA00003_00.png?raw=true" width="100" height="100"> |DRIVECLUB™                                                                                                                                  |
|<img src="ps4/CUSA00559_00.png?raw=true" width="100" height="100"> |The Last of Us™ Remastered                                                                                                                  |
|<img src="ps4/CUSA17777_00.png?raw=true" width="100" height="100"> |Spellbreak                                                                                                                                  |
|<img src="ps4/CUSA05855_00.png?raw=true" width="100" height="100"> |Assassin's Creed® Origins                                                                                                                   |
|<img src="ps4/CUSA03173_00.png?raw=true" width="100" height="100"> |Bloodborne™                                                                                                                                 |
|<img src="ps4/CUSA10249_00.png?raw=true" width="100" height="100"> |The Last of Us™ Part II                                                                                                                     |
|<img src="ps4/CUSA17416_00.png?raw=true" width="100" height="100"> |Persona 5 Royal                                                                                                                             |
|<img src="ps4/CUSA00223_00.png?raw=true" width="100" height="100"> |inFAMOUS Second Son™                                                                                                                        |
|<img src="ps4/CUSA26225_00.png?raw=true" width="100" height="100"> |Splitgate                                                                                                                                   |
|<img src="ps4/CUSA19210_00.png?raw=true" width="100" height="100"> |Guilty Gear -Strive-                                                                                                                        |
|<img src="ps4/CUSA01842_00.png?raw=true" width="100" height="100"> |Overwatch: Origins Edition                                                                                                                  |
|<img src="ps4/CUSA08444_00.png?raw=true" width="100" height="100"> |Dead by Daylight                                                                                                                            |
|<img src="ps4/CUSA01606_00.png?raw=true" width="100" height="100"> |Skullgirls 2nd Encore                                                                                                                       |
|<img src="ps4/CUSA11192_00.png?raw=true" width="100" height="100"> |BLAZBLUE CROSS TAG BATTLE                                                                                                                   |
|<img src="ps4/CUSA13338_00.png?raw=true" width="100" height="100"> |DOOM Eternal                                                                                                                                |
|<img src="ps4/CUSA00419_00.png?raw=true" width="100" height="100"> |Grand Theft Auto V                                                                                                                          |
|<img src="ps4/CUSA10218_00.png?raw=true" width="100" height="100"> |Horizon Zero Dawn™: Complete Edition                                                                                                        |
|<img src="ps4/CUSA08392_00.png?raw=true" width="100" height="100"> |Detroit: Become Human                                                                                                                       |
|<img src="ps4/CUSA23678_00.png?raw=true" width="100" height="100"> |Genshin Impact                                                                                                                              |