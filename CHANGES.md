Changes in PAPPL
================

Changes in v1.3b1
-----------------

- Added timer APIs to manage periodic tasks (Issue #208)
- Added debug logging for device management.
- Fixed a device race condition with job processing.
- Fixed a potential value overflow when reading SNMP OIDs (Issue #210)
- Fixed more CUPS 2.2.x compatibility issues (Issue #212)
- Fixed the default values of `--with-papplstatedir` and `--with-papplsockdir`
  to use the `localstatedir` value (Issue #219)
- Fixed a initialization timing issue with USB gadgets on newer Linux kernels.
- Updated PAPPL to conform to the new prototype PWG 5100.13 specification
  (Issue #216)
