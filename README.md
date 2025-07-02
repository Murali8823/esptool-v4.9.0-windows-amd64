 esptool.exe --port COM7 -b 115200 --after hard_reset write_flash --flash_mode dio --flash_freq 40m --flash_size detect 0x8000 partition-table.bin 0x1000 bootloader.bin 0x10000 esp32-wifi-penetration-tool.bin
 clone the repo and simply open terminal in the folder after installing c120x drivers and put in this command after typing mode to find the com port in which the esp32 is 
