# Block Gate

> A fun Minecraft redstone challenge.
A fun Minecraft redstone challenge.
As this is sorta a forensics challenge it may be a good idea to backup the world folder so you don't have to download it over and over (however, there are MANY ways to solve this challenge and you do not necessarily need to make a backup).
(Link to the world data)
Happy hacking!
  Abjuri5t (John F.)
p.s. Look left immeditaly after spawning-in and see what the water does :-)

So in this challenge, we're given a zip file of a Minecraft save. The creator stated that there are **many** different solutions, even some that don't require people to have Minecraft.
This solution involves having Minecraft.

So first up, upon loading the game, we see that a giant waterfall is coming down and is about to destroy the redstone circuit. Clearly, the goal is to save the circuit through any means necessary.

So that's why I decided that sponge is the answer.
![Sponge Saves The Day](/images/Sponge.png)

This did require saving a backup of the world.
What this solution did was basically use the Minecraft command `/fill x1 y1 z1 x2 y2 z2 minecraft:sponge` to replace all blocks from corner 1 to corner 2 with sponges. Although there was a minor spillage, it did not affect the circuits (thankfully).

Now comes staring at the flashing lamps and figuring out what in the world is going on.

![Lamps](/images/MCLamps.png)

Here are all the blocks with everything lit up. Seeing this reminded me of 7 Segment Display, a very common type of display on clocks. Initially, seeing the flag itself was hard, but after being reassured that the challenge is in WPI{} flag format, it became clear where the WPI actually was.

![Final Order](/images/7SegOrder.png)

After this revelation, the order of the flashing became clear. From there we simply extract the flag.

`WPI{02301}`
