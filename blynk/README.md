## Blynk Instructions for Plantidote

This code is only useful if you want the vase to work with Blynk.

- Use platform.io to import the blynk folder
- Create myconfig.h file based on myconfig.sample.h
- Compile/upload it to the board
- Create a dashboard on Blynk with the following datastreams:
  - V0: Gauge for the battery voltage
  - V1: Gauge for the battery percentage
  - V2: Graph for the moisture level
  - V3: Gauge for the water level
  - V4: Slider for the moisture threshold
  - V5: Switch for the pump
  - V6: Pump history
  - V7: Pump volume
  - V8: Countdown before sleep

  ![](../images/presentation/blynk-widget.png)
