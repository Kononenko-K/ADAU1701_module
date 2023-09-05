# ADAU1701_module
SigmaDSP audio module with SigmaLink-USBi compatible programmer and USB digital isolator included
<br/>
<p align="center">
    <img width="600" src="https://github.com/Kononenko-K/ADAU1701_module/blob/main/pics/board.jpg">
</p>

## Overview
This is a part of my yet unfinished project, that's why the board has such a peculiar shape. But it can be used as a standalone audio processing device with external PC control.
## [Hardware](Hardware)
The board features AUAD1701 SigmaDSP chip, CY7C68013A based USBi programmer and ADUM4160 USB isolator that prevents ground loops when the PC USB port and audio source share the same ground. It also has an active second order low pass reconstruction filter on the DAC outputs. The board can be programmed with SigmaStudio. There are [KiCad project](/Hardware), [Gerber files](/Hardware/gbr) and [PDF](/Hardware/project.pdf) avaliable.

