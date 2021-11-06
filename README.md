# Experimental [V-core 1.3](https://www.ratrig.com/rat-rig-v-core-pro-upgrade-kit-from-v-core-pro-1-x-to-1-3.html) - [Recore A5](https://www.iagent.no/product/recore/) config
## WIP Klipper &amp; Fluidd config files for Recore A5 board on V-Core 1.3

### Printing quite well already, no real tuning of pretty much anything yet (retract/acceleration/flow/pressure, etc).

* [Easy-mod 2.0.0](https://cad.onshape.com/documents/941d3ce9564d1a9f1528bea7/w/af0d99b566038cc9eaf60dc4/e/4c0427b7874846e40129df20) with 400mm MGN12

* [EVA 2.x](https://main.eva-3d.page/) carriage
	* [Slice 50W](https://www.sliceengineering.com/products/50w-heater-cartridge) heater
	* E3D copper block & nozzle (thermistor, PT100 in comment)
	* BMG with Dragon HF

[Firmware retraction](https://www.klipper3d.org/Config_Reference.html#firmware_retraction) and [Arc](https://www.klipper3d.org/Config_Reference.html#gcode_arcs) enabled.

* Bed
	* Triple Z
	* Keenovo 230V heater
	* BLtouch
