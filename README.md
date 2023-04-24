# CPX MakeCode Projects
This repository hosts my projects made in Microsoft MakeCode for the Adafruit Circuit Playground Express (CPX).

## Where can I get a CPX?
You can find it on Amazon, that's where I got it. You can also find it on [Adafruit's website.](https://adafruit.com/product/3333)

## What do these projects do?
**Alarm** - An alarm that reacts to shock and/or sound. When it's showing the magenta and cyan lights, pressing A or B toggles the shock and sound sensors respectively. Press both buttons at once to toggle silent mode, yellow means silenced and cyan means not silenced.

**Lights** - Hold the A button or slide the switch to the right to show a rainbow pattern. The lights turn white if you hold the B button.

**MonitorTV** - A program that controls Samsung Smart TVs and Monitors using keyboard and gamepad commands. If the switch is to the left, press A to lower the volume and B to raise it. Pressing both buttons mutes or unmutes the speakers. If the switch is to the right, you can change sources by pressing both buttons then using A and B to move left or right. The new source is automatically selected after 5 seconds.

**PCMedia** - A program that controls media playback on a PC using keyboard input. If the switch is to the left, press A and B for previous/next track or both to play/pause. If the switch is to the right, use A and B for volume up/down and press both to mute/unmute.

## Can I install these or edit them?
To install these on your CPX board, simply put the board into bootloader mode and drag the UF2 file for the program you want to the CPLAYBOOT drive. If you want to edit the projects, go to the [CPX MakeCode editor](https://makecode.adafruit.com) and drag the UF2 files into your browser.