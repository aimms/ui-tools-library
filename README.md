# libWinUIToWebUI

AIMMS library (prefix `w2w`, one library module) with helpers for converting WinUI
AIMMS applications to WebUI.

- `w2w::bp_useWinUI`, `w2w::bp_useWebUI`, `w2w::pr_DialogProgress`: a progress dialog
  that works in both WinUI and WebUI.
- Notification manager: `w2w::pr_addNotification` adds a notification; the
  library's WebUI page `NotificationHandling` shows the list.

Merged from the former libraries `libw2w` and `NotificationManagerLibrary` (prefix `nml`).
