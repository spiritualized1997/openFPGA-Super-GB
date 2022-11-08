# openFPGA-Super-GB
Super Gameboy core for openFPGA on Analogue Pocket
-

Everything Super Gameboy Should be supported by this core, including
playing real cartridges through the cartridge slot!

To use this core, two files need to be placed into the  
/assets/sgb/Spiritualized.SuperGB/ folder:

sgb_boot.bin - the 256 byte boot ROM for the GB CPU  
sgb_snes.smc - the 256K or 512K BIOS for the SNES  

You can use either SGB or SGB2 files.  

To run real cartridges, select "run_cartridge.gb" for the game,
which is included in this package.

Up to 4 players are supported using the dock.
