# cheap-modular-synth
The aim of this project is to make a modular analogue-style (note, it will be mostly based on digital modules) synth. It should be understandable to people getting started in electronics and programming. To this aim, the electronics will be as simple as possible. I will try to make it all work with code in CircuitPython, but it's possible that this won't handle some of the more comeplex parts. It'll be mostly based around Raspberry Pi Pico dev boards as these are easily available and cheap.

I've going to try and keep the relationship between voltage and pitch that traditional modulr synths have. However, instead of 1v per octave, I'm going to try for 0.25V per octave. Over the 0-3.3V range, that should give the same range as a traditional modular synth has in the 0-12V range. It'll also mean that with simple voltage amplifiers / dividers you can make a eurorack module work with this system.

## Available modules
* midi-to-cv. This does more-or-less what you'd expect. It takes midi out from a computer's USB port. Note that at the moment it needs a computer as it doesn't run in USB host mode. This might change in the future (or it could use a Midi DIN port), but for now, it's just computer USB.
