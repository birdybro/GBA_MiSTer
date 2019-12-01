# GBA_MiSTer
GBA for MiSTer

# HW Requirements/Features
- Requires 32MB SDRAM for games less than 32MB. 32MB games require either 64MB or 128MB module.
- HDMI-only. Native VGA output is not implemented (yet). VGA output can be enabled with vga_scaler=1 option in MiSTer.ini, so it will output the same HDMI resolution.

# Bios
Opensource Bios from Normmatt is included, however it has issues with some games.
Original GBA BIOS can be placed to GBA folder with name boot.rom

PLEASE do not report errors without testing with the original BIOS

# Games with crashes/hang
- Banjo-Kazooie hangs after start. Workaround: instantly save ingame, reset the game and reload the save
- Boktai 2 hangs in language selection
- Bomberman Max 2 - Blue: black screen after intro

- Colin McRae Rally 2.0 hangs when going into race

- Dai-Mahjong: instant crash
- Digimon Racing: hang on 3rd screen(Griptonite)

- Fear Factor Unleashed: hang after ~4 seconds

- Madden: all games not working

- Nihon Pro Mahjong Renmei Kounin Tetsuman Advance - Menkyo Kaiden Series: instant crash

- Iridium II: hangs at first boss

- Mobile Suit Gundam Seed Battle Assault (USA) - crashes during the intro
- Motoracer Advance (USA) : Game crashes upon starting a race.

- Rocky: hang on first screen

- Sennen Kazoku: hang on first screen
- Starsky & Hutch: crash going ingame
- SuperMarioAdvance: MarioBros Minigame hangs. Same game is included  and working in Super Mario Advance 2

- TOCA World Touring Cars: hangs going into race
- Top Gun - Combat Zones: doesn't recognize A-button in main menu

# Games with black bars in 3D view
- Doom2
- DukeNukem
- IceNine
- Fifa 06/06 (only 1st person view)
- Need for Speed(all 5 games)
- Ultimate Winter Games
- Winter Sports

# Games that are unplayable because of catridge hardware missing
- Boktai 1/2/Shin Bokura no Taiyou(Japanese Boktai)
- Warioware Twisted
- Yoshi's Universal Gravitation

# Games that refuse playing because of copy protection
- Nes/Famicon classics (most of them)
- Dragon Ball Z - Taiketsu
- Dragon Ball Z - The Legacy of Goku

# Status
~1600 games tested until ingame:
- 95% without major issues (no crash, playable)

# Features
- all videomodes including affine and special effects
- all soundchannels
- saving as in GBA
- turbomode

# Not included
- Multiplayer features like Serial
- Tilt/Gyro/Rumble/Sun sensor)
- RTC
