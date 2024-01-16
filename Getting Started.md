This is a modding guide for Fate (steam version)

Directory:  Program Files (x86)\Steam\steamapps\common\    windows + r  \Program Files (x86)\Steam\steamapps\common\
Temp Files: ProgramData\WildTangent\FateSteam\Cache        windows + r  %ProgramData%

What is covered:
ICONS, ITEMS, MENU, MONSTERS, MUSIC, PLAYER (includes town NPCs), SOUNDS, SPELLS


Notable Files

items.dat           contains all items, including spell scrolls

monsters.dat        contains all monsters, including pets

races.dat           contains all starting class data (not in the original fate)

quests.dat          contains all quests

spells.dat          contains all spell projectiles and effects

tips.dat            contains all tips

manifest.dat        enables dungeon templates for generation and can be used to enable or disable dungeon generation types (also known as templates)

caves.dat, cellar.dat, manifest.dat, mine.dat, mine2.dat, ruins.dat, seacellar.dat, sewers.dat, volcano.dat, wood.dat


If changes are not being made:

Delete Temp Files at (C:\ProgramData\WildTangent\FateSteam\Cache); this will force Fate to pull from the modified directory again since there are no cached files to use.

Replace Copies in Langauge folders. Sometimes, when modifying a file (ie. items.dat), your selected language will be a folder (ie. en-US), which may contain a copy of the unmodified file, which will take priority.
