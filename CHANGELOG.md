# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and follows
the changelog [Keep a changelog](http://keepachangelog.com/)

## Unreleased
- Modified log2ram to clear blocking files if not enough space at start (SB-1448)
- Modified doLogrotate to record a verbose copy of what's done by logrotate (SB-1448)
- Modify logrotate config for the log2ram log to record 8 days with copytruncate (SB-1448)
- Modified syncFromDisk to use CUSTOM_SYNC_FROM_DISK_FIND to caluclate needed disk space (SBR-398)
- Added CUSTOM_SYNC_FROM_DISK to provide a more customizable copy back from FDisk to RAM to avoid archive maintenance from being copied back to RAM Disk (SBR-377)
- Changed to add LOGROTATE_SYNC_CONFIG to switch off logrotate timer and integrate calls from log2ram