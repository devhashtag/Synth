# Virtual Modular Synthesizer

This file informally describes the specifications of the software. It gets updated over time

## TODO
- [ ] Figure out how to work with time and timing in general
- [ ] Create a specification of the software
- [ ] Choose a development language and target platform
- [ ] Create a list of things one might want to do with the software and list the required functionalities.

## Description

The synthesizer uses modules as building blocks for creating sound. Each module has inputs, outputs and configuration settings. Each output can be connected to an input of another module. The software provides a way to build new modules from existing modules.

Basic modules:
- Oscillator
- Filter
- Sequencer
- Wave visualizer