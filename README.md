# COMP-435 Final Project: Security Investigation
## DolphinAttack (2017) — Ultrasonic Voice Command Simulation

**Course:** COMP-435 — Computer Security  
**Project:** Security Investigation  
**Research Paper:** [DolphinAttack: Inaudible Voice Commands](https://arxiv.org/abs/1708.09537) (2017)

---

## Overview

This repository contains our COMP-435 Final Project, a simulation inspired by the 2017 research paper **[DolphinAttack: Inaudible Voice Commands](https://arxiv.org/abs/1708.09537)**.

DolphinAttack is a security vulnerability demonstrated by researchers who showed that voice assistants could interpret commands carried through ultrasonic signals, even though those signals are inaudible to humans.

Our project aims to recreate and explore the concepts presented in **Sections 3.1 and 3.2 of the original research paper** through a software-based simulation.

Rather than reproducing the physical attack using specialized hardware, microphones, or ultrasonic speakers, we will model the relevant signal-processing techniques computationally.

## Project Objectives

The primary objective is to build a Python-based simulation that demonstrates the relationship between ordinary speech signals and their ultrasonic frequency-modulated representations.

Our simulation will focus on:

- **Speech Signal Input:** Allow users to provide an existing speech recording as the input to the simulation.
- **Signal Generation:** Generate and visualize a standard sine wave representing an ordinary signal.
- **Frequency Transformation:** Demonstrate how changing the signal frequency affects its waveform and frequency-domain representation.
- **DolphinAttack Modeling:** Use the mathematical principles and signal-processing equations described in Sections 3.1 and 3.2 of the original paper to model the relevant ultrasonic modulation techniques.
- **Signal Visualization:** Compare the original speech signal with the simulated transformed signal using waveform and frequency-domain plots.

## Scope of the Simulation

This project is specifically limited to a software simulation of the concepts presented in Sections 3.1 and 3.2 of the DolphinAttack paper.

**What we intend to implement:**

1. A basic sine-wave generator to establish a baseline signal.
2. A frequency-adjustment demonstration showing how changing frequency affects a signal.
3. A speech-audio input option for experimenting with real audio samples.
4. A mathematical implementation of the relevant modulation techniques described in the research paper.
5. Visual comparisons of the original and simulated signals.

**What is outside the scope:**

- Physical ultrasonic transmission.
- Microphone-based signal reception or recording.
- Dedicated ultrasonic speakers or transducers.
- Testing against real-world voice assistants or smart devices.
- Reproducing the complete physical DolphinAttack system.

The goal is to understand and demonstrate the underlying signal-processing concepts, not to build a functional hardware-based attack.

## Research Reference

Zhang, G., Yan, C., Ji, X., Zhang, T., Zhang, T., & Xu, W. (2017).

**DolphinAttack: Inaudible Voice Commands.**

Proceedings of the ACM Conference on Computer and Communications Security (CCS).

[Research Paper — arXiv](https://arxiv.org/abs/1708.09537)

---

*This repository is maintained as an academic security investigation for COMP-435. All implementations and demonstrations are intended for educational and research purposes.*
