# Agent hook samples

`samples.json` demonstrates every VS Code agent hook event with harmless
`echo` commands. Copy and adapt individual entries for the checks appropriate
to the participant's operating system and repository. For example, a
`PreToolUse` command can reject edits outside an allowed path, while a
`PostToolUse` command can run a formatter or focused test.

Review commands carefully before enabling them: hooks run local commands.
Consult the [VS Code hook documentation](https://code.visualstudio.com/docs/agent-customization/hooks)
for the current schema and event support in your installed VS Code version.
