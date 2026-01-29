# TeensyLooper
An audio looper with reverse capabilities and low latency, reverb and based on the Teensy (4 and 4.1) platform.

This project is born out of the "need" for a simple audio reverse tool for my live setup. It will be connected to the AUX1 send/return bus on my console but the main use will be to record and reverse spoken words from old vinyl records. A unit that samples a few seconds of audio (mono) and reverses it playing it in loop mode.

The base is a Teensy 4.0 and it has a 4 second sampling time @ 44.1khz sampling rate 16 bit resolution.
You can use a Teensy 4.1 that will increase the sampling time to 8 seconds.

First interaction:

one input
one output
Rec button
Kill button
Loop or single shot switch
Reverse or forward switch

Code for 4 seconds
To Do:
- PCB
- Front Panel
- test reverb FX Code
- Test add ons (second interaction)
  
Second interaction:

Added GATE/TRIGGER control for record and kill function
Added Reverb FX (via code and Open Source Library)
Added Reverb Size potentiometer
Added Reverb WET/DRY potentiometer
