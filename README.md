# Mara's Tamagotchi Tools!

This repository contains all my browser-based tools for patching Tamagotchis! Everything runs client-side, requires NO downloads, install...
nothing! All that's required is your brain and also access to a computer. Maybe a phone? I haven't tested mobile capabilities. LMK if you do!

First and foremost, there are **no roms** in this repository. You are required to source your own, legal mods. I take NO responsibility if things break.
Use your brain, if you're confused, research!

## Current Things

### tamasmart_patch_creator.html
This tool is for **creators** whos computer either cannot handle Smarty Pants OR they just need something quick and light weight to change a sprite,
a translation, or an item. This tool is **not** a replacement for [Smarty Pants](https://github.com/zenzoa/smartypants), even if it does a lot! Animations are not supported and there
can be some finnicky things. If something breaks and you're confused, *use [Smarty Pants!](https://github.com/zenzoa/smartypants)* it rocks. If you're doing heavy edits, just... use 
Smarty Pants.

### tamasmart_patch_diff.html
This tool is for **creators** who have utilized Smarty Pants to create a custom Tamagotchi Smart bin! You can use this tool to compare your 
original bin file (which you SHOULD have, if you used SP) and the one you exported from Smarty Pants to create a patch. A patch is 
something you can use to share your Smart mod, since. The patch is downloaded in a .zip file, which *remains* a .zip file to utilize 
"tamasmart_patch_apply.html" to combine the OG bin file with the patch!

This tool enables creators to share their creations easily! Without having to worry about being sued! Yay! 

## tamasmart_patch_apply.html
This tool is for **consumers**... or people who just have a .zip file created from one of my tools that they want to apply. This requires knowledge
of the same bin used (ie, if the creator used Melody Friends as a base, you must provide a Melody Friends bin!). If you don't it'll just be... 
completely fucked. It's as simple as selecting the OG bin, selecting the patch and then clicking apply. This assumes everything is going to 
work. There's no checks or validation. 

## meets_translation_patcher.html
This tool is for anyone who's comfortable flashing their Meets and wish that it was in English! It currently only works for the Sanrio Meets and
I don't have JSON's added. I might in a later update, right now, no. The tool has been extensively tested by me, and it's virtually impossible
to brick your meets using it. This simply does a one to one replacement of bytes and does all the fancy shmancy encoding for you.

Still lost? It's like erasing a word on a piece of paper and just rewriting it. It's not possible to enter words that are longer than the byte,
and images are NOT currently something that is supported. That's on the road map. You upload your OG bin, apply a translations.json and then you can make
any edits to anything you want! 

