# Copilot Instructions for this Repository

- This workspace contains a single Python script: `hello.py`.
- The project has no package manifest, build system, tests, or configuration files beyond the script.

## What to edit
- Only modify `hello.py` unless the user explicitly asks to add new files or project structure.
- Keep changes small and directly aligned with the user’s request.

## Behavior and conventions
- `hello.py` is intended to be run as a standalone Python script.
- The current script simply prints `Hello Saurabh`.
- If you add functionality, preserve the script’s simple execution model and avoid introducing complex dependencies unless requested.

## Execution
- Run with the system Python interpreter available in the workspace environment:
  - `python hello.py`
- There is no existing test runner or linter configured in this repository.

## When requesting changes
- Ask the user before adding new files, directories, or external dependencies.
- If the user asks for a larger application, note that the current repo has no existing app structure to follow.

## Notes
- There is no hidden architecture or service boundary in this repository; the whole codebase is just one file.
- Do not invent project-specific conventions that are not supported by existing files.

## Feedback request
- If any section is unclear or if you want guidance added for a new structure, let me know so I can iterate.