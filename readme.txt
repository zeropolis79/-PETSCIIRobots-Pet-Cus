Petscii Robots 1.2/GFX For the Commodore PET
--------------------------------------------

There are two versions of the game included in this distro.
-PETROBTOS12.D64 - This is the latest version of the game which runs completely in PETSCII graphics.
-PETGFX.D64 - This version requires a custom character ROM to use, see below.

The GFX version the ultimate experience of Petscii Robots for the Commodore PET.  In order to play, it does require replacing the character ROM, whether that be in your emulator or on a real PET.  Two character ROMs are included.  One is a 2K version for VICE or a real PET.  The other is for a Mini-PET, which uses a 32K EPROM.  

The PET has two built-in character sets.  Neither can be modified, but you can switch between them. The first set, which is typically the default set on most PETs is the upper-case with graphics.  Petscii Robots GFX uses the second character set, which replaces the upper/lower case set.  

The benefit of this is that 95% of PET programs use the first set, so this means you will retain compatibiltiy with most PET programs.  When Petscii Robots GFX starts, it will switch to the secondary set, which should contain the modified character set.  If the screen looks strange or like it has garbage characters, you probably don't have the ROM image installed correctly.

BURNING A ROM:
-------------
Obviously, I can't help you with the details of that.  But I've included two ROMs.  One is for the Mini-PET because it uses a 32K EPROM with 4 different fonts.  This replaces the lower-case set of FONT-4 on the Mini-PET. For a real PET, you can burn the 2K EPROM.  In this case the PET still boots to the regular uppercase/graphics font.  So most programs will still work fine.  The secondary charset (upper/lower case) is the one that is replaced.  If you have one of the business models that boots to the secondary character set, then obviously you will see the new font immediately on boot.

VICE EMULATOR
-------------
If using the VICE emulator, you will find the ROM is called "chargen" and is located under the PET folder.  However, it is best to leave that ROM alone and just configure it in the emulator under Setttings/ROM settings.  Find the "character" section and browse to the "CHAR-ROM (VICE).BIN" that is included with this distro.

If you have any questions I recommend asking on the Petscii Robots facebook group:
https://www.facebook.com/groups/975620876261750

alternatively, you can email me directly - dfwgreencars@gmail.com

