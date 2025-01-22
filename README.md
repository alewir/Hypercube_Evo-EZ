# Hypercube_Evo-EZ
Custom 3d printer

I'm building a 3d printer that allows quite convinient access too all components and some spare space that can be further utilized in prototyping.
* the box is regular 60x60x60
* the printing space is 32x32x32
* electronics and hotend runs 12V
* bed is made from 2 separate 24V aluminium plates to heat up quickly
* the enclosure is acrylic
* it uses 3 point auto leveling (z_tilt)
* it has a klicky probe and automated Z-offset calibration
* it uses BTT Eddy v1 Coil for rapid platform scan (WIP: due to https://klipper.discourse.group/t/introduce-pin-probe-for-enhanced-multi-probe-compatibility-6663/19747)
* controlled by Klipper
* printhead is controlled over CAN
* uses only very silent fans
* uses sthelthchop to get quiet a motors work
* X/Y endstops are optical
* Z uses a sexbolt to auto-calibrate the klicky probe offset
* currently has a custom filament buffer [allowing pulling filament with a consstant force](https://www.youtube.com/shorts/5Dwlf__6fEI) 

Here is some preview: [here on YT](https://www.youtube.com/shorts/g4zk68t5uF8)
