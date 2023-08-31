# Standard Linear Psu 1993

After reverse engineering an old ham radio psu from 1993, I wanted to use a similar circuit with similar transformers.

I asked for some suggestions on improvements on the electrical engineering stack exchange.

Unfortunately the circuit is weird since it is not a charging circuit just a constant current circuit.

A few big problems are:
- Battery will cause the LM317T to overheat when charging from a low voltage
- Earth and 12v gnd are connected via varistors before fuse.
- Earth seperation is small
- LM317 needs a large heatsink

Add better heatsink with thermal compound is needed