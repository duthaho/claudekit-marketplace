# Claudekit Marketplace

Official marketplace for the [claudekit](https://github.com/duthaho/claudekit) plugin — a verification-first engineering toolkit for Claude Code. Built for senior ICs and tech leads who already know how to ship and want a workflow that keeps the bar high without ceremony.

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

## What you get

- **15 skills** across a 5-phase spine: **Investigate → Design → Implement → Verify → Ship**, plus 1 setup skill (`init`). All user-invocable as `/claudekit:<name>`.
- **8 specialist agents** — `planner`, `architect`, `experience-reviewer`, `investigator`, `tester`, `code-reviewer`, `security-auditor`, `scout`. Each with a single dispatcher and a narrow job.
- **5 output styles** shipped natively — `Brainstorm`, `Deep Research`, `Implementation`, `Review`, `Token Efficient`. Switch via `/config`.
- **Setup wizard** — `/claudekit:init` scaffolds rules, hooks, and MCP server configs into your project's `.claude/` directory.

## What makes claudekit different

- **Rationalizations tables** in every skill. The excuses an engineer makes to skip a step ("I see the problem, let me just patch it") are documented in the skill itself, with rebuttals.
- **Evidence requirements** at every checkpoint. Each phase produces a specific artifact you could paste into a code review.
- **Pre-completion gates.** `verification-gate` runs before any "done" claim — runs the tests, checks the negative path, exercises the change in a non-IDE environment, cross-checks the original ask.
- **Plan-review pipeline as the headline.** Two parallel reviewers (architecture + experience) score 5 sub-dimensions each, consolidate into one fix gate.

## Updating

Once installed, update to the latest version:

```
/plugin marketplace update
/plugin update claudekit
```

## Links

- [Plugin repo](https://github.com/duthaho/claudekit)
- [Documentation](https://claudekit.duthaho.dev)
- [Changelog](https://github.com/duthaho/claudekit/blob/main/CHANGELOG.md)

## License

MIT
