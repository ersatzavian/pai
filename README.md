# Pai

It's an opamp pi clone.

![Board Image](/Docs/images/pai_img_3d.png)

With the bug fixes below, I've played mine and it sounds good. Haven't released a version with the bugs fixed yet, might do that over Christmas break if I've got a little time. 

#### Possible future tweaks: 
* Swapping out diodes to tweak clipping. 
* Tweaking filter cutoff of clipping stage. 
* Adding tone bypass option.

### Known Issues
|Issue| Workaround | Fixed?|
| --- | ---- | ---- |
|Knobs Reversed|Swap back as documented below.| |
|U7 stage all wrong|Swap back as documented below.| |
|Add reverse voltage protection on battery and DC Jack.|N/A| |
|Tone stage cap values incorrect (C8, C11)|C8 > 100 nF, C11 > 120 nF| |

## To-Do
* Correct known Rev01 Issues (release Rev02, or don't).
* Create enclosure stencil (laser cutter stencil requires decent absolute registration, which Glowforge can't do yet).

## Reworks for Rev 01
* U7 stage is just hella wrong. 
![U7 Issue](/Docs/reworks/Rev01/u7_issue.jpg)
![U7 Rework](/Docs/reworks/Rev01/U7_rework.jpg)
* All knobs are counter-clockwise-to-increase (backwards). Fixable, but maybe not worth it if it's already assembled.
![Fix Sustain Knob](/Docs/reworks/Rev01/sus_knob_flip.PNG)
![Fix Tone Knob](/Docs/reworks/Rev01/tone_knob_flip.PNG)
![Fix Volume Knob](/Docs/reworks/Rev01/vol_knob_flip.PNG)
