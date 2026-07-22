# Speaker2Microphone

Transforming a discarded headphone speaker driver into a functional microphone through transducer reciprocity.

## Overview

This project investigates whether a dynamic speaker driver can operate in reverse as a microphone.

A broken Bluetooth headset was disassembled, the speaker driver was salvaged, and electrical signals generated from diaphragm movement were measured, amplified through a standard microphone input, and recorded successfully.

The experiment demonstrates the reciprocal nature of dynamic transducers and highlights the potential of repurposing electronic waste for educational engineering projects.

---

## Objectives

- Verify speaker coil continuity
- Measure generated electrical signals
- Salvage a microphone interface
- Interface the speaker driver with a laptop microphone input
- Record real audio
- Document findings

---

## Key Results

| Measurement | Result |
|------------|---------|
| Voice Coil Resistance | ~17 Ω |
| Maximum Measured Output | 92.7 mV |
| Recording Capability | Successful |
| Platform | Linux (PipeWire + ALSA + Audacity) |

---

## Project Workflow

Broken Bluetooth Headset
↓
Driver Extraction
↓
Resistance Testing
↓
Voltage Generation Tests
↓
TRRS Microphone Salvage
↓
Soldering & Integration
↓
Linux Audio Configuration
↓
Audio Recording
↓
Documentation

---

## Gallery

### Driver Resistance Measurement

![Resistance Test](images/measurements/resistance-test.jpg)

### Voltage Generation Test

![Voltage Test](images/measurements/voltage-generation.jpg)

### Salvaged TRRS Microphone Interface

![TRRS Interface](images/wiring/trrs-interface.jpg)

### Speaker Driver Teardown

![Driver Opened](images/teardown/open-driver.jpg)

### Final Working Setup

![Final Setup](images/final-setup/final-assembly.jpg)

---

## Audio Samples

Audio recordings can be found in:

audio/raw-recordings/

and

audio/processed-recordings/

---

## Technical Report

The complete report is available in:

docs/Speaker2Microphone_Report.pdf

---

## Lessons Learned

- Speakers and microphones share the same electromagnetic principles.
- Salvaged components can be reused effectively.
- Enamel-coated wires require special soldering techniques.
- Linux audio troubleshooting is often as important as hardware debugging.
- Experimental documentation significantly improves project value.

---

## Future Improvements

- Oscilloscope waveform analysis
- Frequency response testing
- Comparison with electret microphones
- External preamplifier stage
- Signal-to-noise ratio measurements

---

## Author

Prateek Sharma

Cyber Security & Digital Forensics
VIT Bhopal University
