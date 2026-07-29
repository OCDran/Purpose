---
name: purpose-unattend
description: Select and begin a task that advances the goal in Purpose/Config/PURPOSE.md. Use only when the user explicitly invokes $purpose-unattend.
---

# Purpose Unattend

When explicitly invoked, use the configured Purpose to begin one concrete task without waiting for the user to define that task.

## Procedure

1. Resolve the Workspace as the directory three levels above this skill directory.
2. Read `Config/PURPOSE.md` from the parent Purpose folder. Treat it as set only when it contains non-whitespace content.
3. If Purpose is unset, do not start a task; report that no Purpose is configured.
4. If Purpose is set, use it as the goal and apply the Workspace instructions and Concepts to select one safe, in-scope task that materially advances it.
5. Prefer a task that can begin and produce a useful outcome in the current turn.
6. Ask a focused follow-up question only when the task requires a material user choice or new authority; otherwise begin and execute the task.
7. Do not modify `Config/PURPOSE.md`.
8. Complete the normal post-task operations and report the outcome.
