One of the [University of Colorado / ATLAS Instute](https://www.colorado.edu/atlas/)'s Spring 20203 Sound Lab class projects includes sampling the lab's Hammond M3 organ.
The M3 lacks a line output jack, so this project adds this missing feature.

Based on [LineOut from a Spinet](http://www.dairiki.org/HammondWiki/LineOutFromASpinet) which is refenced by a number of Hammond M3 techinical forums.
This design add a switch to select the M3 internal speaker or the line out jack. And, it includes 1/4" and 1/8" headphone jacks.
The M3's speaker is integral to the amplifier, so this circuit includes a 10 ohm / 10 watt resistor to provide an equivalent load to the amp with the switch is in the Line Out position.

Caution!
The Sound Lab's Hammond M3 has a speaker with a "field coil." This is an electromagnet; more recent models use a permanent magnet. The field coil runs on about 100 volts DC. Ouch! Do not touch.
Identify the correct 2 wires for the speaker voice coil, which should be black and green.
Cut the green wire and connect the side running to the speaker to the speaker out connection of this circuit.
Connect the other side of the green wire to amp in.
Splice into the black ground wire and connect it to the ground connector.

[Hammond Schematic and wiring diagrams](http://captain-foldback.com/Hammond_sub/hammond_schematics.htm)

* [M-3 Schematic](http://captain-foldback.com/Hammond_sub/schematics/M3_early.zip) - early version with field coil speaker, serial # 48000 to 90485)
* [M-3 wiring diagram](http://captain-foldback.com/Hammond_sub/schematics/M3_early.zip) - for above version

Design files:
* The schematic ([hammond_headphone_lineout.fzz](./hammond_headphone_lineout.fzz)) was designed with [Fritzing](https://fritzing.org/).
* The panel and box ([Hammond_LineOut_Headphone_Panel.f3d](./Hammond_LineOut_Headphone_Panel.f3d)) were designed with [Fusion 360](https://www.autodesk.com/products/fusion-360). 
  * (Note that [Fusion 360 and other Autodesk products are free to use for CU Boulder faculty and students](https://oit.colorado.edu/software-hardware/software-catalog/autocad).)

![panel](./Hammond_LineOut_Headphone_Panel_photo.jpg)
![inside](./Hammond_LineOut_Headphone_Panel_insde.jpg)
![schematic](./hammond_headphone_lineout_schem.jpg)
![wiring block](./Hammond_M3_LineOut_wiring_block.jpg)
[wiring block- Google Drawing](https://docs.google.com/drawings/d/1cAGUUYIvQpBTmiA-liVRN2AA-Yzoq7PjT-2qa91Djhs/edit?usp=sharing)

