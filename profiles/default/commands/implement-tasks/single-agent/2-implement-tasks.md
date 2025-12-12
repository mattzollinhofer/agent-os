Now that you have the slice(s) to be implemented, proceed with implementation by
following these instructions:

{{workflows/implementation/implement-tasks}}

## Display confirmation and next step

Display a summary of what was implemented.

IF all slices are now marked as done (with `- [x]`) in tasks.md, display this
message to user:

```
All slices have been implemented: `agent-os/specs/[this-spec]/tasks.md`.

NEXT STEP 👉 Run `3-verify-implementation.md` to verify the implementation.
```

IF there are still slices in tasks.md that have yet to be implemented (marked
unfinished with `- [ ]`) then display this message to user:

```
Would you like to proceed with implementation of the remaining slices in tasks.md?

If not, please specify which slice(s) to implement next.
```

{{UNLESS standards_as_claude_code_skills}}

## User Standards & Preferences Compliance

IMPORTANT: Ensure that the tasks list is ALIGNED and DOES NOT CONFLICT with the
user's preferences and standards as detailed in the following files:

{{standards/*}} {{ENDUNLESS standards_as_claude_code_skills}}
