# CPX MakeCode Projects
This repository hosts my projects made in Microsoft MakeCode for the Adafruit Circuit Playground Express (CPX).

## Where can I get a CPX?
You can find it on Amazon, that's where I got it. You can also find it on [Adafruit's website.](https://adafruit.com/product/3333)

## What do these projects do?
**Alarm** - An alarm that reacts to shock and/or sound. When it's showing the magenta and cyan lights, pressing A or B toggles the shock and sound sensors respectively. Slide the switch to the right to arm the device, or left to disarm. Press both buttons at once to toggle silent mode, the device is silenced if you see 4 yellow lights.

**Lights** - Hold the A button or slide the switch to the right to show a rainbow pattern. The lights turn white if you hold the B button.

**MonitorTV** - A program that controls Samsung Smart TVs and Monitors using keyboard and gamepad commands. If the switch is to the left, press A to lower the volume and B to raise it. Pressing both buttons mutes or unmutes the speakers. If the switch is to the right, you can change sources by pressing both buttons then using A and B to move left or right. The new source is automatically selected after 5 seconds.

**PCMedia** - A program that controls media playback on a PC using keyboard input. If the switch is to the left, press A and B for previous/next track or both to play/pause. If the switch is to the right, use A and B for volume up/down and press both to mute/unmute.

**SimpleLight** - A flashlight script. Press the A button to pulse a white light, or use the switch to turn it on or off. Press the B button to toggle between white and red.

**SpeedControl** - Allows you to modify HTML video speed using a [Chrome](https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk) extension. Press the A button to slow down and the B button to speed up. Slide the switch to the right or hold both buttons to start speed ramping, release the buttons or slide the switch back to return to normal speed. During speed ramping, a blue light will circle around the device.

## Can I install these or edit them?
To install these on your CPX board, simply put the board into bootloader mode and drag the UF2 file for the program you want to the CPLAYBOOT drive. If you want to edit the projects, go to the [CPX MakeCode editor](https://makecode.adafruit.com) and drag the UF2 files into your browser.
