# Experimental [V-core 1.3](https://www.ratrig.com/rat-rig-v-core-pro-upgrade-kit-from-v-core-pro-1-x-to-1-3.html) - [Recore A5](https://www.iagent.no/product/recore/) config
## WIP Klipper &amp; Fluidd config files for Recore A5 board on V-Core 1.3

* Physical endstops (X on frame, Y on carriage/idler)
* Bed
	* Triple Z
	* Keenovo 230V heater
	* BLtouch

* [EVA 2.x](https://main.eva-3d.page/) carriage
	* [Slice 50W](https://www.sliceengineering.com/products/50w-heater-cartridge) heater
	* E3D copper block & nozzle (thermistor, PT100 in comment)
	* BMG with V6

[Firmware retraction](https://www.klipper3d.org/Config_Reference.html#firmware_retraction) and [Arc](https://www.klipper3d.org/Config_Reference.html#gcode_arcs) enabled.
Printing nicely, but no real tuning of yet (retract/acceleration/flow/pressure, etc).
