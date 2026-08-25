# Firmware Usage Notes

Project: CH32V307 Multirotor Flight Controller

These notes explain how to use the published source archive.

## Recommended Use

1. Download `code/ch32v307-multirotor-flight-controller-source-code.zip` from the repository.
2. Verify the SHA256 checksum listed in docs/SOURCE_CODE.md or docs/SOURCE_MANIFEST.md.
3. Extract the archive into a clean working directory outside the repository.
4. Open the embedded project with the matching WCH / RISC-V MCU development environment.
5. Review source files, project configuration, linker scripts, startup files, and user code before compiling or flashing.

## Safety Notes

- Do not flash firmware to hardware connected to high-power loads before bench validation.
- Use a current-limited power supply for first power-on checks.
- Re-check pin mapping, voltage rails, and peripheral configuration before connecting motors, batteries, or actuators.
