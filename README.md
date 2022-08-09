# xslingerHD
Simple SpaceWar!-style action game for the Apple IIgs that uses the extended text modes of the vidHD HDMI video card.



    
Hello...
    
This game uses the vidHD card's extended text modes as if they were a new 
grahics mode for the Apple IIgs.  These modes were in no way intended
for this purpose for several reasons.
However, it is interesting seeing the full 16:9 screen populated with
text, made of tiny 1080p-sized pixels, controlled by an Apple II! 

There are significant performance drawbacks to using these text modes
for an action game, which is why the "sprites" are quite small, and the
total number of moving objects must be kept to a minimum or the game
will begin to slow down noticeably. 
It was still a cool experiment and I hope it's fun to play anyway!
 
IMPORTANT: This beta/demo is not GS/OS friendly, please don't launch from
GS/OS or expect it to respect what might already be in RAM!

IMPORTANT: Do not enter the IIgs Control Panel while the game is launched
(because the extended text modes are active at all times in XSlinger). 
If you do, you'll need a RESET to get back to BYE. You can pause a game
in progress with ESC (and then Apple+Q to quit to the main menu).

System Requirements:
  
    - Apple IIgs with 2 MB of RAM
    - vidHD card (fw 1.15) in any supported slot for
      your ROM (Slot 1-6 for ROM 3, Slot 3 for ROM 01)
      Set to Your Card if not in Slot 3
    
Recommended:

    - Stereo Card (panning sounds, funky title jam)
    - large-sized HDMI monitor (tiny sprites, remember?)
    - SNES MAX - it's a two player game, and it *really*
      needs two quality controllers for the best gameplay 
    - Zip GSX or TranswarpGS (does not make a big difference though)
      (Note, the vidHD text modes do not appear to be AppleSqueezer
      compatible, probably due to DMA compatibility)
  
The game implements several little "hacks" to make it possible - so it 
should be considered to be somewhat experimental:
 
vidHD text only supports a single foreground and background color,
like the Apple IIgs. So in order to create an illusion of 3 colors,
the player ships are drawn on alternate frames. This mostly works,
but you will see flickering- especially in areas with a large # of
characters or when too many things are being drawn.
  
The vidHD doesn't yet support changing resolution from code, so the 
game tries to use the keyboard buffer to press the resolution keys
for you. This works most of the time, but may sometimes not, 
especially if you are using the keyboard to navigate the menus.
This shouldn't break anything, you'll just see the wrong sized text.
Just enter the View Controls menu or start and quit a game (ESC, Apple+Q)
to reset it.
  
Also, I've seen a few cases where the text modes are unstable
and/or do not engage properly on some hardware combinations.  If 
you encounter this, try another IIgs (or test without a TWGS if
one is installed).  I'm mentioning this because some people have never
tried to engage the text modes on their machine, so this could be
their first experience with it. If you have a problem, try just 
enabling the text modes from BASIC.SYSTEM and seeing if you can view
the different resolutions, CATALOG a disk, etc. 
  
Thanks for trying my little game...
  

<img width="500" alt="image" src="https://user-images.githubusercontent.com/40877410/183492444-4010a592-c4b4-4dc9-bb47-a3b6e1664124.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/40877410/183493986-da25737a-44e9-4426-8ca1-6b99d4f39857.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/40877410/183494056-cb6e56d7-6ff8-489a-b841-8f04c6ae6212.png">





