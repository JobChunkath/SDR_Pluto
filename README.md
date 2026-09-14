Software Defined Radio (SDR) Lab Repository

Welcome to the official repository for Part C: Software Defined Radio of the Communication Lab I (PCECL508) APJ AK KTU 2024 curriculum for Semester 5 (S5).

This repository serves as a hands-on guide and codebase for emulating real-time wireless communication systems using the ADALM-PLUTO (PlutoSDR) active learning module alongside GNU Radio Companion (GRC).

Course Overview
Software Defined Radio (SDR) transforms traditional, hardware-centric communication infrastructure into flexible, software-configurable signal processing pipelines. By combining dedicated RF front-end hardware with open-source software environments, this lab explores the fundamentals of RF signal generation, transmission, reception, spectral analysis, and digital audio processing.

Hardware & Software Environment
Hardware: ADALM-PLUTO SDR (Analog Devices)
Software: GNU Radio / GNU Radio Companion (.grc flowgraphs)
Interface: USB / IP Networking (PlutoSDR Driver & Blockset)

Lab Experiments
This repository is structured around the core SDR curriculum modules:

Exp 1: SDR Hardware & GNU Radio Companion Familiarization
RF Front-End Integration: Interface the ADALM-PLUTO board with the host PC for dual-channel (Tx/Rx) RF operations.
Flowgraph Design & Signal Generation: Configure basic signal sources and observe signal characteristics using GNU Radio blocksets.
Spectral Analysis & Filtering: Analyze Power Spectral Density (PSD) and Fast Fourier Transforms (FFT) across various signal types, and implement low-pass/band-pass filtering.

Exp 2: FM Signal Reception
RF Digitization: Capture live broadcast FM signals centered at local clear-channel frequencies using the PlutoSDR source block.
Demodulation & Filtering: Design Low-Pass Filter (LPF) stages and quadrature FM demodulation flowgraphs.
Audio Resampling & Sink: Downsample audio streams to standard sample rates (e.g., 44.1 kHz / 48 kHz) for real-time playback via computer speakers while displaying live spectrum sinks.

Exp 3: FM Signal Transmission
Audio Source Processing: Ingest custom .wav audio files as modulating signals. (Please note that a audio file is not provided in this repository; you will need to use your own .wav file.)
Transmitter Architecture: Implement rate matching, interpolation, and wideband FM modulation stages.
Over-the-Air (OTA) Transmission: Route the modulated baseband signal to the ADALM-PLUTO sink for transmission over specified ISM/RF bands.
