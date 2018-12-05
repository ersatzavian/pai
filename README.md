# Pai

It's an opamp pi clone. 

![Board Image](/Docs/images/pai_img_3d.png)

With the bug fixes below, I've played mine and it sounds good. Haven't released a version with the bugs fixed yet, might do that over Christmas break if I've got a little time. 

#### Missing from BOM
* Designed to fit 4S125B enclosure from [Mammoth Electronics, Predrill option VY41, Jack location V Side (recommend orange powder coat) | https://www.mammothelectronics.com/products/4s125b-enclosure?variant=41945282515].
* BOM calls out Mammoth [3PDT switch solder assist board|https://www.mammothelectronics.com/products/large-3pdt-wiring-board?variant=25345638407], but omits switch. Most PCB-mount 3PDT latching footswitches should fit; recommend [FS3PDT-LP from Mammoth|https://www.mammothelectronics.com/products/4sfs3pdt-lp-3pdt-footswitch-with-pc-mount-terminals?variant=25354110023].

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
