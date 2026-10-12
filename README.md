# My Dumb-Ass ROM hacks

This repo contains a variety of poor ROMhack decisions I've made thanks to the power of a cold, unfeeling machine that's willing to enable my stupid delusions.

## Primal Rage: Arcade Edition on Saturn v.07

### Latest release file:

```
Saturn_Primal_Rage/PrimalRage_4MB_FullAnim_v0.7.zip
```

Inside you want `Primal Rage (USA) (Track 01) - 4MB Cart Full Animation.ips`

Patch this file:

|File|SHA256|MD5|
|----|----|----|
|Primal Rage (USA) (Track 01).bin|358cfed0acda21e1b181aae31d25112cd62befcf70c1e259b482ac93810bfcdc|de243475bec0ce7f54a8ce56a63ed29c|

### What it does:

Basically imagine a world in which the 4MB RAM cart came to America and Probe Entertainment was flush with cash and decided to shoot for the moon with their Saturn port of the game.

The Saturn verison already has "full" animation frames per fighter, but it only uses them in mirror matches.

This patch detects the RAM cart and then loads the full animations for **both fighters** instead.

Has some bugs, works on real hardware, doubles the loading times. I shouldn't be allowed to make decisions in life.

## Puchi Carat: Arcade Translation Edition v1.0

### Latest release file:

```
Arcade_Puchi_Carat/Puchi Carat Translation Kit.html
```

The original dialogue script for Puchi Carat was basically shredded for its English language release.

This translation tool:

- Restores the dialogue boxes and prepairs them for translation
- Allows you to preview the translated text so you can account for placement
- A sample translation is provided
- Provides an editable box for every line of dialogue
- Includes a "Word Wrap" feature and verification that all of the words fit
- Has symbols for text coloring
- Has symbols for the game's few emojis
- Allows characters to be renamed (mostly for the dialogue)
- Allows you to unlock Patrako permanently
- Also lets you save a MiSTer .mra for the "PuchiCarat" fork of spacestate1's Taito F3 MiSTer core. 

Some incidental text hasn't been translated. It would require a bit more work, so I may tackle it later.

**The tool does not contain any game data**. The game has to be uploaded into the tool first.

## Lords of Lunar (Hidden Mini-Game in Lunar: Silver Star Story Complete on PSX in the "Making of" Disc)

### Latest release file:

```
PSX_Lords_of_Lunar/LordsOfLunar_PaddlePatcher.html
```

This tool:

- Adds Namco NeGcon/Volume Controller support
- Adds PlayStation Mouse support
- Lets you shorten unlock code to just pressing start
- Allows you to export a 2MB image of __just__ the game
- Has an option for mouse speed (I use 3X) and mouse menu movement

Effectively, Lords of Lunar is the neatest 9-player paddle game inspired by Atari's Warlords that I've never seen playable since.

I was a bit annoyed that it didn't have "proper" paddle controls for the PlayStation Mouse or NeGcon when the game itself obviously detected these controller types.
