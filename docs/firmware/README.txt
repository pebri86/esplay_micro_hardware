How to deploy bootloader and emulation firmware to ESPlay Micro

Preparation
-----------

1. Micro USB Cable
2. Micro SDCard
3. Install esptool
   >pip install esptool

Installation
------------

1. open the firmware folder and execute flash.bat under windows or flash.sh under linux (don't forget to make it executable first by chmod +x).
2. if the operation success the esplay will boot into bootloader menu.
3. copy esplay, mp3 and roms folder to root of microsd card.
4. put the card to ESPlay Micro sdcard slot.
5. turn on the board and the bootloader will show list of firmware file available in this case it will display esplay-retro-emu.fw and mp3-player_DAC.fw
6. To flash the firmware select the file then press A then Start, wait until flashing done then it will automatically restart and boot to application.
7. Place the rom of emulator on roms folder to the appropriate folder example game gear rom to gg folder, gameboy rom to gb folder and so on.

