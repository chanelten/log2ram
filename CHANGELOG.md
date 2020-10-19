# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and follows
the changelog [Keep a changelog](http://keepachangelog.com/)

## Unreleased
- Modified syncFromDisk to use CUSTOM_SYNC_FROM_DISK to caluclate needed disk space (SBR-398)
- Added CUSTOM_SYNC_FROM_DISK to provide a more customizable copy back from FDisk to RAM to avoid archive maintenance from being copied back to RAM Disk (SBR-377)
- Changed to add LOGROTATE_SYNC_CONFIG to switch off logrotate timer and integrate calls from log2ram