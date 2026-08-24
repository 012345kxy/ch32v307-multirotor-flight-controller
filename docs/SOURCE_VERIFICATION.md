# Source Verification Checklist

Project: CH32V307 Multirotor Flight Controller

Use this checklist to verify that the source-code update is complete and traceable.

## Repository Checks

- [ ] code/ contains exactly one published *-source-code.zip archive.
- [ ] docs/SOURCE_CODE.md lists archive path, entry count, and SHA256 checksum.
- [ ] docs/SOURCE_MANIFEST.md describes archive scope and packaging boundary.
- [ ] README contains a Source Code section pointing to the archive and documentation.
- [ ] CHANGELOG includes the 2026-08-25 source-code update.

## Archive Checks

- [ ] Archive extracts successfully.
- [ ] Archive does not contain nested .git/ metadata.
- [ ] Archive does not contain generated obj/ directories.
- [ ] Archive does not contain common generated files such as .o, .elf, .hex, .map, .lst, or .d.
