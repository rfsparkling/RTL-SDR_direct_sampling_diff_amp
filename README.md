![layout preview](https://github.com/rfsparkling/MAX9709_Amplifier_PCB/blob/master/MAX9709_screenshot.png)

This is a breakout board for stock RTL-SDR dongle, allowing the until known best direct sampling method for HF reception using a differential amplifer as BALUN. Right now filtering DC...14 MHz band but possible to work on 14...28 MHz band too after adding a Band Pass Filter BPF.

My design utilizes an LNA too, which adds about 20 dB of gain on HF band. Also a PI attenuator added right after to avoid saturation in the diff amp. The LNA main reason is to create good noise figure for the RX chain.
