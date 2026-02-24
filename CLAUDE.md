# Ralph Wiggum — Autonomous Agent Loop

Documentation and prompts for the Ralph Wiggum autonomous agent pattern.
The actual plugin lives at `ralph-loop@claude-plugins-official`.

## Contents
- `PROMPT.md` — Core prompt for Ralph Loop behavior
- `WORKFLOW-CHEATSHEET.md` — Quick reference for using Ralph Loop

## Usage
Ralph Loop is invoked via the `ralph-loop` plugin:
- `/ralph-loop` — Start an autonomous loop
- `/cancel-ralph` — Stop the loop
- `/ralph-loop:help` — Get help

## Safety Rules
- Set conservative `--max-iterations` (start with 10-20)
- Always define clear completion criteria
- Review git history after autonomous sessions
- Use for: tests, documentation, refactoring
- Avoid for: security code, architectural decisions
