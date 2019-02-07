## Q: Why do I get a white screen when trying to load a game from SD Card?    
A: 
- First, check [the nds-bootstrap compatibility list](https://docs.google.com/spreadsheets/d/1LRTkXOUXraTMjg1eedz_f7b5jiuyMv2x6e_jY_nyHSc/htmlview#gid=0) and make sure your game is compatible.
- If the game your trying to launch is a DSi Enhanced game then make sure that TWiLight Menu++ is set to use `DS Mode`.
- If you're on a CFW DSi make sure that your launching `HIYACFW` in Unlaunch, *not `TWLMENUPP`*, as nds-bootstrap requires Hiya CFW.

## Q: How do I use cheats?
A: You need to have the file `sd:/_nds/TWiLightMenu/extras/usrcheat.dat`. The most updated cheat database is [DeadSkullzJr's](https://gbatemp.net/threads/deadskullzjrs-flashcart-cheat-databases.488711/).

## Q: How do I show a custom picture on the top screen of the DSi theme?
A: A random `.bmp` file in `sd:/_nds/TWiLightMenu/dsimenu/photos/` will be shown each time the menu is loaded. The file(s) must be a 16-bit (X1 R5 G5 B5) bmp file with a resolution of 208x156, and no color space info.

## Q: Why isn't touch input working on sudokuhax?    
A: Depending on the save file of sudokuhax, the touch screen inputs may not work.

## Q: Can The Biggest Loser boot TWiLight Menu++?    
A: No. As The Biggest Loser is a Slot-1 game, and not a DSiWare game, SD access is disabled when running Slot-1 cards.
