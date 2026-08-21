# Orion-Hardware Build and Deployment

## 1. Purpose and Scope
Orion-Hardware is currently a reference/documentation placeholder. Its README states that the leaf contains no executable driver or firmware, build system, test suite, schematic source, BOM, board manifest implementation, or deployment script. This guide records that boundary rather than inventing commands.

## 2. Prerequisites
No repository-specific software prerequisites are declared because this leaf has no Makefile or package manifest. For future hardware work, expect revision-controlled schematics/CAD, approved BOM and pin map, a programming/debug probe, power and measurement equipment, and the board's documented host tools.

## 3. Setup
There is no setup target and no installable software package. Read the repository README and the top-level Orion architecture before adding hardware evidence. Any future board revision, Pico W link/protocol, power constraints, and connector mapping should be documented alongside the corresponding source artifacts.

## 4. Build and Compile
No build or compile command is available. Do not run a guessed `make`, CMake, Cargo, Python, or Node workflow against this repository; none is declared by the leaf.

## 5. Test and Lint
No repository test or lint target exists. Software checks belong to the consuming Orion-HAL, Orion-OS, configuration, or client repositories. Hardware acceptance must be defined as revision-specific bench and bring-up procedures when the missing artifacts are added.

## 6. Packaging and Artifacts
No packaging target or generated artifact exists. Future deliverables should identify approved manufacturing outputs, firmware/programming images if applicable, checksums, BOM revision, and the relationship to Orion-HAL/Orion-OS interfaces.

## 7. Deploy, Install, and Run
No deployment, install, or run command is available. There is no cloud deployment path. Programming or assembling a board will require human-owned procedures, a board revision, a safe power sequence, and the appropriate hardware tools; those procedures are not present in this leaf.

## 8. Cleanup
No repository cleanup target exists and no generated build directory is defined. Preserve existing documentation and add cleanup instructions only when a real hardware toolchain or artifact workflow is introduced.

## 9. Hardware, Cloud, and Manual Verification Caveats
This leaf is entirely manual by design at its current state. Nothing here verifies schematics, PCB/CAD, BOM, Pico W connectivity, electrical limits, assembly, programming, or acceptance criteria. Treat all board-level behavior as unverified until revision-specific evidence, measurements, and bring-up records are added. The absence of a Makefile is itself a documented repository fact, not a missing command to infer.
