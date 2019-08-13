Requires an Old/New Nintendo 3DS or 2DS console, and a 64-bit Windows PC.

**Preparation**

1. If you're not on the latest TWiLight Menu++ version, please install it using the manual method.    
If your first version was v9.0.0 or later, you can skip this step.
1. Make sure Luma's "boot.firm" is on the SD root as well.


**Part 1: GodMode9**

1. Go to `SYSNAND CTRNAND`.
1. Select `title`.
1. Select `00040138`.
1. Select `#0000102`. (# is 2 on new3DS, and 0 on old3DS)
1. Select `content`.
1. Select `000000##.app`. (## represents any number.)
1. Select `NCCH image options...`.
1. Select `Mount image to drive`.
1. Enter path, when asked to.
1. Select `exefs.bin`
1. Copy to `0:/gm9/out`
1. Power off the console.


**Part 2: Making the widescreen TwlBg, and using it**

1. Download TWL Patcher from [this](https://gbatemp.net/threads/sharp-ds-i-mode-scaling-filters.542694/page-25#post-8752015) post.
1. Copy `exefs.bin` file in `sd:/gm9/out/`, to the same folder as `mkpatch_b.exe`.
1. Rename the .bin file to `section0.bin`.
1. Open Notepad.
1. Put this in Notepad    
> mkpatch_b asd 1010
6. Save as `wide.bat` in the same folder as `mkpatch_b.exe`.
1. Run `wide.bat`.
1. Create a folder called `TwlBg` in `sd:/_nds/TWiLightMenu/`.
1. Copy the newly made `TwlBg.cxi` to the `TwlBg` folder.
1. Rename the cxi file to `Widescreen.cxi`.
1. In Luma config, enable external FIRMs and modules.
1. In TWLMenu++ settings, switch the page to `Games/Apps settings`, and set `Screen Aspect Ratio` to `16:10`.


You're all done! Enjoy your DS games in widescreen!