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
