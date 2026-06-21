# MirrorSync v1.3.11

Stability hotfix for mirror lifecycle and Wireless Debugging.

## Changes

- Keeps disconnected mirror sessions visible with clear reconnect status.
- Adds bounded automatic WiFi ADB and scrcpy reconnect with Retry and Cancel controls.
- Reconnects Android 11+ mDNS serials without changing the saved device identity or alias.
- Prevents duplicate scrcpy processes during repeated retries.
- Uses UHID for Auto keyboard mode and only falls back for confirmed UHID startup errors.
- Preserves the hidden detached backend launcher and PID-scoped scrcpy console hiding.
- Keeps USB ADB, Wake Up, Always On Top, renderer fallback, diagnostics, and port fallback behavior.

## Release note

This release supersedes v1.3.10. Existing v1.3.10 assets are not overwritten.
