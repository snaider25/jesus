*NOTE:* Starting with v6.8.3, DS game saves are stored in a `saves` folder in exact same folder as the DS ROMs.
Please move them to that folder before updating.

## DSi CFW Update instructions
1. Download the latest version [here](https://github.com/RocketRobz/TWiLightMenu/releases).
2. Copy `_nds/`, the folders in `DSi - CFW users/SDNAND root/`, and `DSi&3DS - SD card users/_nds/` to the root of your SD.
   - When copying from `DSi - CFW users/SDNAND root/` if you're asked to merge, click `Yes`. Be careful if you're on macOS, as it'll overwrite it, instead of merging.
3. In the original DSi Menu, if you see another TWiLight Menu++ icon or a DSiMenu++ or SRLoader icon, delete `53524c41` at `sd:/title/00030015`.

## 3DS CFW Update instructions (via Updater)
1. Install the updater [here](https://github.com/RocketRobz/TWiLightMenu-Updater/releases), if it's not already installed yet.
2. Launch the updater.
3. Touch `Release` next to `TWL Menu++`. Extraction may take a while.
4. Do Step 3 again, but for `nds-bootstrap`.

## 3DS CFW Update instructions (Manual method)
1. Download the latest version [here](https://github.com/RocketRobz/TWiLightMenu/releases).
2. Copy `_nds/` and `DSi&3DS - SD card users/_nds/` to the root of your SD, overwriting the `_nds` folder there.
3. Copy what's in `3DS - CFW users` to the root of your SD.
4. Delete TWiLight Menu++ from DSiWare Data Management in System Settings.
5. Install the two CIAs.

## DSiWarehax Update instructions
1. Download the latest version [here](https://github.com/RocketRobz/TWiLightMenu/releases).
2. Copy `_nds/`, `DSi&3DS - SD card users/_nds/`, and `DSi&3DS - SD card users/boot.nds` to the root of your SD.
