Hex Editing Guide VIA HxD
Written/Cooked by Azu

Hey wassup. Pretty easy tutorial. Created so that it's really easy to hex your own denpas with no confusion. 

First, your gonna need a Hex editor. Many exist although HxD is the most trusted by anyone in the Denpa community.

Second, you're gonna need to get your save file. On citra, right click on the game in the home page and "open save data location" to get your savedata.bin. This is your whole save. On 3ds, use checkpoint to create a backup save of the game. Put your SD into your computer/pc/idk and your saves will be in 3ds/Checkpoint/saves. Your savedata.bin will be here as well.

Third, you'll need the lists of locations. They are in the pins of #the-hacker-hole, and the one that is currently on the top has pretty much them all. The values are the longer strings of numbers such as 25EC for headshape.

The easiest way to get to a desired location is CTRL+G

Fourth, you need the values. These are the small strings of numbers that are always 2 digits long such as 00 or 01. Lets say you want a headshape, you would head to 25EC and change it to... lets say a heart. You would find 25EC and put 11, completely replacing it.

For facial features, you will need the images that come with the locations. They have the numbers right over da part you want to use. However, note that some hairstyles are incorrect.

Setting the bytes per row, which is next to the decoded text language (default is ANSI for windows) to 252 will perfectly align every Denpa Man's values.

Fifth, save. Put the save back in the place you found it. On citra, it will automatically save. On 3ds, you will need to head back to checkpoint and use the "restore" button.

That should be all, thanks for now. 
Best regards, Azulicious.
