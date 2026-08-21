# Orion-Hardware

## 1. Project Summary

Orion-Hardware is the hardware-reference leaf for the Orion platform.

- Unlike Orion-HAL, Orion-Client, and Orion-OS, this repository currently contains no executable driver, firmware, build system, test suite, schematic source, bill of materials, or board-manifest implementation that can be inspected as software.
- Its only tracked project documentation is this README.
- The top-level Orion architecture describes the physical boundary as an Orion hardware interface connected to a Pico W real-time controller.
- That relationship is an ecosystem design reference rather than an implementation found here.

Hardware behavior is represented elsewhere through HAL module libraries, OS device integration, configuration manifests, and client adapters.

- This leaf should become the home for human-owned electrical and mechanical evidence when those artifacts are added.
- Expected evidence includes schematics, PCB or CAD sources, approved BOMs, connector and pin maps, assembly notes, programming procedures, bring-up records, and revision history.
- Until then, it cannot honestly promise a reproducible setup command or device-level usage path.

The inventory separates repository facts from planned documentation.

- “Unknown” means the repository offers no evidence to decide the status.
- “Planned” means the artifact is missing.
- No manual hardware check is marked complete.
- Future additions should identify the board revision, Pico W link and protocol, power and signal constraints, required instruments, acceptance checks, and the Orion-HAL and Orion-OS values they constrain.

## 2. Feature Status

| # | Name / Description | Implemented? | Test Coverage? | Manual Test |
|---:|---|---|---|---|
| 1 | Orion-Hardware repository placeholder | Implemented | Unknown: no tests found | [ ] Manual verification required |
| 2 | Board schematic source | Planned | Not covered | [ ] Manual verification required |
| 3 | PCB/CAD layout source | Planned | Not covered | [ ] Manual verification required |
| 4 | Approved bill of materials | Planned | Not covered | [ ] Manual verification required |
| 5 | Connector, pin, and signal map | Planned | Not covered | [ ] Manual verification required |
| 6 | Pico W hardware link definition | Unknown | Not covered | [ ] Manual verification required |
| 7 | Assembly and bring-up procedure | Planned | Not covered | [ ] Manual verification required |
| 8 | Hardware acceptance records | Planned | Not covered | [ ] Manual verification required |

## 3. Current Validation

No repository-specific build or test command is currently available.
