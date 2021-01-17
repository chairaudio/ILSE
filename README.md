# ILSE. An Analog Monophonic Synthesizer Module for Education

<img src="ilse.png">

Ilse is designed as a low cost, easy to build, but still flexible and feature rich synthesizer. 
It is based on Syntherjacks single-chip synthesizer [Totoro](https://syntherjack.net/totoro-1-ic-simple-synth/) and extends the design for voltage control on filter, oscillators and LFO.

Components: 

- two saw tooth oscillators
- brigded-T low pass filter with resonance switch 
- triangle LFO with speed control, and routing to filter or oscillators
- simple mixer and detune for oscillators
- level control
- external filter input

Modulation Inputs: 

- 1V/Oct input for oscillators
- Gate
- Filter Cutoff (exponential)
- LFO Speed (linear, via pin header)
- Oscillator 2 detune (linear, via pin header)

<img src="3d_viewer.jpg">

You can find the [schematic here](ilse.pdf).
