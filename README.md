
# Pikuniku port for PS VITA

This repos contains patch you can apply on Pikuniku Epic Games Store data files in order to get the game running on PS VITA.
**Please read carefully following sections before going on with the patching procedure**

## Notes

- **Overclock CPU to 500Mhz for best experience**
- Expect FPS between 25 FPS and 30 FPS depending on the scenes except in menus and Ernie part (see below)
- Menus (Main and Pause) are designed in a way it's quite heavy for PS Vita to handle but I decided to not refactor this part as it is not critical (not impacting gameplay)
- Ernie part has some drops because it highly relies on physics. Its jelly effect has been simplified to avoid the game running at 1FPS during this part ;-)
- COOP has been cut off the game as well as some settings in order to optimize menus framerate
- Xray effect has been disabled when wearing Xray glasses
- Some minor graphical glitches could happen here and there
- If not yet done, support the dev by buying the game

## Patching procedure

- Download Pikuniku vpk from vitadb and install it.
- Go to the Release page and download ``PikunikuVitaEPIC.zip``.
- Extract it.
- Put the game's data folder(```Program Files/Epic Games/Pikuniku/Pikuniku_Data```) inside the extracted folder
- Launch ``ApplyPatch.bat`` and wait.
- Let it finish and there should be a .ZIP file named ``PikunikuVita.zip``.
- Open VitaShell, connect your PS Vita to your PC and copy the contents of the .ZIP file```(Zip file should be around 120MB before unpacking)``` over to ``ux0:app/PIKU12345/``.
- Click on "Replace the files in destination" when you are asked to.
- Launch the game and have fun!
