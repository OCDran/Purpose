---
name: initialize-concepts
description: Reset all eight base Concept Markdown files in Purpose to zero-length files, creating any that are missing. Use when the user explicitly asks to initialize, reinitialize, clear, wipe, or reset the base Concepts.
---

# Initialize Concepts

Reset only the eight base Concept files in `Config/` within the Purpose folder containing this skill. Do not modify `README.md`, either `AGENTS.md` file, or files in `Workspace/`.

## Procedure

1. Resolve the Purpose folder as the directory three levels above this skill directory.
2. For each file below, create it if it is missing. Otherwise, replace its entire contents with nothing:
   - `Config/PURPOSE.md`
   - `Config/IDENTITY.md`
   - `Config/REASONING.md`
   - `Config/SOURCES.md`
   - `Config/VALUES.md`
   - `Config/MOTIVATIONS.md`
   - `Config/PREFERENCES.md`
   - `Config/MEMORIES.md`
3. Verify that all eight files exist and are zero-length.
4. Report that the base Concepts were initialized.
