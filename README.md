# Experimental [V-core 1.3](https://www.ratrig.com/rat-rig-v-core-pro-upgrade-kit-from-v-core-pro-1-x-to-1-3.html) - [Recore A5](https://www.iagent.no/product/recore/) config
## WIP Klipper &amp; Mainsail config files for Recore A5 board on V-Core 1.3

### Printing quite well already, no real tuning of pretty much anything yet (retract/acceleration/flow/pressure, etc).
Using some of RatRig's [RatOS](https://github.com/Rat-OS/ratos-configuration) defaults.

* @Top_Gun_DE Modded [Easy-mod 2.0.0](https://cad.onshape.com/documents/5ed9d8823cafc0516f5c04af/w/6404b4e920175b6ba3c9f231/e/3e2569dff03c66c20f8031e6) with 400mm MGN12

* [EVA 2.4.2](https://main.eva-3d.page/) carriage
	* LDO 0.9 pancake stepper
	* BMG with [Dragon HF](https://www.phaetus.com/dragon-hotend-hf/)
	* [Slice 50W](https://www.sliceengineering.com/products/50w-heater-cartridge) heater

[Firmware retraction](https://www.klipper3d.org/Config_Reference.html#firmware_retraction) and [Arc](https://www.klipper3d.org/Config_Reference.html#gcode_arcs) enabled.

* Cast tooling plate bed
	* Triple Z
	* Keenovo 230V heater
	* BLtouch
