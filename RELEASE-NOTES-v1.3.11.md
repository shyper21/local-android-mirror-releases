# MirrorSync v1.3.11

Native mirror shell and Wireless Debugging stability hotfix.

## Changes

- Keeps disconnected mirror sessions visible with clear reconnect status.
- Adds bounded automatic WiFi ADB and scrcpy reconnect with Retry Sekarang and Tutup Mirror controls.
- Reconnects Android 11+ mDNS serials without changing the saved device identity or alias.
- Prevents duplicate scrcpy processes during repeated retries.
- Keeps one native Android mirror shell open when scrcpy disconnects.
- Retains the last Android frame in memory and displays a translucent Retry Connection overlay.
- Re-embeds the reconnected scrcpy process into the same native shell window.
- Uses UHID for Auto keyboard mode and only falls back for confirmed UHID startup errors.
- Preserves the hidden detached backend launcher and PID-scoped scrcpy console hiding.
- Keeps USB ADB, Wake Up, Always On Top, renderer fallback, diagnostics, and port fallback behavior.

## Release note

This release supersedes v1.3.10. Existing v1.3.10 assets are not overwritten.
