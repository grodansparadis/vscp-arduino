# Changes in vscp-arduino

Every change that goes into a release is listed here, newest release first.
Add each change under **Unreleased** when it is made. When a release is
tagged, rename **Unreleased** to the version and date, and start a new
**Unreleased** section above it.

## Unreleased

- No changes since the last release.

## v0.3.0 - 2015-08-26

- VSCP framework v0.4.0 merged (7c8e9c3)
- v0.3.0 (b990688)
- Changelog prepared (c62d6cb)
- - Changed the priority for packet bursts of extended read responses to the lowest priority, so other frames win arbitration (e. g. on the CAN bus) when they are sent. This will help other events moving on the bus. - Changed functionality for extended page read request with optional byte. If the optional byte is 0, 256 registers will be read now, instead of 1. (d3e05d1)
- Missing initialization fixed. (ca0960d)
- Keywords and library version updated. (2ec243d)
- - DigInDebounce class for digital input debouncing implemented. - Update to current VSCP framework trunk - Status lamp and init button connection fixed. (0a84749)
- VSCP framework head revision merged (8c76040)
