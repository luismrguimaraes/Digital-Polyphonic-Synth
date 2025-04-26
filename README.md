# Digital Polyphonic Synthesizer

## Includes:
- 3 oscillators, each featuring vector synthesis (for the definition of the waveform);
- An ADSR envelope;
- 16 voices for the 3 oscillators;
- 2 LFOs;
- FM and RM modulation (processed sequentially: FM → RM) for each oscillator;
- An effects section which includes spectral gating and reverb.

## External libraries required
- [ELSE](https://github.com/porres/pd-else)

## How to run
Clone or download this repository and run `polysynth.pd`. It also runs on [plugdata](https://plugdata.org/), so it can be loaded into its supported DAWs.

**IMPORTANT:** Currently, the patch state **isn't saved**, so make sure to record your audio before closing your current session.

Note: If you need lower latency, remove the [pd fft-spectralGate] FX object. Tested on Pd 0.54-0 and plugdata 0.9.1.

## Implementation
For implementation details check [the report](Assignment%202%20-%20Report.pdf).

## Demo
Full demo [on YouTube](https://www.youtube.com/watch?v=eSdJ8ZwYfUs) and short demo below:

https://github.com/user-attachments/assets/13c59504-d852-443c-b0ec-39d8e99a0fed


