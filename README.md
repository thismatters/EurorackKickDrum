# Kick Drum


The circuit here is an implementation the circuit in the [Moritz Klien kick drum video](https://www.youtube.com/watch?v=yz37Yz315eU) with all of the trappings to make it a proper module. The aforementioned video is extremely good and deserves a watch (along with all their other content, top notch). While the [Erica Synths kit](https://www.ericasynths.lv/shop/diy-kits-1/edu-diy-kick-drum/) has 7 knobs I have limited myself to 4 knobs: Decay, Pitch, Distortion, and Tone. The other 3 knobs are be present as screw-turn potentiometers accessible from the front panel for retuning the module.

The KiCAD project here uses the library/footprints [found in my companion repo](https://github.com/thismatters/EurorackKiCAD).


## Width

6hp on a standard 3U rack.

## Inputs

3 Jacks
- Gate
- Accent CV
- Pitch CV

4 Knobs:
- Decay
- Distortion
- Tone
- Pitch

3 Screw Pots (accessible from front):
- Tune Decay
- Tune Depth
- Max Pitch CV

## Outputs

1 Jack for audio output.

## Vendors

There are part numbers in the [BOM](kick-drum.csv) for many of the parts (not for basic passives though) at the following vendors:

* [Mouser](https://www.mouser.com): Needs no introduction. Get your ICs from here (or [digikey](https://www.digikey.com)).
* [Tayda Electronics](https://www.taydaelectronics.com/): Good supplier for passive components; audio jacks, and potentiometers. Their audio jacks are slightly smaller than the thonkiconn from thonk.
* [Love My Switches](https://lovemyswitches.com/): Has [really good knobs](https://lovemyswitches.com/anodized-aluminum-knob-the-lo-fi-1-4-smooth-shaft-12-5mm-od/) to go on those potentiometers!
* [OSHPark](https://oshpark.com/): Fast and (relatively) cheap PCB manufacturer. Prototype run pending.


## Changelog
