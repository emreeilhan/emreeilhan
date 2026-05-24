# Emre Ilhan

Computer Engineering student focused on **embedded software**, **firmware**, and **low-level security**.

I am building a portfolio around C, x86-64 assembly, ESP32, CAN-oriented tooling, and security-aware systems programming. My goal is not to look like a pure SOC analyst or web developer. I want my work to show that I understand how software behaves close to hardware: memory, timing, protocols, failure modes, and defensive design.

Currently targeting:

- Embedded Software / Firmware Internship
- Working Student Embedded Systems
- Junior Embedded Software Engineer
- Embedded Security / Product Security Internship

I hold Turkish and German citizenship and am open to internship or working-student roles in Germany, DACH, and the wider EU.

## Current Focus

- **C and low-level programming**
  Memory layout, pointers, build systems, CLI tools, testable C modules, and debugging with gcc/gdb.

- **Embedded systems**
  ESP32, hardware-facing software, CAN frame tooling, watchdog/brownout concepts, bootloaders, and protocol parsers.

- **Embedded security**
  Constant-time comparisons, timing side channels, buffer overflows, secure boot concepts, fuzzing, and failure-aware design.

- **x86-64 assembly**
  Small assembly ports and measurement-oriented experiments to understand what the compiler and CPU are actually doing.

- **Reviewer-friendly documentation**
  I try to make projects easy to screen: clear README files, test commands, architecture notes, devlogs, CI, and small reproducible demos.

## Featured Projects

### lowlevel-crypto
C99 low-level security lab: XOR cipher with an x86-64 assembly port, Caesar cipher, djb2 hash, stack buffer-overflow exploit, and constant-time comparison tests. The project is intentionally built without crypto libraries so the mechanics are visible.

- Repo: https://github.com/emreeilhan/lowlevel-crypto
- Focus: C, x86-64 assembly, memory safety, constant-time comparison, testable low-level code
- Proof: test script, sanitizer-based CI, devlog, reviewer fast path in README

### canframe
Zero-dependency C CLI for decoding raw CAN frames from terminal pipelines. Built as a small embedded diagnostics tool rather than a general web or Python project.

- Repo: https://github.com/emreeilhan/canframe
- Focus: C, CAN bus, CLI tooling, embedded diagnostics

### timing-side-channel
Planned embedded/product-security project around early-exit vs constant-time string comparison, measured with rdtsc and clock_gettime, with statistical analysis and an attack write-up.

- Focus: timing leaks, measurement noise, constant-time design, practical security analysis
- Status: roadmap / Linear-tracked project

## Technical Stack

- **Languages:** C, x86-64 Assembly, MIPS Assembly, Python, Java
- **Embedded / systems:** ESP32, CAN bus concepts, gcc, gdb, Makefiles, Linux tooling
- **Security:** memory safety, timing side channels, fuzzing basics, secure boot concepts, threat modeling
- **Dev workflow:** Git, GitHub Actions, documentation, CI, reproducible test commands

## What I Am Looking For

I am looking for roles where I can work close to real systems: firmware, embedded Linux, microcontrollers, automotive software, product security, or low-level software tooling.

The best fit would be a team that values careful debugging, readable C, hardware/software boundaries, and security-aware engineering.

## Links

- Portfolio: https://emreilhan.pages.dev
- GitHub: https://github.com/emreeilhan
- Email: mailto:emreilhan@aol.com
