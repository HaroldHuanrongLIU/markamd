# stale docs

last checked: 2026-07-09

This is the short parking lot for open feedback that is not in the current release yet.

## next todo

- #98 `[feedback] Entry Optimization`
  - Newest open issue.
  - Triage first: confirm what "entry" means in the report, then decide whether this is startup/open-with, welcome flow, command entry, or file-entry UX.
  - Candidate for the next small release if the change is focused.

- #97 `[feedback] The preview can be displayed in a separate window`
  - Separate preview dialog/window is not shipped in v1.5.18.
  - Likely shape: command palette action, optional shortcut/help copy, Tauri child window, active-tab preview sync, clean close behavior.
  - Keep open until implemented and verified.

## later backlog

- #72 `[feedback] feature request, need plantuml support`
  - Keep as a larger renderer follow-up.
  - Needs design for local PlantUML rendering, remote/server rendering, or explicit unsupported-state messaging.

## release thought

- Possible follow-up release target: 2026-07-10 or 2026-07-11 if #98 or #97 lands cleanly.
- Do not bundle broad renderer changes with a small UX fix unless tests stay simple.
