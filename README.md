# Claudekit Marketplace

Official marketplace for the [claudekit](https://github.com/duthaho/claudekit) plugin — the development-workflow plugin for Claude Code. 35 skills organized around a 6-phase workflow, 24 agents, and an interactive setup wizard.

## Install

1. Add this marketplace:
   ```
   /plugin marketplace add duthaho/claudekit-marketplace
   ```

2. Install claudekit:
   ```
   /plugin install claudekit
   ```

3. Configure your project:
   ```
   /claudekit:init
   ```

   Or install everything at once:
   ```
   /claudekit:init --all
   ```

## What You Get

- **35 Skills** organized around a 6-phase workflow: Think → Review → Build → Ship → Maintain → Setup
- **13 user-invocable spine skills** — typed directly as `/claudekit:<name>` (brainstorming, writing-plans, autoplan, 4 plan-reviewers, feature-workflow, TDD, systematic-debugging, verification-before-completion, mode-switching, init); the rest auto-trigger by context
- **24 Specialized Agents** — planners, reviewers, implementers, and 4 plan-dimension reviewers (ceo, eng, design, devex)
- **Setup Wizard** — `/claudekit:init` scaffolds rules, modes, hooks, and MCP servers into your project

## Updating

Once installed, update to the latest version with:

```
/plugin marketplace update
```

## Links

- [Plugin repo](https://github.com/duthaho/claudekit)
- [Documentation](https://duthaho.github.io/claudekit)
- [Changelog](https://github.com/duthaho/claudekit/blob/main/CHANGELOG.md)

## License

MIT
