# BodePlotter Pro

## Project Overview
An automated testing and instrumentation system engineered to capture and map the frequency response of hardware circuits. The system leverages optimized low-level firmware to dynamically track real-time gain modifications and phase shift boundaries, translating physical data streams directly into precise frequency response metrics.

## Key Computational Algorithms
* **Simultaneous Pole & Zero Estimation:** Implements concurrent root-finding utilizing the **Durand-Kerner / Aberth-Ehrlich** algorithm to find all transfer function poles and polynomial roots simultaneously in a single computational loop.
* **Optimized Polynomial Evaluation:** Integrates **Horner's Method** within the iterative solver to dramatically minimize complex floating-point multiplications, enabling rapid real-time calculations directly from stream data.

## System Features
* **Firmware Optimization:** Written in highly efficient, low-level execution logic to achieve rapid hardware data sampling and tight hardware-software synchronization.
* **Automation Framework:** Automates data capture sequences across a defined frequency spectrum, eliminating manual oscilloscope/signal generator tracking.

## Repository Contents & Source Code
* **Firmware Core:** View the source code handling processing, timing, and calculation: [C++ Automation Source Code](Code.txt)
* **Technical Documentation:** Read the full report detailing the mathematical validation, transfer functions, and experimental data: [Formal Technical Report (PDF)](Report.pdf)
* **Desktop Application:** Download the compiled system executable package: [BodePlotter Pro App Release (ZIP)](BodeAppDownload.zip)
