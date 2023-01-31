# January 2023

_entry music_

I have been thinking about **emulators**. I wrote one for CHIP-8 in December and it was fun, so I want to make another one for a more involved system. I was thinking about doing just an Intel 8080, but people I asked about where to start recommended I emulate a system with graphics, like a game console. This way I can visually see my progress, which I think will help with motivation.

The people I asked recommended Gameboy or NES, and I started looking at Gameboy emulator resources. I realized the Gameboy Color is pretty similar to it. So similar, in fact, that most of the resources I found applied to both of them. Since GBC has ✨ pretty colors ✨, I decided I would do that.

My friend pointed out I never played any games made for GBC, so I thought about Gameboy Advance. However, it seems much more _advanced_ and I would still want it to support original Gameboy and Gameboy Color games. I figured I would just write a GBC emulator first, then when I'm satisfied with it, I will eventually write a GBA emulator that uses my GBC emulator backend for GBC and DMG support.

Currently my end goal of what system I want to emulate is the Nintendo DS. I spent a lot of time playing on my DS as a kid, but never learned about its internals. I want to make something I can feel proud of, and I think an emulator where I can run the games I grew up with would be a good choice.
