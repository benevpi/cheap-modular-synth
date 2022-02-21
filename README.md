# cheap-modular-synth
The aim of this project is to make a modular analogue-style (note, it will be mostly based on digital modules) synth. It should be understandable to people getting started in electronics and programming. To this aim, the electronics will be as simple as possible. I will try to make it all work with code in CircuitPython, but it's possible that this won't handle some of the more comeplex parts. It'll be mostly based around Raspberry Pi Pico dev boards as these are easily available and cheap.

## Available modules
* midi-to-cv. This does more-or-less what you'd expect. It takes midi out from a computer's USB port. Note that at the moment it needs a computer as it doesn't run in USB host mode. This might change in the future (or it could use a Midi DIN port), but for now, it's just computer USB.
