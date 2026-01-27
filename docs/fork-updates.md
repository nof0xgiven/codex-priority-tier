# Fork updates

This file tracks fork-specific changes so upstream updates can be rebased cleanly.

## 2026-01-27
- Added config-level `service_tier` (e.g., "priority") and threaded it through Responses/Chat requests.
- Exposed `service_tier` in app-server protocol (v1/v2) and the config schema.

## Maintaining this fork
Use the upstream remote to keep changes rebased on OpenAI’s main branch.

```shell
git remote add upstream https://github.com/openai/codex.git
git fetch upstream
git checkout main
git rebase upstream/main
git push origin main
```
