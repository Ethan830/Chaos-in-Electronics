# Chaos-in-Electronics
An analog electronics implementation of chaotic systems, physically modeling the Lorenz Attractor and the Jerk Circuit using operational amplifiers, analog multipliers, and diodes.

## Overview
This repository contains the findings and documentation for exploring the analog implementation of chaotic systems. The experiment physically models two renowned systems—the Lorenz Attractor and the Jerk Circuit—using operational amplifiers, analog multipliers, and diodes. 

We derived and verified the ordinary differential equations for both systems against the physical circuits. This was achieved by analyzing the currents across various resistances and utilizing Kirchhoff's laws alongside the op-amp golden rules. Both chaotic systems successfully displayed multiple dynamic regimes, including constant voltage points, stable period motions, and period-doubling cascades.

## Hardware & Components
**Lorenz Attractor Circuit:** Utilized MPY634 analog multipliers and LF412 op-amps.
Jerk Circuit:** Constructed with LF412 op-amps, silicon diodes, 1kΩ resistors, and 0.1µF capacitors.
