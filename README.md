# Elegoo Neptune 3 Pro profiles for use with PrusaSlicer

I'm sharing my profile for using my stock Elegoo Neptune 3 Pro with PrusaSlicer.

The profile was tuned with the following priorities:

1. Use the stock values from the official firmware
2. Keep the same printing quality as the Elegoo Cura profile
3. Keep the same printing speed as a Prusa i3 MK3

To tune this profile I examined many of my prints and did a extruder flow test and determined that 12 mm³/s was the highest value it could achieve without underextrusion for my PLA at 210ºC.

It should print a 0.2mm layer height benchy with 20% rectilinear infill and 2 walls in about one hour.

It also aims to have a very nice starting/ending Gcode.

# How to install

0. Download the lastest [release](https://github.com/RuiNelson/Neptune3ProProfileForPrusaSlicer/releases) from GitHub.
1. Open PrusaSlicer
2. On the menu, click **Help** > **Show Configuration Folder**
3. Open the `vendor` subfolder
4. Copy/Replace your `Elegoo.ini` and `Elegoo` folder with my version
5. If you do configuration updates from Prusa, you might need to replace again the files/folders. You can disable configuration updates in PrusaSlicer if you want.

Optional: here on GitHub, click the **Watch** button then **Custom**  then **Releases** to be notified of configuration updates.
