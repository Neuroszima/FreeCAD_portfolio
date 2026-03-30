# About this repo

Mostly amateur-level CAD designs. I have thrown them in for showcase, that I can operate and navigate this environment.
Most of the designs have already been 3D printed, and based on experience gotten from solving problems that were 
encountered, next projects were made with new tools/solutions in mind. I have a few other designs, that I cannot show 
(property of previous company I worked for - models of robots internals).

#### Box for parts

A simple box with a matching lid. 0.1mm tolerance added (in printed version on the Ender-3 this was not enough). It does
not feature parametric design.

Tested and printed on Creality Ender-3 V3 SE. (tolerance needs to be increased for box to be comfortably closed)

#### Screw box holders

Two designs, one with 10 compartments of equal sizes (2 rows of 5 layout), another with 4 smaller compartments and 2
wider ones. First few designs ever made - used simple assembly tool to know what it is used for.

Tested and printed on Creality Ender-3 V3 SE. (both)

#### Ziptie holder

Organizer for zipties. 5 cylindrical compartments - 2 taller ones (143mm height by 17.5mm diam. for longer, 160mm zipties) and 
3 smaller ones (78mm height by 12.5mm diam. for 90mm zipties). 

Tested and printed on Qidi plus 4.

#### Flower pot and vase

As the name says. Used extrusion around axis (for flower pot) to start with, then applied symmetries for inner pot raisers 
(so that water can actually stay in the pot without drowning roots) and prepared a small cutouts as recorations.

For vase, boolean fuse operation + removal of excessive material were performed (using subtractive prisms/boxes).

Tested and printed on Qidi plus 4.

#### Gwent box

Alternative box for paper version of Gwent game. This box is for old, exclusive tarot-size version of the game.
There is new version of the game ("Gwent, Legendary Card Game" edition), but new version has good, factory-made insert, 
so designing it is pointless. For original release however, cardboard boxes were lacking. My design does take into 
account card sleeves, so if you want, you can print this pretty much directly. It has large cutouts for fingers 
for easier deck picking.

3D model does not have an enclosure designed yet. 

Tested and printed on Qidi plus 4.

#### Splendor box

Current project. This is meant to be an alternative 3D-printable box, to hold elements (tokens, playing cards) 
for board game "Splendor". In this repo it exists in two versions. Original version used imported constraints from 
different sketches to realize the build. Has 0.5mm tolerance applied, however the problem with importing constraints 
from other sketches is longer calculation time when design is changed somewhere (it has to check and re-apply 
re-calculated constraints on other sketches and thus other 3D parts and, for example, operations like chamfers). 

The original design was then fixed in the "revised" version using fully parametric design (through the use of 3 varsets) 
and now it is easier to reason about and easier to modify by altering parameters. It also re-calculates faster. 
Revised (parametric) version also has 0.5mm tolerance for all the game components. Both designs take into account 
additional increase of space due to card sleeves. In parametric design, you can alter the multiplier to increase or 
shrink the space left for extra deck space.

The box will feature a lid in future versions, now it is an open design without an enclosure.

Not yet tested.
