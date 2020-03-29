# Pai

It's an opamp pi clone. 

![Board Image](/Docs/images/img_front.JPG)

Rev 02 has been released to correct Rev 01 bugs, and has been built and verified.

#### Missing from BOM
* Designed to fit 4S125B enclosure from [Mammoth Electronics, Predrill option VY41, Jack location V Side (recommend orange powder coat) | https://www.mammothelectronics.com/products/4s125b-enclosure?variant=41945282515].
* BOM calls out Mammoth [3PDT switch solder assist board|https://www.mammothelectronics.com/products/large-3pdt-wiring-board?variant=25345638407], but omits switch. Most PCB-mount 3PDT latching footswitches should fit; recommend [FS3PDT-LP from Mammoth|https://www.mammothelectronics.com/products/4sfs3pdt-lp-3pdt-footswitch-with-pc-mount-terminals?variant=25354110023].

#### Possible future tweaks: 
* Swapping out diodes to tweak clipping. 
* Tweaking filter cutoff of clipping stage. 
* Adding tone bypass option.

### Known Issues
|Issue|Workaround|Fix|
| --- | ---- | ---- |
| Input and Output Bypass switches are drawn wrong (common pole facing wrong side) but work correctly (i.e. as intended, not as drawn) | N/A | Update symbol |

## To-Do
* Create enclosure stencil (laser cutter stencil requires decent absolute registration, which Glowforge can't do yet).
