<img src="https://user-images.githubusercontent.com/59484948/132199315-58a34c80-7bd2-4d3e-9d11-75374f621e10.png" alt="TrueBlocks" align="right" height="256px">
<div align="center">
  <h1>TrueBlocks</h1>
  <h4>Uncover the true identity of Minecraft: Dungeons' blocks</h4>
  </div>
<br>  
<br>  
While developing texture packs for Dungeons, I've noticed a lot of blocks that randomly rotate in vanilla, but look awful when used with the higher-resolution textures I was applying. So I set out to disable the rotation for all applicable blocks, since you can do that by editing blocks.json in each level resource pack. Some of the blocks, like obsidian, were simple enough – its filename being <code>obsidian.png</code>. But if you've ever dabbled with Dungeons assets yourself, you know it doesn't end here, because textures oftentimes do not match their filename at all. As I pressed on, I constantly found myself wondering "What block is that internally?" and having a hard time determining it correctly since there are just so many block textures in the game, many of them identical. So finally, after getting tired of it, I quite literally said "Fuck it" to myself and went on to create this mod. Here is some info about it!

## What this mod does:
<ul>
    <li>Makes all block textures look like their latest Bedrock or Education Edition counterpart with the same file name.<br>For example, the most hilarious use of a texture I could find is this (in the <code>frozenfjord</code> resource pack, among others):<br><p align="center" width="100%"><img width="33%" src="https://user-images.githubusercontent.com/59484948/132216551-e39d5490-1a8e-4fbc-ba5e-e30e8173751a.png" alt="TrueBlocks"></p><br>With this mod, the texture looks like an actual diamond block:<br><p align="center" width="100%"><img  width="33%" src="https://user-images.githubusercontent.com/59484948/132218775-841031ac-23ef-417c-bba7-27139931b91d.png" alt="TrueBlocks"></p><br><i>(Sorry for the blurriness, that's just how Finder previews small images.)</i>
    </li><br>
    <li>Textures exclusive to Dungeons that do not exist in Bedrock/Education Edition assets (and some others) get an awesome magenta texture with their filename written over it in black. Powered by Adelle Sans.</li><br>
    <li>Emissives and other PBR textures are disabled entirely, so as to not get in the way. They're easy enough to figure out anyway.</li>
</ul>

### Notes
<ul>
    <li>"Carried" textures (like <code>carried_waterlily.png</code> or <code>leaves_oak_carried.png</code> also get a magenta texture even though they exist in the Bedrock assets, because they're too hard to distinguish from "non-carried" textures otherwise.</li><br>
    <li>Textures that get tinted per-biome in base Minecraft have been manually tinted a plains green so as to not look as jarring.</li><br>
    <li>I've left textures that are purely transparent images in vanilla alone, since they probably don't matter anyways.</li>
</ul>

## What you can do with this mod:
<i>It's recommended to use Universal Unreal Unlocker and take advantage of its freecam feature to fully utilise this mod.</i>
<ul>
    <li>See the file name of any block texture directly in-game, without having to export the level to Java Edition or having to dig through the files</li><br>
    <li>Discover interesting quirks in levels, such as this rotated chiselled quartz block (a Bedrock exclusive block):<br><p align="center" width="100%"><img width="33%" src="https://user-images.githubusercontent.com/59484948/132233097-88d2e6c2-c0c4-4861-bf86-de307938a4d8.png" alt="TrueBlocks"></p><br>or writings in normally hidden parts of levels like this one:<br><p align="center" width="100%"><img width="33%" src="https://user-images.githubusercontent.com/59484948/132233030-2b249e73-6aa3-4035-8fec-9ffeb87c02dc.png" alt="TrueBlocks"></p><br></li><br>
    <li>Determine whether an object is a block or not (non-vanilla non-magenta textures = prefab, mob, effect or something else)</li><br>
    <li>Marvel at Mojang's creativity:<br><p align="center" width="100%"><img width="33%" src="https://user-images.githubusercontent.com/59484948/132235053-b0b025ac-48cb-4ba5-9beb-17b57510dc00.png" alt="TrueBlocks"></p><br></li><br>
    <li>Probably some more awesome stuff that I can't think of right now</li>
</ul>
<br>
<hr>
<br>
That's all for now! I hope you find this mod useful in your texture-making adventures!
