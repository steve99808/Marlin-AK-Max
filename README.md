Started out of desperation, since I shorted out the factory board and couldn't get an replacement and there wasn't the budget or knowledge to switch to Klipper for that time. 
So this was a budget rebuild with about 120€ in new parts. Of course it's more if you don't have the required tools

Based on Marlin 2.1.2.4

Requires basic knowledge of electricity, crimping pliers, multimeter, cables, JST-XH 2.54 and PH2.0 connectors <hr>

The parts I went with: <br>
<a href="https://biqu.equipment/de/collections/control-board/products/bigtreetech-skr-mini-e3-v2-0-32-bit-control-board-for-ender-3" target="blank"> Bigtreetech SKR Mini E3V3 </a> <br>
<a href="https://biqu.equipment/de/collections/lcd-screen/products/bigtreetech-mini12864-v2-0-lcd-screen-rgb-backlight-mini-display-supports-marlin-diy-for-skr-3d-printer-part-1" target="blank"> BTT Mini 12846 Display </a>  <br>
<a href="https://de.aliexpress.com/item/1005007804320392.html" target="blank"> Toolhead board since I later to switched it up to BL Touch later </a>  <br>
Bambulab X1C Clone hotend from Aliexpress or Amazon <br>
<a href="https://biqu.equipment/de/collections/module-expansion-board/products/antclabs-bl-touch-v3-1-original-auto-leveling-sensor-premium-3d-kossel-printer-reprap-for-skr-v1-3-3d-printer-parts" target="blank"> BL Touch </a> <br>
If you're using a different adapter plate and leveling probe you might need to change the offset of certain probe in the Configuration.h file <i>(NOZZLE_TO_PROBE_OFFSET Line 1516)</i>.

Decided to switch the entire printhead out a Voron Stealthburner and a Clockwork 2 Extruder. Since it was all on a budget the CW2 is fitted for a Nema17 stepper motor. 
List of the STL files for my build: 

<a href="https://www.printables.com/model/538165-stealthburner-adapter-for-kobra-max-and-vyper-volc?lang=de" target="blank"> Adapter plate for BL Touch</a> <br>
<a href="https://www.printables.com/model/1283225-clockwork-2-nema-17-last-version-stealthburner" target="blank"> Clockwork NEMA17</a> <br>
<a href="https://www.printables.com/model/322091-voron-stealthburner-printhead-for-bambu-x1cx1-hote" target="blank"> Stealthburner for Bambulab Hotend </a> <br>

<hr>

The biggest issue was the display, since the E3V3 board only has one EXP port for connecting the display. So custom rewiring is necessary if you really want to use this certain type of display. I'd reccomend the <a href="https://biqu.equipment/de/collections/lcd-screen/products/tft24v1-1-gd-version" target="blank"> TFT24 </a>  or <a href="https://biqu.equipment/de/collections/lcd-screen/products/btt-tft35-e3-v3-0-display-touch-screen-two-working-modes" target="blank"> TFT35 </a> to spare you some headache.
For wiring up the motherboard please refer to the pinout from Bigtreetech. I personally recrimped all cables since the board is mostly used for Creality 3D printers and their stepper motors are wired different to the ones from Anycubic. So a Multimeter tool is a must for it. 

<hr>
<h4>Edit: Discontinued for now since I switched to Klipper with a different board. </h4>
