# InsectWingbeat
This repo documents my initial attempts to record insect wingbeat waveforms using an optica sensor and a Raspberry Pi.

In the late 80s and early 90s I did a bit of work on automated monitoring and identification of flying insects using waveforms collected by very simple none-imaging optical sensors. Hardware and software has certainly changed a lot since then. My contribution to the field was to suggest characterizing insect wingbeat waveforms using harmonic content in addition to the wingbeat frequency (=fundamental frequency).

Just for fun, I decided to hook one of my old sensors to a Raspberry Pi via a USB sound adaptor to see what kind of signals I could capture with minimum effort. Here's my setup:

## Hardware

The sensor is just a miniature solar cell connected to a small transformer which removes the DC component of the waveform. Output from the sensor was connected to a Raspberry Pi 3+ single board computer using a CableCreation USB sound adaptor.

## Software

I installed Audacity VERSION on Raspbian VERSION and was pleasantly surprised that it ran very well. I operated the Raspberry Pi remotely using VNC.

## Experiment

* I taped the sensor to the end of a 6 foot wooden pole and placed it in the direct sun just outside the balcony of my apartment. The sensor was connected to the USB sound adaptor using a 10 foot cable with appropriate connectors.
* I used Audacity to record four one-minute mono WAV files at a sample rate of 44100 Hz.

## Results

![](sensor.jpg)
Fig. 1 Sensor.

![](rpi.jpg)
Fig 2. Raspberry Pi with USD sound adaptor.

![](1.png)
Figure 1. Spectrogram of 1.wav. Note the insect wingbeat harmonic series at about 20s.

![](2.png)
Figure 2. Spectrogram of 2.wav.

![](3.png)
Figure 3. Spectrogram of 3.wav. These signals are probably caused by parts of a small cloud moving over the sun.

![](4.png)
Figure 4. Spectrogram of 4.wav.
