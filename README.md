# Coachbot Plugin

Early skeleton for testing plugin infrastructure — loading, GitHub install, slash commands, cross-environment behavior. Not real Coachbot logic yet; the placeholder agent and skill exist only to confirm the plumbing works.

## Installation

To install this plugin, run:

```bash
claude plugin install coachbot-plugin@coachbot-testing
```

That's it. The plugin will be installed with auto-updates enabled, so you'll automatically receive new versions as they're released.

## Structure
- `.claude-plugin/plugin.json` — plugin manifest
- `agents/placeholder-agent.md` — stub subagent to test subagent loading
- `skills/placeholder-skill/` — stub skill to test skill loading and slash-command invocation
- `hooks/hooks.json` — empty hooks config to test hooks loading
- `.claude/settings.json` — Claude Code configuration (auto-update settings, marketplace source)

## Project Ownership

This plugin is designed to be maintainable by anyone. If the project ownership changes, the new maintainer should:
1. Update the GitHub repository URL if moving to a new account/organization
2. Update `extraKnownMarketplaces` in `.claude/settings.json` if the repo location changes
3. Users will automatically receive updates via the auto-update mechanism
