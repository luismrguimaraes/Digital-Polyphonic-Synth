# Digital Polyphonic Synthesizer

## Includes:
- 3 oscillators, each featuring vector synthesis (for the definition of the waveform);
- An ADSR envelope;
- 16 voices for the 3 oscillators;
- 2 LFOs;
- FM and RM modulation (processed sequentially: FM → RM) for each oscillator;
- An effects section which includes spectral gating and reverb.

## How to run
Clone or download this repository and run `polysynth.pd`. It also runs on [plugdata](https://plugdata.org/), so it can be loaded into its supported DAWs.

**IMPORTANT:** Currently, the patch states **do not save**, so make sure to record your audio before closing your current session. Also, make sure to **use a limiter** or be very careful setting the mod sources because loud feedback may happen.

Note: This project is not very adequate for real-time usage as the patch has too much delay.

## Implementation
For implementation details check [the report](Assignment%202%20-%20Report.pdf).

## Demo


https://github.com/luismrguimaraes/Digital-Polyphonic-Synth/assets/100025288/26e22cfb-ec58-411f-9ef4-27c5c968d6a5



https://github.com/luismrguimaraes/Digital-Polyphonic-Synth/assets/100025288/6ee730b8-e86f-455d-adb3-691c72169544

