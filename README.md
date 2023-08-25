
# Pixel Experience Plus Release for Yunluo(Redmi Pad)

- Flashing the recovery: 
    - Download the latest platform-tool for your device from [here](https://developer.android.com/tools/releases/platform-tools).
    - Download boot.img and vendor_boot.img from above.
    - Reboot your tablet into bootloader fastboot mode (using Volume Down Key or ```adb reboot bootloader```)
    - Flash the provided boot image using ```fastboot flash boot boot.img```
    - Flash the provided vendor_boot image using ```fastboot flash vendor_boot vendor_boot.img```
    - Reboot your tablet using ```fastboot reboot``` and hold the Volume Up until you see the recovery screen

## Once the device boots into recovery:
- Perform a factory reset by ```Factory Reset --> Format Date```
- Sideload the rom by: ```Apply Update --> Apply from ADB```
- On PC type ```adb sideload <Drag and drop Rom Into Terminal>```
- If verification Fails, just hit "Yes" on recovery.
- Select ```Reboot system now``` on recovery option after flashing finishes.

## After successful boot:
 - While setting up the device skip adding device lock (You may add that later from settings). This is to ensure face lock doesn't show during setup.
- Face unlock doesnt work. If you're stuck at setting up face unlock screen, keep doing it 2-3 times until you get the cancel option.

## Warning:
- You are using this ROM at your own will, hence you are soley responsible for any damage that you may inflict on you device or you.
