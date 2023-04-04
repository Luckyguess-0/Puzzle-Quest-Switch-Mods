# Puzzle-Quest-Old-Icons
The icons in the remake of Puzzle Quest are pretty bad so I replaced them for the switch. Upscaled and made yellow a little brighter too.

Before:
![before](https://user-images.githubusercontent.com/90596580/229689251-8f814d8a-a0b4-4ed9-b8e1-e289ea6cabd9.PNG)
After:
![after](https://user-images.githubusercontent.com/90596580/229689257-c1bdd0f9-fd12-4758-b709-8da7fa3dae95.PNG)

# Puzzle-Quest-Portraits
I batch edited all the portraits in the game with a bit of sharpness, contrast, and saturation. It helps a bit with the more blurry ones. I didn't go too crazy just wanted it to look a little better in handheld mode.

Before

![Portrait_PC_Knight1](https://user-images.githubusercontent.com/90596580/229712944-3ac62c5e-af6c-42af-a3a5-7a11e644b630.png)

After

![Portrait_PC_Knight1](https://user-images.githubusercontent.com/90596580/229712990-6f97346d-a8c8-474d-a1f1-2a427e8897e3.png)

# Puzzle-Cooldown-Mod
On the PsP version there was no cooldowns for spells. If you had the mana and the extra turns you could cast as you liked. The remake added some cooldown timers and while some make sense for low cost high power buffs others are annoying. I made a mod that changes any cooldown that was 1-3 to 0. Crazy buffs that cost 5-9 are still that long. Effects bad guys too.

# How to make your own mods
Dump the romfs from the game. 
Download Asset Studio. 

Open the directroy where you dumped the game and figure out what file has what you want to mod. 

Open the file with UABE, uncompress it somewhere then go to info and export whatever you are modding, probably using the plugins button. I was using ver 2.2 the other one wasn't working for me.

Edit it.

Import back into the archive.

Save it somewhere.

Compress it with UABE, File>compress. The method doesn't matter much.

Make a romfs folder and copy the structure from the dumped game files.

Put your new editied file where the old one used to live. It needs to have the exact name.

There you go.

I inculded a document I made called spelldir. It combines info from the base spell files and the scripts that control them. Easy to edit so feel free to make a new class even using this base info.
