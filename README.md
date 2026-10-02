# Java Animated Totem Pack Maker

GIF in, Minecraft Java animated Totem of Undying resource pack (.zip) out. Java twin of PPYGaming/Animated-totem (Bedrock).

## Plan
- Single-page web app (index.html), runs fully in the browser.
- Decode GIF (gifuct-js), resize to 16/32/64 px square frames, stack vertically into totem_of_undying.png.
- Write totem_of_undying.png.mcmeta with animation.frametime.
- Zip with JSZip: pack.mcmeta, pack.png, assets/minecraft/textures/item/totem_of_undying.png(+.mcmeta).
- Vanilla resource pack only, no OptiFine or mods.

Made by Tamilcrafters Studio.
