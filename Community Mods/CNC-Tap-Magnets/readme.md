Voron Tap r8 style magnet mounts for Chaoticlab's CNC TAP

Initial release by Telani#9207

Tip jar at https://www.patreon.com/TidyPrints

This is a remix of the most recent Tap R8 release with the 2.4r2 hot end rear mount parts. The goal is to get additional stability on the CNC TAP by adding Voron Tap r8 styled/angled magnets to the assembly. I didn't end up doing as much benchmarking of this vs tap r8 as I had intended, but I'm getting 5500 y axis automatic tunes when before magnets I had issues breaking 3200 on y axis, both using the fixed higher preload rail. I'm releasing this early without much testing in the hopes that others will have ideas for ways to do this better.

BOM:

2x M3x6 BHCS (button head) to replace the M3x5 SHCS (cap head) at the belt mounts

2x M3 washers

2x M3x10 BHCS

2x M3x5x4 Heat Set Inserts (Voron Inserts)

2x (or 4x) 6mm x 3mm neodymium magnets, I am using 4x N52

2x (or 0x) M3x6 FHCS

STLs:

1x of left belt mount

1x of right belt mount

1x of left magnet pod

1x of right magnet pod

1x of your hot end's rear mount from the hot ends folder


Check the voron tap manual here for magnet pod assembly and general tips on alignment: https://github.com/VoronDesign/Voron-Tap/blob/main/Manual/Assembly_Manual_Tap.pdf

Belt mounts are best installed with a/b drive belt tension at minimum, with the slack on the left of the print head. AKA, install the right belt mount first. I find it easier to attach the CNC TAP to the rail only after attaching the belt mounts.

Overtightening any of the fastners that secure plastic to metal can cause part warping, be careful not to over tighten things. 

Install magnet pods at the farthest back spot before installing the hot end, after assembly release then tighten the magnets while gently pulling the hot end downwards. Make sure the switch audibly clicks when the hot end returns to it's default position. Improperly installed magnets can be worse than none.
