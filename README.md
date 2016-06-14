![layout preview](https://github.com/rfsparkling/RTL-SDR_direct_sampling_diff_amp/blob/master/3.JPG)

This is a breakout board for stock RTL-SDR dongle, allowing the until known best direct sampling method for HF reception using a differential amplifer as BALUN. Right now filtering DC...14 MHz band but possible to work on 14...28 MHz band too after adding a Band Pass Filter BPF.

My design utilizes an LNA too, which adds about 20 dB of gain on HF band. Also a PI attenuator added right after to avoid saturation in the diff amp. The LNA main reason is to create good noise figure for the RX chain.


Thanks to Martin - G8JNJ for publishing his idea about a possible diff amp solution for direct sampling! Also for taking his time and working with me on that also testing and reviewing the first prototype.
http://www.g8jnj.net/softwaredefinedradio.htm