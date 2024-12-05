# Fire_Switch
USe Rpi with MLX90640 to guard  the e-bikes while charging  (both batteries and charging devices)
The MLX90640 will view loading-bay, and determine max temperature
If the amx temp exeeds threshold --> A smart plug (tuya) will be switched off, stopping all chargng processes.
In this case hopefully prevent a fire.

HW
- Rpi zero 2W
- MLX90640 wide angle
- 3d printed case + flex joint to be able to move camera.

SW
- Rpi + raspbian
- libs based on URL:


Installation / preparation:

Clean Raspian install + update/upgrade



