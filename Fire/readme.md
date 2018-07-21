# Fire (FR-27)

**szgw-XL-Fire**  **[PLAYABLE]**  **[WIP]**  
(Requires [ShenzhenMod](https://github.com/gtw123/ShenzhenMod))

* Basic gameplay: simplified spawning (4th floor only)
* Fully functional interface: start button & game over; score & lives display; audio
* TODO: incremental difficulty: score-based spawning on both 3rd & 4th floor.
* TODO: smoke animation


Unfortunately, framerate is slow due to complexity.  
For smoother gameplay, try prototype 2 instead.


## Prototypes

Initial (partial) implementations to develop and test various features and functionality in a modular fashion.

**szgw-Fire-proto1-simulated**  
Billowing smoke animation.  
Simulated gameplay and audio to get a first impression of how things might look/feel.

**szgw-Fire-proto2-basic-gameplay**  **[PLAYABLE]**  
Basic gameplay, with simplified spawning (4th floor only).  
No scorekeeping.

**szgw-Fire-proto3-sound-scorekeeping**  
Start button. Scorekeeping, lives, game over. Audio.  
Uses simulated signals for animate/bounce/fall events.

**szgw-Fire-proto4-7seg-decoder**  
3-digit 7-seg decoder for score display.

**szgw-Fire-proto5-score-based-spawn**  
Score-based spawning for both 3rd & 4th floor.
