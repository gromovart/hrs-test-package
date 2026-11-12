---
name: review
description: Review changes with evidence in projects with or without Git.
---

Check whether the selected project is a Git worktree before running Git-specific commands.
If Git is available, inspect the requested changes and their relevant callers.
If Git is absent, inspect the supplied files or diff instead. Missing Git metadata is not itself a code defect.
If no source files or diff are available, state that limitation without creating files or claiming a completed code review.
Identify concrete defects, explain their impact, and report file locations and the smallest useful correction.
Separate confirmed findings from questions. Do not modify files, run external commands, or publish changes without the permissions required by the project.
