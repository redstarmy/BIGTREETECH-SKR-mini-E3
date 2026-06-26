# Build Firmware

Use this when you only need to change the Marlin config and download a new firmware file.

1. Open `firmware/V2.0/Marlin-2.0.8.2.x-SKR-mini-E3-V2.0/Marlin/Configuration.h`.
2. Click the pencil icon, make your changes, then click **Commit changes**.
3. Open `firmware/V2.0/Marlin-2.0.8.2.x-SKR-mini-E3-V2.0/Marlin/Configuration_adv.h`.
4. Click the pencil icon, make your changes, then click **Commit changes**.
5. Click the **Actions** tab.
6. Open the latest **Build firmware** run.
7. When it finishes, download the `firmware-bin` artifact.
8. Unzip the download and copy `firmware.bin` to the printer SD card.

The file on the SD card must be named `firmware.bin`.
