As of 1.19, removing things like recipes and advancements is easier than ever, due to the datapack "filter" feature that was added in that version. Filters are applied to the pack.mcmeta rather than internal files; you'll notice that this pack doesn't even have anything in it other than that file.

Open this pack's pack.mcmeta to see the format for adding filters. I've gone ahead and removed the same 4 things that I removed in the video (two recipes and their corresponding unlock advancements) - HOWEVER, because filters erase recipes much more cleanly than simply overwriting the file, deleting the advancements isn't even really necessary anymore.

Filters can erase more than just recipes and advancements - any file in any datapack (including the vanilla datapack) can be removed in this way, and they even have support for removing large numbers of files at once with a single filter. For more information on this, the best place to look is actually the changelog from the snapshot where filters were added!

https://minecraft.wiki/w/Java_Edition_22w11a