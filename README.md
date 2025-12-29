# TPM 2.0 Software Emulator

Lightweight TPM 2.0 command emulator for research purposes.

## Features
- Emulates EK, SRK hierarchy
- PCR extend/read simulation
- NV index support
- Basic command dispatching (GetCapability, PCR_Read, etc.)

## Build
```bash
cl /EHsc /Zi main.cpp tpm_emulator.cpp
