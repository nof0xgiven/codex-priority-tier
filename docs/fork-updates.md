# Fork updates

This file tracks fork-specific changes so upstream updates can be rebased cleanly.

## 2026-01-27
- Added config-level `service_tier` (e.g., "priority") and threaded it through Responses/Chat requests.
- Exposed `service_tier` in app-server protocol (v1/v2) and the config schema.
