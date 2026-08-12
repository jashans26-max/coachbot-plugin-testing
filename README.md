# Coachbot Plugin

Early skeleton for testing plugin infrastructure — loading, GitHub install, slash commands, cross-environment behavior. Not real Coachbot logic yet; the placeholder agent and skill exist only to confirm the plumbing works.

## Structure
- `.claude-plugin/plugin.json` — plugin manifest
- `agents/placeholder-agent.md` — stub subagent to test subagent loading
- `skills/placeholder-skill/` — stub skill to test skill loading and slash-command invocation
- `hooks/hooks.json` — empty hooks config to test hooks loading
