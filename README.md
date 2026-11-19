# libUITools

AIMMS library (prefix `uit`, one library module) with helpers for converting WinUI
AIMMS applications to WebUI.

- `uit::bp_useWinUI`, `uit::bp_useWebUI`, `uit::pr_DialogProgress`: a progress dialog
  that works in both WinUI and WebUI.
- Notification manager: `uit::pr_addNotification` adds a notification; the
  library's WebUI page `NotificationHandling` shows the list.
